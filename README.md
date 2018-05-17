# Magento 2 Search AND Operator #
For some rather strange reasons, the devs at Magento have set the default search to combine search words with an OR parameter. 
Upon entering a search query, results are shown in alphabetical order. This is rather useless, because search results machting all
words would apear further down in the list, than a search result that only matches one word but is better ranked in an alphabetic search. 

Example: 

Search query: The cutest kitten book

Results would be: 

1. Allowing kids to read a book
2. Dental surgery using the cutest safety Masks
3. Many ways to book your holidays
4. The cutest kitten book 

With the AND operator, search results will be:

1. The cutest kitten book

## Setup ##
Install via composer "composer require arcmedia/mage2-search-and-operator"

flush all caches.

