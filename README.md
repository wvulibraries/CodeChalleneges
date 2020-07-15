# Code Challeneges

## Correct_CSV

This challenge addresses a common problem amoung data that we deal with in the library.  This is not real data so the contents of it really do not matter, however the end file you create must match this file in terms of data integrity.

Goals:
1. Do not lose any of the data
2. Correct the data doing the following 
  - `first_name` and `last_name` need to be standardized into title case (Ex: SMITH or smith should be changed to Smith).
  - `username` field should have all the content formatted to lowercase.  
  - Both `start_date` and `end_date` fields should be modified to be mm/dd/yyyy (Ex: 12/02/2020) 
  - Content inside the `content` section should have the `data_embed(%%)` removed and should just be represented as a String in that column.   
  - Save the updated csv as `corrected_data.csv` 
3. Bonus: Identify and correct the `uuid` section for any records that have duplicate `uuid`.  Put all of the `id` numbers of rows that have duplicate `uuid` numbers in a sperate text file named `bonus.txt`.
4. Save the code you wrote as `csv_fix_lastname` where lastname is your lastname. 
5. 


