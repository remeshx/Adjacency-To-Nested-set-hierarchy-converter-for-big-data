# Adjacency To Nested set hierarchy converter for big data step by step in PHP (ATN)

This Class is written in PHP for converting/updating/fixing hierarchy data from Adjacency Model to Nested set Model in a <b>large data set</b>.

If you do not know anything about hierarchy models I advice you to visit following link : 
http://mikehillyer.com/articles/managing-hierarchical-data-in-mysql/

ATN is optimised for large data. it uses memory tables and fix your table garadually and step by step. If your data is not large, there are other much simpler ways to convert from Adjacency list Model to Nested set. most of these codes out there are desined to do the same thing but in one shut. This is normally does the work for smaller data sets. However , as updating large data sets can take more time, you may get timout errors, or experience downtime during conversion.

This class has created to convert/update/fix Nested set data in step by step and smooth proccess that does not affect running database during conversion. You can safely run ATN on your live data with out any downtime. We are updating our data regularly using ATN.php for more than 5 millions of records on a live busy tables.



