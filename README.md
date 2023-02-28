While in the process of applying for jobs as a web developer I wondered how many people were actually clicking the links on my c.v to the various projects I have made.  
Some people say that a portfolio is of utmost importance, while others say that recruiters are unlikely to take anything but a cursory look at a candidate's code given the volume of applications they must read through. 
To answer my question, instead of using Adobe Acrobat to insert a javascript into the pdf file of my c.v I set up this simple API using Node, Express, Mongoose and MongoDB Atlas. Now, all of the links in my c.v lead to the different api routes which serve to log a click for each link. The date and time of the click is also recorded so that a front end can eventually display the statistics for ease of viewing.
When an API route is visited the database is updated, but instead of returning a response and notifying the user in the browser, they are immediately redirected to the appropriate link as normal.