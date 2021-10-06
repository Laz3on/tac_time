Project overveiw:



Applications:

tac_time_display
Single Line display report
Showing tac time (countdown timer)
Completed = Quantity of completed units
Goal = Sum of units to be completed (qty * tac time counter)
Difference = Completed - Goal (color coded for visibility)

logic
tac time 5 seconds
for every 5 seconds the Goal goes up by 1

Tac time set my ENG based on study, hard coded by WO type

DB Connections
Completed units = pull qty completed from eFoxSFC DB
tac time = based on WO group (Mouse, Kybd....) tac time set based on first unit of WO

tac_time_multi_display
Display each lines data in a table where supervision is able to see the entire operations status

Project DB
table for material and tac time
table for line - goal - completed
