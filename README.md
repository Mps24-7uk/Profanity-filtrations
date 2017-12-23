# Profanity-filtrations:

The project is to Remove the profanity words used in the sentences.

# Dependencies:

1.  urlopen
2.  BeautifulSoup

# Step By Step explanation:

1.  Import the urlopen and BeautifulSoup from the urllib.request and bs4
2.  Use urlopen to open the site http://www.purgomalum.com/service/xml?text= this is shit test input
3.  Use beautifulsoap to extract the the sentence from the purgomalum page.

PurgoMalum is a simple, free, RESTful web service for filtering and removing content of profanity, obscenity and other unwanted text. PurgoMalum's interface accepts several parameters for customization and can return results in plain text, XML and JSON.

PurgoMalum is designed to remove words from input text, based on an internal profanity list (you may optionally add your own words to the profanity list through a request parameter (see Request Parameters below). It is designed to recognize character alternates often used in place of standard alphabetic characters, e.g. "@" will be recognized as an "a", "$" will be recognized as an "s", and so forth.
