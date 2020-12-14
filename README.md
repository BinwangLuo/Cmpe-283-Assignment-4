# Cmpe-283-Assignment-4  
### Q1. For each member in your team, provide 1 paragraph detailing what parts of the lab that member implemented / researched.  
I did this assignment by myself. Just need to do the same steps in assignment 3 and get the results in shadow paging.  
### Q2. Include a sample of your print of exit count output from dmesg from “with ept” and “without ept”.  
As we can see the results for shadow paging,  
 $./a.out CPUID(0X4FFFFFFE), exit number=10, number of exits = 156810  
 Which is more than in nested paging. 
### Q3. What did you learn from the count of exits? Was the count what you expected? If not, why not?  
The count of exits in the nested paging is less than the count in shadow paging.  
The count of exits is expected.  
Because: 
In the nexted paging, 
### Q4. What changed between the two runs (ept vs no-ept)?
 If there is no-ept, the exits' count will be more than when there is ept. When there is ept(to nested paging), there are more locations, then it will access more memory than there is no-ept (shadow paging). 
