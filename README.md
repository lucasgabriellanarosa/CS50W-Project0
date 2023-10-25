# CS50W-Project0

This is my first CS50's Web project. It is a front-end design for Google. Here I made my first step to understand how the front-end works and looking back now I can understand what is happening behind the scenes. And now I can see what is for example the form tag.
The main goal of the project is show how you send information from the front-end (in this case, thanks to the form and input tags) to a server (Google) and return a response. Here the data we send to the server is the query we write in the input and the response is the page we get searching for that data.

## index.html

Here we have the main page of the app. Inside this file there's a form tag with the action with the URL of our server (Google). Then we have three important input tags. 
* The first one is the query you'll search for. It has the name="q", which makes our server look at its value as the query.
* The second one and the third are very similar, the difference is the name. The second sends a request with the name btnK, which is a normal Google search, while the last one sends a request with the name equals to btnI, which will redirect you to the first page you would see if you searched by the normal Google search. You already know it, I don't have to explain how the Google works.
* 
