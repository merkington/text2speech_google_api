# text2speech_google_api

This is just a short script to use the Google text2voice API.

It reads the setting from JSON, the same settings the form on the
google t2s pags provides. It reads your google api key from another json
and then it reads from panda df comlumns title and content. 

It uses title as the saved filename, and content as the text to 
change to audio. It then repeats for every entry in the df.

