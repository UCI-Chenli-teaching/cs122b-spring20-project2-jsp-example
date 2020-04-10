## CS 122B Project 2 JSP example

This example shows how JSP works independently.

### To run this example: 
1. clone this repository using `git clone https://github.com/UCI-Chenli-teaching/cs122b-spring20-project2-jsp-example.git`
2. open Intellij -> Import Project -> Import Project `(choose the project you just clone)`-> Choose `Maven` -> -> Click on `Finish`.
3. Open `src/main/webapp/index.jsp`. Change the mysql username and password and make sure you have the `moviedb` database.
4. Make sure you have configured Tomcat, and you have specific database with you
5. You can run this project on Tomcat now.

### Brief Explanation
`index.jsp` dynamically generates the html page with Java API. It is requested as a static resource, rather than a servlet sample we have seen before.
The .jsp file is requested directly.
