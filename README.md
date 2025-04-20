 python-week-5
Explanation of the Code:
Function Definitions:

read_file(file_path): Attempts to read the content of the specified file. It handles FileNotFoundError and PermissionError to provide user-friendly error messages.
write_file(file_path, content): Writes the modified content to a new file and handles potential permission issues.
modify_content(content): A placeholder function that modifies the content. In this example, it converts the text to uppercase, but you can customize it as needed.
Main Function:

Prompts the user for a filename.
Calls read_file to read the content.
If the content is successfully read, it modifies the content and writes it to a new file prefixed with "modified_".
Error Handling: The program includes error handling to manage common file-related issues, ensuring that the user receives clear feedback if something goes wrong.

Usage:
Run the program, and when prompted, enter the name of the file you wish to read. The program will create a new file with the modified content in the same directory.