![image](https://github.com/user-attachments/assets/c9956445-9b55-4e18-ac20-7a8bdde93005)

MindU is a lightweight standalone suite for task management & mind maps creation, 
wrapped around node-based UI. It is a pure and minimalistic solution aimed at 
individuals, aimed to provide a "quick and dirty" solution for cases where
the heavyweight platforms like Monday or Trello are an "Overkill". 
As such - MindU doesn't provide users with the abilities to assign tasks between
multiple users or teams, nor the ability to synchronize tasks or projects between
devices. 

In basic terms: No Back-end, No cloud or server based syncing and storage, No frameworks. 
Everything is wrapped inside a single HTML file with use of JS and CSS. The data is always
stored in a localstorage, with the ability to export and import all the workspace as a CSV.  

Functionality is based around bare minimum of CRUD (Create, Read, Update, Delete) of nodes,
each representing a task. Each node has a Title, Type, Priority level, Current Status, Deadline
and Description properties which can be edited after the node is created. The design features
"parenting" approach, where multiple sub-tasks can be connected to a "parent" task or project.
These connections are seen as dashed lines or spaghetti, connected to relevant nodes for ease
of tracking. 

Each node can be panned or moved around the canvas which can be zoomed in and out, thus 
allowing it to accomodate a large number of nodes(tasks). Each node is color coded, based
on priority level. Tasks with "DONE" status are designated with a clear (V) icon on their
top left corner. 

Navigation buttons in bottom right of the canvase are providing the ability to:
Zoom in and out, Fit the canvas view to show all existing nodes, Search a specific node
by typing in a string in search modal window (Enter cycles between results, Esc exits the modal),
and Filter the shown nodes by their Status and/or Priority.

