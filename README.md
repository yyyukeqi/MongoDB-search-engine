# MongoDB-search-engine

Provided automation solution for internal operation team. 

Replacing manuel search on typeing keywords on Excel or SQL to search a large scale of database, I created a search engine to provide more efficient solution to achieve search as you type (autocomplete) and search any matching (wildcard) functionality. 

The [autocomplete](https://www.mongodb.com/docs/atlas/atlas-search/autocomplete/) operator performs a search for a word or phrase that contains a sequence of characters from an incomplete input string. You can use the autocomplete operator with search-as-you-type applications to predict words with increasing accuracy as characters are entered in your application's search field. autocomplete returns results that contain predicted words based on the tokenization strategy specified in the index definition for autocompletion. The fields that you intend to query with the autocomplete operator must be indexed with the How to Index Fields for Autocompletion data type in the collection's index definition.


The [wildcard](https://www.mongodb.com/docs/atlas/atlas-search/wildcard/) operator enables queries which use special characters in the search string that can match any character.
