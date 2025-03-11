# Write the psuedocode
START  
SET list = [your_list]  
SET n = length(list)  

FOR i = 1 TO n - 1  
SET key = list[i]  
SET j = i - 1  

WHILE j >= 0 AND list[j] > key  
SET list[j + 1] = list[j]  
SET j = j - 1  
END WHILE  

SET list[j + 1] = key  
END FOR  

PRINT "Sorted List:", list  
END  
