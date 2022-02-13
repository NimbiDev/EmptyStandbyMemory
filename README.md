# Windows Memory Leak Fix

Fix the memory leak problem in Windows by clearing the stanby memory cache every 5 minutes after logon.

![Untitled](https://user-images.githubusercontent.com/17615050/153669622-830ef734-af54-453b-84ff-1da3b4891ea7.png)

## Instructions

 * Download the repo via the link belowa and copy the  `EmptyStandbyList.exe` file found inside into `C:\`.
 * Open **Task Scheduler** and import the `Empty Standby List.xml` file to create the automated task.
 * Run the `Empty Standby List` task.

 Once you have completed the above steps, restart your PC and the Memory Leak Fix should be setup and automated.

 ## Download

  * [MemoryLeakFix.zip](https://github.com/DevCorner-Github/Memory-Leak-Fix/archive/refs/heads/main.zip)
