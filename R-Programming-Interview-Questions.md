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

