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

### Replace with average (Imputation)  
One example is a general replacement where all missing values are 
replaced with an average value (Mean, median or mode).    
This hould tend not to distort the rest of the data but does not allow
for the true value at that point and may distort any modelled line.   
Similar case imputation happens when there are 2 (or more) similar 
sub-populations in the data and we use the average of the relevant 
sub-poulation to replace the missing point(s).    

\
### Last known value
