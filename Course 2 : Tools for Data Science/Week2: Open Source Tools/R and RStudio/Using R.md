# Getting started with R
### **Calling Libraries**
`library(library_name)`

<br>

### **Loading data**
`data(data_set)`

<br>

### **Previewing datasets** 
`View(data_set)`

<br> 

### **To install packages**
`install.packages("package name")`

<br>
<br>

# Exploratory Data Analysis

<br>

### **Visualizing all the different values in a variable**

`unique()`

>  The unique() function is used to identify and eliminate the duplicate counts present in the data. Thus it is able to show the **"unique"** values within a variable. 

```R
# Example 1: Exploratory Analysis: Examination of values in data column 

Class_data<-data.frame(Student=c('Naman','Megh','Mark','Naman','Megh','Mark'),Age=c(22,23,24,22,23,24),Gender=c('Male','Female','Male','Male','Female','Male'))

unique(Class_data$Student)


Output = "Naman" "Megh"  "Mark"
```
