# Oracle AI APIs

How does a Data Scientist take advantage of Oracle AI capabilities ? 
1. REST API
2. Language SDKs (Python, Java, Go, etc..)

Before you can invoke the SDK, you have to obtain an **API Signing Key**. 

You can obtain an API Signing Key from your user profile in the OCI Console, then you save that key as a file to your local machine. The API Signing Key also provides commands to be added to a config file that the SDK expects to find in the environment, where the SDK code is executing. The config file then references the key file. Once these files are prepared on your local machine, you can upload them to the Notebook session, where you will execute SDK code for the AI service.

The API Signing Key and config file can be reused with any of your notebook sessions, and the same files also work for all of the AI services. So the files only need to be created once for each user and tenancy combination.