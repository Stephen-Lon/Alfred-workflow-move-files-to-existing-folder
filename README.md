# Alfred-workflow-move-files-to-existing-folder

# Introduction

This workflow takes a file or files selected in Finder and moves them to an existing folder and then opens that folder to reveal the contents of it.

# Usage

1. If you want to use a hotkey to launch the workflow double click on the hotkey action in the workflow, press the key combination you want to use then click on `Save`.

2. To use the workflow simply select a file or files in Finder then press either:
- your hotkey; or
- your Universal Action hotkey (if this workflow title does not appear at the top of the list of your Universal Actions start typing `Move` until you see the name of this workflow).

![Move](https://github.com/user-attachments/assets/fe00da4a-8e97-40b4-bb52-95346fad1c6f)

3. Choose the folder to which you wish to move the file or files. Just start typing the name of the folder to see a list of matching folders from which you can select the appropriate one. (See also the important note below about discovery of folders.)

![ChooseFolder](https://github.com/user-attachments/assets/996945e4-a873-4d37-8169-0265f8310659)

The files will be moved (not copied) to the folder (note that existing files will not be overwritten) and the folder will be opened.

# Important note

- In order for a folder to be found in the second step of the workflow *it must be within your default search scope*. (See `Alfred Preferences → Features → Default Results` and look under `Search Scope`.) However, if you want to be able to find folders outside that scope just double click on the workflow `File Filter`, go to `Scope` and drag in the folder(s) you wish to be included within the file filter search scope. *Note that if you do that you'll also as well have to drag in the folders that are within your Alfred search scope*. If you don't do that the folder search will be limited only to the new folders you have dragged in.
