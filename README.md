## FileTransaferUtility

This little project should make it easier to transfer files and folders 
from one place to another over most Protocols like SSH/SFTP/FTP/FTPS/HTTPS.

The entire project is written in PHP without a third-party library.

I'm happy if you can give me feedback on my code(-style) and solutions if you think it can be solved more easily.

Methods which will be included:

##### -> listFiles
    |-> List all Remote Files in the current folder (not recursive)
##### -> listFolders
    |-> List all Remote Folders in the current remote location (not recursive)
##### -> download
    |-> Download one or more files to local system
##### -> upload
    |-> Upload a local file to remote server
##### -> transfer
    |-> Transfer a file if possible from one server to another
##### -> delete
    |-> Delete a file from server
##### -> move
    |-> move one or more files from one directory to another on the server