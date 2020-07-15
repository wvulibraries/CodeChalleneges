# Correct_CSV Instructions 

When migrating data or moving data to other systems they are often sent in CSV files.  These files are what we typically use to correct data and send it back to whatever system needs the data.  This task proves you can use programming skills to modify data in a CSV file without losing the integrity of the data.

## Programming Language 
You may use any programming language you know, but we are primarily interested in Ruby, PHP, and JavaScript.  There may be other libraries out there that can help with these tasks, please do not use them unless they are part of the core langauge (examples would include JSON and CSV addons in ruby that are part of the ruby standard library). You may use regular expressions. 

## Goals:
1. **DO NOT LOSE ANY DATA**
2. **Correct the data doing the following Tasks**
  - `first_name` and `last_name` need to be standardized into title case (Ex: SMITH or smith should be changed to Smith).
  - `username` field should have all the content formatted to lowercase.  
  - Both `start_date` and `end_date` fields should be modified to be mm/dd/yyyy format. (Ex: 12/02/2020) 
  - Content inside the `content` section should have the `data_embed(%%)` removed and should just be represented as a string in that column.   
  - Save the updated csv as `corrected_data.csv` 
3. **Bonus:** Identify and correct the `uuid` section for any records that have duplicate `uuid`.  Put all of the `id` numbers of rows that have duplicate `uuid` numbers in a sperate text file named `bonus.txt`.
4. Save the code you wrote as `csv_fix_#{lastname}_#{firstname}` changing lastname and firstname to your names. 
5. Attach instructions to run your code as a `README.md` file. 
6. Save your code, csv, and instructions in github either as a github repository or github gist.  You may use other services as long as the code, csv, and instructions are viewable.  


