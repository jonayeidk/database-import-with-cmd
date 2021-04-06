# database-import-with-cmd


# Step 1 
  Go to c:\xampp\mysql\bin\
# Step 2   
  then Open your Command Prompt.
  
# Step 3  
  Now Run MySQL login command: 
  
       mysql -u root -p
       
  It will ask for password. Just click Enter button if you have no password.
  
# Step 4
  Select the database using command:  
        
      use your_database_name
  
# Step 5  
  Provide the file name \.your_database_local_path.sql.
  use command : 
    
      source \.your_database_local_path.sql
