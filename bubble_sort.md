# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START  
SET list = [your_list]  
SET n = length(list)  
SET swapped = TRUE  

WHILE swapped == TRUE  
SET swapped = FALSE  
FOR i = 0 TO n - 2  
IF list[i] > list[i + 1]  
SWAP(list[i], list[i + 1])  
SET swapped = TRUE  
END IF  
END FOR
SET n = n - 1  
END WHILE  

PRINT "Sorted List:", list  
END  

```
