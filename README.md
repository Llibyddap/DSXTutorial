# DSXTutorial

## NYS Restaurant Data Set

Includes:  NYRestaurantsNotebook_Full & DSXTutorial

IBM Watson - NYS Violations (updated to py3.5 with data asset connection)

The code for NYRestaurantsNotebook_Full pulls from a static repository (open source).  The second workbook, DSXTutorial, pulls
from a static CSV file loaded into the DSX environment.  Because the data is housed in a VM, the code creates a connection within
the VM.  The coding is fairly straight forward usign the link wizard on the dataset.

There is also changes from the original tutorial due to the fact that I couldn't get spark to run within the DSX environment.  There
were some notes in StackOverflow noting similar issues within DSX.  So, I imported pyspark and recoded the example to generate new
connections and SQL instances under pyspark.

Overall - everything worked - code could definately be cleaned up.

Original Tutorial can be found here:

https://developer.ibm.com/clouddataservices/wp-content/uploads/sites/85/2016/11/DSXTutorial.pdf

## NYC Taxi Data Set

Includes: NYC_Taxi_KMeans

IBM Watson - NYC Taxi (converted to py3.5 from Scala with updated data set from NYC)

The original expample/tutorial was written in Scala - I've rewriten into python 3.5.

Ongoing project
