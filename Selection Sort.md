# Write the psuedocode
START  
SET list = [your_list]  
SET n = length(list)  

FOR i = 0 TO n - 1  
SET min_index = i  
FOR j = i + 1 TO n - 1  
IF list[j] < list[min_index]  
SET min_index = j  
END IF  
END FOR  
SWAP(list[i], list[min_index])  
END FOR  

PRINT "Sorted List:", list  
END  

