# Mongo Db Backup and Dump
Mongo Db Backup and Dump into new Database

1.Dump Database In Local From Mongo Database
2. Create Folder "Dump" In Bin Folder of Mongo Folder Of C Drive
"C:\Program Files\MongoDB\Server\3.4\bin"

Open CMD as Administrator Mode and Then 
cd C:\Program Files\MongoDB\Server\3.4\bin

Run Command : mongodump and Enter

Backup is Ready now : in Dump folder
***************************************************************************************************************************************
2. Restore Database In Mongo Database
...../bin  mongorestore --db <NewDatabaseName> dump/<DatabaseName>
  
  NewDatabaseName : This is new Database Name and this db name will set in mongo Database name.
  DatabaseName: This is backup database name which is backuped in dump folder.
