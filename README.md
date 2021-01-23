# WorkCount
Word count Using Scala and Spark

A demo project ( Hello World of Big Data ) to learn about Spark and Scala 
using Sbt package for running compiling and packaging and Scala.

- The wordcounter.scala takes the input file sample or sample.txt which contains lines of code 
- It maps each line of the file 
- splitting each line into an array of space delimited words 
- we then flattening the resultant sequence of string arrays into a single long sequence 
- we then set up our sequence for counting by changing each a word into key value pair ,where the word is the key and value is the count 
seeding with count of 1 for each counted word string .

- the data prepared into this key valued format we can now reduce the value down to single count for each key ,
adding up all the ones in each word bucket and sorting out list of word count pairs on the count in descending order. 
