

# Installing ggplot2
``` r
install.packages("ggplot2")

library(ggplot2)
```
<br>
<br>

# The Basic Syntax 
<br>

![700](/Appendix/Images/basic%20synthax%20of%20ggplot.jpeg)
<figcaption> 
Figure 1: The basic syntax of the essential components of the ggplot. Note that the data set and aes is in brackets. These 2 componets are grouped together as additional layers are added
</figcaption>

<br>

The main components of ggplots are:
- data: 
- aes ( ): describes how the variables in the data are mapped to the visual aesthetics of geoms. 'aes ( )' is a **quoting function**
- geom_ : geometic objects to increase readability of the plot


<br>
<br>

# Layering in Plots: Stylization
<br>

## **Geom objects** 
![700](/Appendix/Images/Common%20geom%20objects.jpeg)
<figcaption>
Figure: Comon geom objects 
</figcaption>

<br> 



## **Theme ( ) function**
Purpose: Controls the display of non data elements of the plot

<br>


![700](/Appendix/Images/the%20theme%20function%20in%20ggplot.jpeg)
<figcaption>
Figure: An example of the basic syntax of the theme function in ggplot2. The syntax contains the theme function, a theme argument, the element function and the stylizing code.
</figcaption>

<br> 

The theme ( ) function have numerous arguements and will not be display here. But for reference please look at [Theme: Modify components of a theme](https://www.rdocumentation.org/packages/ggplot2/versions/3.4.1/topics/theme)

A part of the theme ( ) function is the element module. 
 <br>


## **Element Module**
The most common element module includes:
- element_line ( )
- element_rect ( )
- element_text ( )
- element_blank ( )
- element_point ( )
- element_bar ( )
