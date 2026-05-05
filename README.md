Task 1: Basic File Reading
•	Read the file using: 
o	read() 
o	readline() 
o	readlines() 
•	Print: 
o	Total number of lines 
o	First 2 lines 
o	Last 2 lines
Task 2: Log Classification
•	Count: 
o	Number of keywords “INFO”, “WARNING”, “ERROR” 
•	Store results in dictionary
Task 3: Write Filtered Files
Create 3 files:
•	info_logs.txt to store the lines containing keyword “INFO”.
•	warning_logs.txt to store the lines containing keyword “WARNING”.
•	error_logs.txt to store the lines containing keyword “ERROR”.
Use:
•	write() 
•	writelines() 
Task 4: Search Feature
•	Ask user for keyword (e.g., ERROR) 
•	Print matching lines 
•	Save results in search_result.txt
File Pointer (seek) Operations ⭐ (Important)
Perform:
1.	Open file in read mode 
2.	Read first 50 characters 
3.	Move pointer to: 
o	Beginning → seek(0) 
o	Middle → seek(len(file)//2) 
o	Last 100 chars → seek(-100, 2) 
Print content after each move
