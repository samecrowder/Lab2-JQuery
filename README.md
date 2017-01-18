# Lab2-JQuery
First take the <a href="https://www.khanacademy.org/computing/computer-programming/html-css-js/html-css-js-intro/e/quiz--javascript-recap">Khan quiz</a> to make sure you know basic javascript. In this assignment you will implement a jquery ajax call to get the current weather. 

![Example of Weather Page](Screen%20Shot%202015-02-20%20at%202.05.21%20PM.png)

The weather section should do the following:

1) Allow the user to type characters into a form. With each keystroke, query a <a href="http://bioresearch.byu.edu/cs260/jquery/getcity.cgi?q=Pr">REST service</a> that will return a list of cities in utah that have those characters as a prefix. This will provide a hint to the user as to what legal values can be. Put these options into a list. These [hints](https://github.com/BYUCS260/Lab2-JQuery/wiki/Getting-Suggestions-to-Work) may be helpful.

2) When the user selects the submit button, take the entry from the form and put it into the CITY box on the page. These [hints](https://github.com/BYUCS260/Lab2-JQuery/wiki/Getting-Submit-to-Work) may be helpful.

3) The submit button will also query the <a href="http://www.wunderground.com/weather/api/d/docs">weatherunderground REST service</a> to get the current weather for that city. These [hints](https://github.com/BYUCS260/Lab2-JQuery/wiki/Connecting-to-WeatherUnderground) may be helpful.

4) There is another input where a user can type a word, with a button that will query the [StackExchange REST service](https://api.stackexchange.com/docs/search) for questions with the word in the topic.  For example, if the user had entered "javascript" in the form, then you would create the following REST request

https://api.stackexchange.com/2.2/search?order=desc&sort=activity&intitle=javascript&site=stackoverflow

Or in other words:

- [ ] You have the basic layout of the weather form (the input box, output, etc.)
- [ ] As you type characters in the city input, the application suggests legal values
- [ ] When the submit button is pressed, you correctly fill in the City box
- [ ] You make the request to the weatherunderground site and fill in the weather div
- [ ] Users can query the stackExchange service for questions that have a particular word in the topic

**Submit to learningsuite the URL to your live webpage, along with any comments you have that will make your assignment easier to grade. Your URL must have the form: xxx.xxx/lab2/weather.html, otherwise you might not get full credit on the lab. You should have utilized the github classroom link to get started with the assignment.**

#### Grading:


- You will be graded based on the following (there's some room for partial credit, don't worry):


Behavior | Approximate Points
--- | ---
You have the basic layout and parts of the weather application | 30
A User is suggested the full list of Utah cities with an inputed prefix | 15
A User can search for an inputed city's weather | 30
A User can search Stack Exchange for an inputed word | 15
Your page looks really good. This is subjective, so wow us. | 10

