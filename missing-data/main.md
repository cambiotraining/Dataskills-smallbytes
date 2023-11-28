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
This has the advantage of being simple to do but has an adverse effect 
on the power of the model by reducing the sample size.    
A special case is *pairwise deletion* where we analyse all the cases
where data is present. This comes with the downside of having different 
sample sizes for the different variables.   

### Replace with average   
\
### Last known value
