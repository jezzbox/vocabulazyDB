# vocabulazyDB
documentation for the mongoDB vocabulazyDB which will be used for my app Vocabulazy

## Collections:	
collection | description
------------ | -------------
users | collection that will store most user information
cards | This will have documents of the users cards with a reference to the deck it belongs to (decks will be embedded in users)
vocabulary | the words and expressions available in the app to be used as cards
phrases | documents of all the phrases

## Naming conventions:
type |  convention
------------ | -------------
database | camelCase with 'DB' on the end
collection | single word, plural, lowercase
field name | camelCase



