solr-wikipedia-conf
===================

Configuration files for Solr wikipedia. Part of the tweet categorization project. 
Add these to (solr-dir)/example/solr/collection1/conf. 
Add enwiki-latest-pages-articles.xml from the Wikipedia download page to (solr-dir)/example

Run java -jar start.jar in (solr-dir)/example, go to localhost:8983/solr, and start the import!

Note: this import requires a few hours and gigabytes of disk space and memory. Start with a small part of wikipedia!
