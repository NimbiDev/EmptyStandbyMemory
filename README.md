# Windows Memory Leak Fix

Fix the memory leak problem in Windows by clearing the stanby memory cache every 5 minutes after logon.

![Untitled](https://user-images.githubusercontent.com/17615050/153669622-830ef734-af54-453b-84ff-1da3b4891ea7.png)

## Instructions

 * Clone the repo to wherever you want and copy the `EmptyStandbyList.exe` file into `C:\`.
 * Open `Task Scheduler` and import the `ESM.xml` file to create the automated task.
 * Run the `MemoryLeakFix` task.

 Once you have complted the above steps, restart your PC and the Memory Leak Fix should be setup and automated.
