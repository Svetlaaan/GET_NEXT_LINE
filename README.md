# GET_NEXT_LINE 124/100

This project is written in C.

**The goal of project:**  
to code a function that returns a line ending with a 'newline', read from a file descriptor and be able to manage multiple file descriptor.  
## Project Description  


This project is a function who reads and returns the next line of a file prototyped as such:  

```  
int get_next_line(int const fd, char **line);  
```
<ul>
  <li>The first parameter is the file descriptor that will be used to read</li>
  <li>The second parameter is the address of a pointer to a character that will be used
    to save the line read from the file descriptor</li>
   <li>Function get_next_line must return its result without ’\n’</li>
  <li>The function will return 1 if successful, 0 if the file has nothing to read, and -1 if there is an error
  </li>
</ul>
