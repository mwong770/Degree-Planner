
# Degree Planner

A Node.js and MySQL degree planner that lets students organize courses by semester planned, registered, or completed

[Check Out Degree Planner](https://degree-planner1.herokuapp.com/)


## Table of Contents

[:computer:  Technologies Used](#technologies-used)

[:dvd:  Installation](#installation)

[:bar_chart:  MySQL Configuration](#mysql-configuration)

[:crystal_ball:  Usage](#usage)

[:boom:  Features](#features)

[:bust_in_silhouette:  Developer](#developer)

[:email:  Questions or Comments](#questions-or-comments)


## <a name="technologies-used"></a> :computer: Technologies Used 

* Node.js
* Heroku
* MySQL
* MySQL Workbench
* JavaScript
* Handlebars
* Bootstrap
* HTML5
* CSS3
* Node Modules
	* [mysql](https://www.npmjs.com/package/mysql) 
	* [express](https://www.npmjs.com/package/express)
	* [body-parser](https://www.npmjs.com/package/body-parser) 
	* [method-override](https://www.npmjs.com/package/method-override) 
	* [express-handlebars](https://www.npmjs.com/package/express-handlebars) 


## <a name="installation"></a> :dvd: Installation 

* Install [Node.js](https://nodejs.org/en/download/) and [MySQL](https://www.mysql.com/downloads/), if you don't have them.
* Optional: Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/), if you don't have it.
* Clone the Degree Planner repository to your local computer.
* On your terminal, navigate to the folder where the repository is located.
* Run the command `npm install` to download all required dependencies.


## <a name="mysql-configuration"></a> :bar_chart: MySQL Configuration 

* Find the following code in the connection.js file.

![screenshot of connection file](/screenshots/connection.png)

* Enter your MySQL password, if you have one.
To create the database and tables and then populate the tables, you can run the .sql files in the terminal by going to the Degree Planner folder and typing mysql -uroot -p < schema.sql and mysql -uroot -p < seeds.sql, or you can run schema.sql and seeds.sql in MySQL Workbench.

![screenshot of MySQL database creation](/screenshots/mysql.png)


## <a name="usage"></a> :crystal_ball: Usage 

* On your terminal, navigate to the folder where the repository is located.
* Run the command `node server.js` to begin using the app.


## <a name="features"></a> :boom: Features

* Users can enter course information -- course name, semester took/will take, year took/will take, whether planning on taking the course, currently registered for the course, or completed the course (optional - defaults to planned)
* Course information entered is displayed under Planned, Registered, or Completed categories
* Courses under each category are displayed in ascending order by semester/year 
* Users can delete courses
* Users can move courses from Planned to Registered by clicking the 'Registered' button
* Users can move courses from Registered to Completed by clicking the 'Completed' button


## <a name="developer"></a> :bust_in_silhouette: Developer

* Maria Wong 


## <a name="questions-or-comments"></a> :email: Questions or Comments 

If you have any questions or comments, feel free to message me on [LinkedIn](https://www.linkedin.com/in/maria-wong/).

Thanks for checking out Degree Planner!
