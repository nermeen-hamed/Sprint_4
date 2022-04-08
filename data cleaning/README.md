In these tasks I used:

•	Isna()

•	dropna(axis=0 or axis=1,inplace =True)

•	fillna(method='bfill')

•	to_datetime(columnsName,format="%m/%d/%Y")
   
•	decode()

•	encode()

•	fuzzywuzzy.process.extract(string_to_match, strings, 
   limit=10, scorer=fuzzywuzzy.fuzz.token_sort_ratio)






Explanation of each method:

•	isna() : return True if there is none value

•	dropna() : drop column or row that contain NAN

•	fillna():which fill the place with value of back index

•	to_datetime ():convert column to date type with this format

•	decode():convert encoded bytes to characters

•	encoded():encode the characters

•	fuzzywuzzy.process.extract(string_to_match, strings, 
   limit=10, scorer=fuzzywuzzy.fuzz.token_sort_ratio): it’s  a function
that return the most 10 values (string_to_match) that similar to string 


