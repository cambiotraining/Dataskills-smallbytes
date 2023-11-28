# Missing data (or "Sherlock Holmes and the case of the Missing Data"   

## The nature and classification of missing data   
### MCAR   
### MAR   

<HR>

## Finding missing data (or rather detecting it)   
is.na()
which(is.na())
sum(is.na()
<HR>

## Strategies for dealing with missing data (and their consequences).   
### Remove it (It didn't happen)
na.omit()
na.exclude()
na.rm = TRUE in functions like mean() & median()
### Replace with average
### Last known value
