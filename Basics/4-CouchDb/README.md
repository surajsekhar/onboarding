## Introduction to CouchDB
* [CouchDB - What and why?](http://www.infoq.com/articles/apache-couchdb-the-definitive-introduction)
	 * Read till 'Technical details'. Rest of the concepts will be covered in the upcoming sections.
* [Install CouchDB](http://couchdb.apache.org/) and [Try this example.](http://guide.couchdb.org/draft/tour.html#go)
* Why does CouchDB make sense for Artoo?

## Basics
* CouchDB is a 'schema-less' database. [Why?](http://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/)
* [Key/ Value concept](http://guide.couchdb.org/draft/why.html#containment)
* [Core API](http://guide.couchdb.org/draft/api.html#api)

## Documents
* [Docs, local docs, and _design/docs.](http://guide.couchdb.org/draft/design.html#design)
* [Revisions and Conflicts](http://guide.couchdb.org/draft/conflicts.html#conflicts)

## Views
* [Views](http://couchdb.readthedocs.org/en/1.6.1/api/ddoc/views.html#view-options)
* [What is Map Reduce?](http://www.slideshare.net/okurow/couchdb-mapreduce-13321353)
* [An interesting example](http://stevekrenzel.com/finding-friends-with-mapreduce)
* Reduce and rereduce
* Built in functions: _sum, _stats, _count
* [Let's refresh](http://www.relaxed.tv/#video/0e0aad9d3ff48ed9d29fe32b7918468a)

#### Task
* On the dataset(url to be added) provided, create views (using map-reduce) to-
    * Display the sum of the loan amount in each branch based on their branch_context.
    * Display the sum of the loan amount in each branch for each disbursement_date.
    * Display the sum of the loan amount in each branch per loan-type.
    * Combine 2 and 3.
    
## Extra
* [What are Show / List / Update APIs?](http://docs.couchdb.org/en/latest/couchapp/ddocs.html#show-functions)

#### Task
[Build the table similar to this site : http://www.bbc.com/sport/football/premier-league/table]
* Using `curl`, create 2 databases, add 5 different documents in each. Create a third which contains 10 combined. Build a view to display the different sets of docs
* Using `curl`, create a database for 10 cricket teams/football teams/racers over 20 games with their details. Now using views:
	* Build a championship table for the team
	* Build a championship table for players
	* Build a historical view a player
	* If you had to purchase a player, which one will it be? Using a view justify your response.
* Demonstrate Show, List and Update APIs on your dataset above



## Changes
* [How does changes work?] (http://guide.couchdb.org/draft/notifications.html)
* [Watch the video and also play around with the concepts] (http://www.oreilly.com/pub/e/1708)
* Create a DB and a few docs. Demonstrate the effect of the following query params:
	* since
	* feed
	* filter

## Replication
* [What's the point of replication?] (http://guide.couchdb.org/draft/replication.html)
* [How does one do filtered replication?] (https://wiki.apache.org/couchdb/Replication#Filtered_Replication)
* [What is touch db and how we use it] (https://github.com/couchbaselabs/TouchDB-iOS/wiki/Replication-Algorithm)
