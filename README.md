# flask_socketIO_namedpipe
# vue+flask+socketIO+win32_namedpipe

## only backend code in this repository  

This project is running on windows system.  

In this project, there are two python files.  

One python file process has two processes to get data from external resources, the other one is running a flask socketIO app as backend. I need to send some data which is upgrading 2 times a second to the flask app, and then the flask app sends the data to the frontend.  

I use win32api namedpipe to complete communication between two python files.  

In python3.8, I can use sharedmemory. I will update my code later.
