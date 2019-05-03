# Fisdom_Assignment

Export Table Content To CSV File - JQuery
  This is a sample implementation of export table data to csv file using standard jQuery library.
  
  
  
export2CSV()
  - Parameters:
    + @filename is name of the file given to download
  - functionality:
		+ This function helps in finding table data with respect to rows and columns and store in a variable as a string data with comma seperated which is supported CSV format
  
  
  
  
download()
  - Parameters:
    + @csv is the table data in string concatenated with column and row delimiter
    + @filename is name of the file given to download for export
    + @type is extension for downloading with specific MIME type
  - functionality:
		+ This function tries to download a file by creating a blob of table data string from export2CSV() 
  
	
Usage:
	call function 
		- export2CSV('custom_export_name.csv'); //It finds table and its body contents and pass those data to download function for downloading the file
		
