Indexers
========
These are some indexers which are compatible with [Lucene4IR](https://github.com/lucene4ir/lucene4ir/blob/master/README.md) . In addition , all of these classes are written to be run using IndexerApp from [Lucene4IR](https://github.com/lucene4ir/lucene4ir/blob/master/README.md)

CommonCore Document Indexer
-----------------------------------------------

Brief :
-------
Lucene indexer for CommonCore 2017 

Contents :
---------
a- Indexer 
<br/>
b- CommonCore Topics parser : parsing topics to a readable format to be used later by [RetrievalApp](https://github.com/lucene4ir/lucene4ir/blob/master/README.md)
<br/>
c- sample data and query files

Json Line Document Indexer
-----------------------------------------------
Brief
This is a Lucene indexer to index CAR - Cast and WAPO ( CommonCore 2018) collections. 
<br/>
This can be done with a [parser](https://github.com/stamatisvas/Index-TREC-CAR-MSMARCO-TREC-WASHINGTONPOST) that parses  files from all of these collections into one unified format 
	 
Contents :
 - Java class File (JsonLine Document Indexer) 	
 - Sample file that is resulted from the specified [parser](https://github.com/stamatisvas/Index-TREC-CAR-MSMARCO-TREC-WASHINGTONPOST)

![Accepted Json Format to the Indexer](https://github.com/ABDULAZIZALQATAN/Indexers/blob/master/Explanations/Json%20input%20Format.jpg)

General Classes
------------------------
These classes were made to achieve specific tasks :

| Class Name           | Description                                                            |
|----------------------|------------------------------------------------------------------------|
| CrossDirectory Class | Cross a folder and return a list of files inside it even inner folders |
