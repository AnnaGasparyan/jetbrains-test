# Local History

Local history is a built-in real-time version control system. Every time you edit a project, a snapshot is added to the local history. You are always able to view all previous versions of the project, compare them to each other, or restore any of them.

**Important** Local history is cleared in case of IntelliJ IDEA update or cleaning out the system caches. Be sure you checked in all the changes to external version control system before performing these operations.

[View and restore changes](view-and-restore-changes)
[Add labels](add-labels)
[View recent changes](view-recent-changes)

## View and restore changes

Track changes of specific folders, files or even blocks of source code:

1. Select an object to track.
2. Right click on the selection and choose **Local History** → **Show History**.
3. Use the list on the left to switch between versions.
4. Restore any version using the **Revert** button.

[More about files and folders history](#files-and-folders)
[More about source code history](#source-code-blocks-classesand-methods)

### Files and folders

To track changes of a specific file or folder:

1. Select a file or folder in the Project tool window or open a file in the editor.
2. Open the local history view by one of the following:
  * Click **Local History** → **Show History** on the context menu or on **VCS** menu.
  * Press *Alt+Back Quote* and click **Show History**.
3. Select the appropriate version from the list on the left. Check differences in the area on the right.
4. If necessary, restore the whole file or folder (**Revert**) or revert changes one by one (**>>**).

### Source code blocks, classes and methods

In addition to files you can track changes of a specific class, its elements or arbitrary block of source code:

1. Select a class, method, field or fragment of source code in the editor. You can also select a class in the Project tool window. 
2. Click **Local History** → **Show History for Class/Method (Field)/Selection** on the context menu or on **VCS** menu.
3. Select the appropriate version from the list on the left. Check differences in the area on the right.
4. If necessary, restore the whole selection (**Revert**) or revert changes one by one (**>>**).

## Add labels

Mark stable versions of a project with labels. Labels help you quickly to roll back to a safe version.

1. Click  **VCS** → **Local History** → **Put Label** or press *Alt+Back Quote* and click **Put Label**.
2. Name your label. Try to make it meaningful.
3. Label applies to the whole project. It appears in local history of any file or folder.

## View recent changes

IntelliJ IDEA provides a summary of recent changes of all your projects including configuration files of the IntelliJ IDEA itself.

To view the recent changes:

1. Click  **View** → **Recent Changes** or press *Shift+Alt+C*.
2. Select the appropriate change from the list.
3. Review the differences in the window opened.
4. Discard any change using the **Revert selection** button.
