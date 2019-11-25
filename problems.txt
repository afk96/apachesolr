
I am trying to setup Apache solr in a project and have been partially succesfull with it , the only problem I am getting is :

-The proximity search on solr is not working as expected . I have a single core in this copy of solr . 
In the schema.xml file you'll find my fields within which i have a field named "pSearchField" which is 
only supposed to work with proximity it has no synonym filter or stemmer in it . But still I am unable 
to get it working right although in the analysis tab the stopword filter factory is stopping the words 
as its suppose to but in query time the proximity search is not stopping the stopwords .

This is a link to a question I posted on stackoverflow which has details in it also if you want to check it : 
https://stackoverflow.com/questions/58995281/solr-stop-words-not-seem-to-work-stop-words-are-removed-while-indexing-but-sti
