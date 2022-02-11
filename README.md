# Windows 11 Memory Leak Fix
Fix the memory leak problem in Windows 11 by deleting the Stanby Memory Cache every 5 minutes.


## Instructions

 * Clone the repo to wherever you want and copy the `EmptyStandbyList.exe` file into `C:\`.
 * Open `Task Scheduler` and import the `ESM.xml` file to create the automated task.
 * Finally run the newly created ESM task.