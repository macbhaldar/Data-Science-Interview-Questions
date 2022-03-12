## R Programming Interview Questions

### What is R?
R is a programming language which is used for developing statistical software and data analysis. It is being increasingly deployed for machine learning applications as well.

### What are advantages of R?
- Its **open-source nature**. This qualifies as both an advantage and disadvantage for various reasons, but being open source means it’s widely accessible, free to use, and extensible.
- Its **package ecosystem**. The built-in functionality available via R packages means you don’t have to spend a ton of time reinventing the wheel as a data scientist.
- Its **graphical and statistical aptitude**. By many people’s accounts, R’s graphing capabilities are unmatched.

### What are the disadvantages of R?
- **Memory and performance**. In comparison to Python, R is often said to be the lesser language in terms of memory and performance. This is disputable, and many think it’s no longer relevant as 64-bit systems dominate the marketplace.
- **Open source**. Being open source has its disadvantages as well as its advantages. For one, there’s no governing body managing R, so there’s no single source for support or quality control. This also means that sometimes the packages developed for R are not the highest quality.
- **Security**. R was not built with security in mind, so it must rely on external resources to mind these gaps.

### Explain how you can start the R commander GUI.
rcmdr command is used to start the R commander GUI.

### What is the memory limit of R?
In 32 bit system memory limit is 3Gb but most versions limited to 2Gb and in 64 bit system memory limit is 8Tb.

### What are R packages?
Packages are the collections of data, R functions and compiled code in a well-defined format and these packages are stored in library. One of the strengths of R is the user-written function in R language.

### What is the use of With () and By () function in R?
with() function applies an expression to a dataset.
```
#with(data,expression)
```
By() function applies a function t each level of a factors.
```
#by(data,factorlist,function)
```

### What is the use of subset() and sample() function in R?
Subset() is used to select the variables and observations and sample() function is used to  generate  a random sample of the size n from a dataset.

### What is difference between lapply and sapply?
lapply is used to show the output in the form of list whereas sapply is used to show the output in the form of vector or data frame.

### What is the difference between seq(4) and seq_along(4)?
Seq(4) means vector from 1 to 4 (c(1,2,3,4)) whereas seq_along(4) means a vector of the  length(4) or 1(c(1)).

### Explain how data is aggregated in R.
There are two methods that is collapsing data by using one or more BY variable and other is aggregate() function in which BY variable should be in list.

### How many sorting algorithms are available?
There are 5 types of sorting algorithms are used which are:
1. Bubble Sort
2. Selection Sort
3. Merge Sort
4. Quick Sort
5. Bucket Sort

### Which method is used for exporting the data in R?
There are many ways to export the data into another formats like SPSS, SAS , Stata , Excel Spreadsheet.

### Which packages are used for exporting of data?
For excel xlsReadWrite package is used and for sas,spss ,stata foreign package is implemented.

### What is the use of coin package in R?
Coin package is used to achieve the re randomization or permutation based statistical tests.

### What happens when the application object does not handle an event?
The event will be dispatched to your delegate for processing.

### Explain app specific objects which store the app contents.
The app specific objects are Data model objects that store app’s contents.

### What is npmc?
It is a package which gives nonparametric multiple comparisons.

### Why library() function is used?
This function is used to show the packages which are installed.

### Why search() function is used?
By this function we see that which packages are currently loaded.

### How to create new variable in R programming?
For creating new variable assignment operator `‘<-’` is used
For e.g. 
```
mydata$sum <- mydata$x1 + mydata$x2
```

### What is the function which is used for merging of data frames horizontally in R?
Merge()function is used to merge two data frames
```
Sum<-merge(data frame1,data frame 2,by=’ID’)
```

### what is the function which is used for merging of data frames vertically in R?
rbind() function is used to merge two data frames vertically.
```
Sum <- rbind(data frame1,data frame 2)
```
### Which command is used for storing R object into a file?
Save command is used for storing R objects into a file.
```
Syntax: >save(z,file=”z.Rdata”)
```

### Which command is used for restoring R object from a file?
load command is used for storing R objects from a file.
```
Syntax: >load(”z.Rdata”)
```

### How do you read a CSV file in R?
We’ve covered this already with the import process. Simply use the read.csv() function.
```
Data <- read.csv("Data.csv", header = TRUE)
```

### Which function is used for sorting in R?
order() function is used to perform the sorting.

### What is the use of abline() function?
abline() function is add the reference line to a graph.
```
Syntax: abline(h=yvalues, v=xvalues)
```

### What is the use of with() in R?
We use the with() function to write simpler code by applying an expression to a data set. 
```
with(randomDataSet, expression.test(sample))
```

### What is the use of by() in R?
We can use by() to apply a function to a data frame split by factors.
```
by(data, factor, function, ...)
```

