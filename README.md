# My hello world

X = seq(1:7);
Text1 ="I enjoy riding my bike, pray, and the science";
Text2 = "Only see the sea";

for (i in seq_along(X)){ # Contition for all element in the range between 1 to 7  
  if (i <7){             # Condition to select only numbers lower than 7          
    print(Text1)         # Iterated element                                       
  } else {               # Condition to change the element iterated               
    print(Text2)         # New iterated element                                   
  } 
}
