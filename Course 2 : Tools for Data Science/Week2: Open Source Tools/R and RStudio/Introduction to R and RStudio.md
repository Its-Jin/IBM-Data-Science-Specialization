# Why use R 
**R is a statistical programming laguage for data processingm manipulation, statistical data analysis and machine learning**

R Capabilities:
- Easy to use
- Great visualization 
- Basic data analysis dont need additional packages

<br>
<br>

# What is RStudio
The **Integrated Development Environment(IDE)** to run R codes. 

![300](https://datascienceplus.com/wp-content/uploads/2019/02/r-studio.png)
<figcaption>Figure 2.2.2.1: R Studio user interface </figcaption>

<br>
<br>
<br>

# Popular R Libraries
<center>

| Library | Purpose |
|---------|---------|
|dplyr| data manipulation|
|stringr| string manipulation|
| ggplot | visualization |
| caret | machine learning|

</center>

<br>
<br>

# Visualizations with R 

<center>

| Library | Usage |
|---------|-------|
| ggplot | plot simple charts and graphs|
|plotly | web based visualizations and can be saved as HTML|
| lattice | for complex, multi-variable data sets|
|leaflet | for interactive plots |

</center>

<br>

# Getting Started with R
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

# Plotting in R with ggplot2
### **Calling for the ggplot2 library**

```R
library(ggplot)
ggplot(data_set)
```
<br>

### Basic functions 
+ `aes()` : construct aesthetic mappings

+ `+` : adding additional components/function 

+ `ggsave()` : to save a plot

+ `qplot() or quickplot()` : quick plot 

<br>

[**For complete list of functions in ggplot2**](https://ggplot2.tidyverse.org/reference/index.html)

Plots can have different layers of information. Most common are:
+ data
+ aesthetic
+ geometric object
+ stat 
+ position adjustment

In ggplot, these are called geoms so their function name is also 'geom' 

<br>
<br>

# Additional Resources 
- [Introduction to R - Biocorecrg](https://biocorecrg.github.io/CRG_RIntroduction/index.html)

