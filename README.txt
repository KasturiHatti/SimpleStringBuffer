Here are the key points I followed to implement StringBuffer-

1. Constructor for the user to define size for the buffer.
2. append method that takes object as the parameter
  a. convert the string/integral to char array
  b. caclulate the length of char array.
  c. if char array length is more than buffer size, increase the buffer size(newLength() returns new length)
  d. else copy each character to buffer
3. toString() to return stringified version of the buffer.
4. Test cases to check append method - 
  a. pass the string
  b. pass any integral
  c. pass null and check if exceptions are handled properly