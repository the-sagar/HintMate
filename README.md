# A system to provide hints for the words on web-pages according to the user’s knowledge and vocabulary. This system is not invasive, does not break user’s existing flow, and works automatically while giving users the ultimate control.

To install the server backend - 

Install the following libraries - 
python3
nltk
pandas
numpy

Download the wordnet sql db from - https://sourceforge.net/projects/wnsql/files/wnsql3/sqlite/3.1/sqlite-31.db.zip/download
Unzip and move it into src/main/resources

Open command line
Go into root folder(HintMateBackend) and run the following command - 
mvn spring-boot:run

For front-end - 
Install tampermonkey to run the user-script on the browser
