itEbooksDownloader
==================

Dump utility to download ebooks from http://it-ebooks.info/

==================

This utility allows you to easily download the ebooks published on the website http://it-ebooks.info/
Use the jar inside the dist folder to run the utility.

Example of usage (1) - download all possible ebooks to the specified folder:
java -jar ebookdownloader.jar -outputFolder=c:\itebooks\

Example of usage (2) - download selected ebooks, using a range id, to the specified folder:
java -jar ebookdownloader.jar -outputFolder=c:\itebooks\ -start=100 -end=150

==================

TODO
1. Improve filename generation: should not exclude chars like # or +. They can be useful in case of specific words like C++, C# etc.
2. Generate a txt file for each file containing the info regarding the ebooks.
3. Generate a summary txt that relates ebook id to the downloaded file.
4. Use Log4J for better logging.