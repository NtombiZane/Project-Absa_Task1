#Task 1- API
The task was to use API requests to get information from the Public API - https://dog.ceo/dog-api/.
The script was done in Colab.
The Request function was imported so that I can send API requests.
Because the script was done in Colab, I mounted my google drive to the program to make sure the results generated by the script will be saved on that particular path.
Google drive acts as disk space for my google colab scrips and jobs ran.
After the drive was successfully mounted, I checked if it was mounted correctly and the datasheet was saving in the right place.
I import pandas to make sure I will be able to save the data using methods like CSV/Excel.
I use the get function for all the requests because I just want to search on the website for the information we need.
What the code does is to send a request to the Public API to get a list of all the dog breeds.
From the list of all the dog breeds, we use a for loop to verify that the breed "Retriever" is part of the list
I send another request to get a list of all the sub-breeds of "Retriever". 
The last request is to get a random image of the sub-breed golden.

