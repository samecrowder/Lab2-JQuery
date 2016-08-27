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

**Submit to learningsuite the URL to your live webpage, along with any comments you have that will make your assignment easier to grade. You should have utilized the github classroom link to get started with the assignment.**

#### Grading:


- You will be graded as follows (there's some room for partial credit, don't worry):


Passoff Level | Behavior | Points
--- | --- | ---
Minimal Passoff | You've got the basic layout of the weather app Your basic javascript functionality works (suggestions, filling in the city box, etc.) | 45%
Passoff | Your page is lacking one or two parts of the functionality (ex. the full cities list isn't working, or the API call isn't right, etc.) |	70%
Basic Passoff | You have all the required weather functionality | 80%
Good Passoff | You utilize the other required REST service | 90%
Perfect Passoff | Your page looks really good. This is subjective, so wow us. | 100%

