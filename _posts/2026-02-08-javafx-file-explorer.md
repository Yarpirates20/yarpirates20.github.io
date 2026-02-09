---
layout: post
author: Rob Samoraj
tags: [java, gui, file]
---

I made a file explorer for a programming class using JavaFX to create the GUI. The splash page for the program has a giant eye, since a user LOOKS at files in a file viewer. Witty! [^1]

![splash page](assets/images/java_file_viewer_project/splash_page.png)

File Explorer lets you:

1. Opens the file chooser dialog and pick a file or directory.
2. Look at a chosen files/directories attributes.
3. List the contents of a directory.
4. Exit gracefully.

---
![directory info](assets/images/java_file_viewer_project/directory_info.png)

This is the directory info view. The directory view and file view are very similar, but different dialog windows are opened depending on which drop down menu item is chosen. 

Below is the file info view.

![file info](assets/images/java_file_viewer_project/file_info.png)

And then you can see the directory view below. It starts out empty then populates the explorer with a list of files once you provide a path.

![directory view](assets/images/java_file_viewer_project/directory_view.png)

You can find the source code for this exquisite File Explorer at it's Github repo: 

[FileExplorer](https://github.com/Yarpirates20/FileExplorer)

---
{: data-content="footnotes"}

[^1]: This image was created using GIMP.