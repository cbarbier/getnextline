# Getnextline
Function that allows you to read line by line from a several file descriptor.\
Each call stores the result of the next line at the address sent in parameter.
## prototype
```int get_next_line(const int file_descriptor, char **address_of_line);```
## return value 
* `1` some line left
* `0` end of file
* `-1` an error happened
