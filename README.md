#  SED : STREAM EDITOR 
## USES :
- modify text in files 
- make changes on screen 
- delete a particular set of information
- changes even a single character 
- add comments before/ after 
- add text before/after a line

#### **BASIC SYNTAX**: sed 's/oldtext/newtext/ '
**S** MEANS : Substitute

`$ echo "this is SEM I result" | sed 's/I/II/' `

>  **Output** 
  ` this is SEM II result `
 
 Consider: 
 > ` $ echo "Johny Johny Yes Yes Papa \n Eating sugar Yes No Papa..!" | sed 's/Yes/No/' `
 
 > **Output**:
  ` Johny Johny No Yes Papa \n Eating sugar No No Papa..! `
  
 Similarly : 
- To replace each occurence use global at the end 
- Save directly to the file : -n 
  
Referrence Article : 
[https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/] (REFERENCE ARTICLE) 

  

 
