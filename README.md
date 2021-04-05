# Newsify

<img src="https://user-images.githubusercontent.com/36112125/113533406-d6bb4a00-959b-11eb-8fcd-5e4201c350e0.gif" width="450"/>

:newspaper:	A web application that allows the user to enter the URL of a COVID-19 related news article and receive a summary of its contents. 
It keeps the reader informed and updated on current news. The web application also offers a prediction analysis graph of COVID-19 cases for the next 20 days.

The front end was connected to a **Python** backend via the [**axios**](https://www.npmjs.com/package/axios) package which allows for sending **HTTP requests** to **REST API endpoints**. 
The url is passed to the backend as a string and then passed through the [**MeaningCloud natural language processing API**](https://www.meaningcloud.com/developer/apis).

### Tools/Technologies: ###  
* [Vue.js]()
* [MeaningCloud natural language processing API](https://www.meaningcloud.com/developer/apis)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [axios](https://www.npmjs.com/package/axios)
