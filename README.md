# database-import-with-cmd


# Step 1 
  Go to c:\xampp\mysql\bin\
# Step 2   
  then Open your Command Prompt.
  
# Step 3  
  Now Run MySQL login command: 
  
       mysql -u root -p
       
  It will ask for password. Just click Enter button if you have no password.
  
# if you face an error like 
mysql : The term 'mysql' is not recognized as the name of a cmdlet, function, script file, or operable program. Check
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ mysql -u root -p
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (mysql:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
then go to env and edit the path and add c:\xampp\mysql\bin\ 

  
# Step 4
  Select the database using command:  
        
      use your_database_name
  
# Step 5  
  Provide the file name \.your_database_local_path.sql.
  use command : 
    
      source \.your_database_local_path.sql
