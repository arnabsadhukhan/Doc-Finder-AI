# Doc-Finder-AI
THIS IS A PROGRAM SCANS ALL OF YOURS DOCUMENTS LIKE PDF DOCX AND PPT FILE AND CREATE A MAPPING OF ITS CONTENT.
THIS MAPPING IS USED FOR FAST SEARCHING IN ALL OF YOUR DOCUMENTS.

the "reader.py" file stores all the method to read different files 

TO USE THE DOC-FINDER OPEN "DOC FINDER.ipynb"

TO USE THE DOC FINDER WITH INTERACTIVE GUI OPEN "DOC FINDER WITH GUI.ipynb" 


# DOCUMENT FINDER:
# Key points:
1.	Effective document scanning
2.	Searching using keywords and nearest synonyms
3.	Personalized search
4.	Suggestive searching
5.	Content based tagging

# Effective document Scanning:
After installing the software for the first time, it scans all the documents present in the folder and creates a processed database. This database is created based on a mapping of the document's title and the words present in that document. If a new document is added in the folder the database gets updated. It tracks the new document that is added and scans only that document to update the database. 
It doesn't search the document with all the words present in that document, instead, it searches the document with the help of the mapped database it has created. Therefore, the searching time is very less (a few milliseconds).

# Searching using keywords and nearest synonyms:
When a user enters the search query, the program searches the documents with that search query along with the nearest possible synonyms. The program prioritizes the search results based on the number of times the search query is present in a particular document and provides the user with a list of documents based on that priority order. Thus, the user finds a more appropriate file in lesser time.

# Personalized search:
The program will keep track of the user`s activity. It will observe the types of documents the user usually opens. The program will prioritize those types of documents and will show them at the beginning of the search list.
Suggestive searching:
When the user enters a search query, the suggestive search algorithm provides the user with some group of words as search suggestions which may contain the actual or nearest search query of the user.
Example: 
If the user gives a search query "signal", the suggestive search algorithm will provide some suggestions like: "signal processing", "signal and systems", "signal to noise ratio" etc.

# Content based tagging:

The program has an auto-tagging capability which means it classifies the documents based on their categories such as "Technology", "Sports", "Literature" etc.
The process of classifying the documents under different tags takes place during the initial scanning of the documents at the time of the first installation of the software.
It supports human-tagging also, which means the user can change the document tags manually.  
