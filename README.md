# folder-enumeration
The application is used to generate an index of folders, adding the prefix of the number in front of it.

Example:

Folders:

  * folderA
  * folderB
  * folderC

enumeration-config.txt:

  * folderB
  * folderA
  * folderC

output:
  * 1-folderA
  * 2-folderB
  * 3-folderC

If the application is run without an existing enumeration-config.txt file, it is automatically generated. 

Then, you can modify it and run the application again. 
