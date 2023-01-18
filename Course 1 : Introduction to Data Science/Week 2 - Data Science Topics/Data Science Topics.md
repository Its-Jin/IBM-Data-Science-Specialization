# Big Data and Data Mining 
> Big Data refers to the dynamic, large and disparate volumes of data created by people, tools, and machines. It requires new, innovative and scalable technology to collect, host, and analytically process the vast amount of data gathered in order to derive real-time business insights to relate to consumersm risk, profit, performance, productivity management, and enhance shareholder value - Ernst and Young 

# Defining features of big data
- Velocity: speed of data accumulation 
- Volume: scale of data. Drivers of increasing data volumes can be:
    * new data sources
    * better sensors
    * scalable infrastructures 
- Variety: the diversity of the data. Diversity in the context of:
    * Structured vs unstructured data
    * Sources of data 
    * Drivers of data ie the devices that collects data
- Veracity: quality and origin of data which deals with the accuracy of the data
- Value : the impact and benefits from the data

Given these features, big data is difficult to analyze with conventional means. Thus alternative tools are used.

# Tools in Big Data analysis
- Apache Spark 
- Hadoop 
provides ways to extract, load, analyze and process the data across distrubted compute resources. 

### Hadoop 
 Before the Hadoop

The issue - Lots of data that is challenging to analyse

The solution by Larry Page and Sergey Brin - Chop the data into smaller chunks, replicate it multiple times, send it to different computers, replicate each piece and send those out too. Along with the data send out the programming that is needed. Each computer will run the program on the files and send back the result.This is the mapper process The results are sorted and processed. This is the reduce process.

The benefits: 
- allows for analysis of big data
- scalable to meet even bigger data as there is a linear relationship between analysis capabilities and # of servers 


As Hadoop povides a way to examine trends in big data 

# Digital Transformation 
Digital Transformation is data driven organizational and cultural changes causing changes in business operations, existing processess and technologies. Many organizations are using big data and digital transformations to change their very core. 

Digital Transformations are not simple in any aspect. It impacts the foundations of an organization and fundamentally change their operation. As such digital transformations require the support of many personnel and decision makers.



# Methods in Data Mining 
Data Mining is the process of search and analysing data and discovering previouslt unrevealed patterns.
### Defining Goals
As with data analysis, data mining needs:
- an established goal (ie questions that need answered)
- costs - benefit analysis
- expected data accuracy and usefulness
Cost and benefit trade off ties into data accuracy. Highly accurate data requires higher costs. At a certain level of accuracy, benefits are minimal due to the costs. 

### Selecting Data 
Data can be readily available or data collection efforts must be made,, which can drive up the costs. Regardless, identification of the right data within budget is crucial.

### Preprocessing Data 
Data is messy and those issues needs to be addressed before analysis. Data can: 
- contain errors: identifications and flagging is necessary 
- be missing data: systematic missing data lead to systemati biases and impact analysis must be done. As such, inclusion of the observation / variable must be considered 

### Transforming Data 
Relevant attributes can be numerous and while relevant, is not a representative indicator, as such transformations must be performed. Common techniques include:
- PCA - Principle component analysis
- Aggregation 
- Transformation to a different type of variable in accordance to analysis goals

### Storing Data
Transformed data must be stored to ensure:
- ease of access 
- usable formats
- safety and privacy 

### Mining Data 
The analysis aspect which can include parametric, non parametric and machine learning. Good starting point is data visualizations. Think back to stastics class, what was the first thing you do? look at boxplots, correlation graphs etc. 

### Evaluating Mining Results
Conduct formal evaluations which includes testing the predictive capabilities of moles and examing how effective the algorithm is at reproducing data aka in-sample forecast