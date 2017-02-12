---
sitemap: false
excerpt: "Nicole Weatherburne Projects"
permalink: /projects.html
date: 2017-02-13
---

<h1>Major Work Projects</h1>
<div class="alert alert-info" role="alert">
SPAGS Information System (Environmental Research Institute)
</div>

<figure class="half">
	<a href="images/SPAGS_1.jpg"><img src="images/SPAGS_1.jpg"></a>
	<a href="images/SPAGS_2.jpg"><img src="images/SPAGS_2.jpg"></a>
	<figcaption>The SPAGS online information system was designed for the purpose of improving monitoring and conservation efforts of the Nassau Grouper specie in Belize.</figcaption>
</figure>

### Major Features:

- Uploading data from custom excel templates provided to users
- Displaying dynamic graphs of analysis results using HighCharts interactive graphing tool
- Displaying dynamic summary analysis results (Google Maps, PHP, XML, MySQL, AJAX)
- AJAX and JQuery for enhanced user experience
- Use of licensed software PHP Report Maker to generate reports
- Generating SQL queries for analysis, manipulation and accessing data
- Implementing SQL injection techniques
- Defining user access levels
- Developing a user guide and organizing training sessions



<div class="alert alert-info" role="alert">
Coral Bleaching Information System (Environmental Research Institute)
</div>
<figure class="half">
<a href="images/CORAL_2.png"><img src="images/CORAL_2.png"></a>
	<a href="images/Coral_1.png"><img src="images/Coral_1.png"></a>
	<figcaption>The National Coral Bleaching Monitoring Network (NCRMN) Information System provides coral bleaching statistical reports based on defined time periods and locations along the coast of Belize</figcaption>
</figure>


This application was an existing PHP application built using the Codeigniter framework. I had to understand and modify existing code to enhance this application which involved:

- Designing an improved user friendly data entry interface where users upload data from custom excel templates. The previous data entry interface was very slow and required download of a `jar` file everytime there were updates.
- Generating reports as PDF files
- Development of an interactive map displaying coral bleaching summary results (Google Maps, PHP, XML, MySQL, AJAX)
- Developing a user guide and organizing training sessions

<p><br><p>

<h1>Major Course Projects</h1>
<div class="panel panel-primary">
      <ul class="list-group">


      <li class="list-group-item">
      <span class="underline"><b>Data Mining (2016)</b></span>
      <br><b><a href = "https://github.com/Hopenglish-Miners">Hopenglish Miners</a></b> 
      <br>The dataset was provided by an e-learning company based in Taiwan. Their online e-learning platform provides different alternatives to efficiently learn the English language through the use of multimedia content, such as video clips and audio recordings. The dataset consisted of video details and student behaviours which show how students interacted with videos. We were asked to discover some interesting insights that we can provide to the company to better understand their clients and improve their service. After gaining extensive insights into the data, we found a pattern in the student behaviour which could eventually lead to students quitting the service. We performed a classification using a decision tree to perform a prediction in an effort to identify when students lose interest. Our argument is that if we can identify when students lose interest, the company can recommend better videos that could keep the users engaged and reduce student dropout. We developed a web application to demonstrate the real world application of our proposal.

      <br><br><b><i>Gained experience in several data mining processes which included:</i></b>

      <br>- Data Exploration/Visualization (Pandas, Jupyter, K-means clustering algorithm, Plotly)
      <br>- Data pre-processing (Feature selection/creation to address curse of dimensionality problems - clustering algorithms)
      <br>- Data mining algorithm (Supervised algorithm to perform classification: C4.5 Decision Tree - 70% training/30% testing)
      <br>- Data mining evaluation (10 Fold Cross Validation with 64% accuracy)

      <br><br><i>Prepared by Hopenglish Miners
      <br>National Tsing Hua University (Hsinchu, Taiwan) </i>
      </li>


      <li class="list-group-item">
      <span class="underline"><b>Service Security (2016)</b> </span>
      <br><b><a href = "https://github.com/wisebits">Wisebits URL Shortner</a></b> 
      <br>Developed a secured service that allows authorized users to generate and share shortened URLs. Registered users can create a shortened URL that is secure and shareable among users with appropriate permissions. The service was built in Ruby (Sinatra) using Slim and Bootstrap for the client application. We used heroku and postgres to host our services and databases. We made use of Rbnacl cryptographic libraries for implementing security features: <a href = "https://github.com/cryptosphere/rbnacl">https://github.com/cryptosphere/rbnacl</a>
      <br><br><b><i>Gained experience in developing a secured distributed architecture which included:</i></b>

      <br>- Securing databases through SQL injection, mass assignment restrictions, ORM based encryption
      <br>- User Authentication
      <br>- Password hashing (Salt + Hash + Key stretching)
      <br>- Token based Authentication (secured session and cookies, safe user registration and authorization)
      <br>- Token based Authorization (Signed client apps (JWK), secure API requests)
      <br>- OAuth Authorization Protocol
      <br>- Preventing XSS/CSRF attacks, protecting HTTP headers
      <br>- API and interface testing
      <br>- Defining access control
      <br>- Enforce SSL/TLS

      <br><br><i>Developed by Wisebits Team
      <br>National Tsing Hua University (Hsinchu, Taiwan) </i>

      <figure>
      <a href="images/ss.png"><img src="images/ss.png"></a>
      <figcaption>URL Shortner Service Architecture</figcaption>
      </figure>
      </li>


      


      <li class="list-group-item">
      <span class="underline"><b>Service Oriented Architecture (2015)</b> </span>
      <br><b><a href = "https://github.com/ZhongMeiZhou">TraViz</a></b> 
      <br>We developed TraViz Web Application and Data API service. TraViz allows users to generate visualizations of lonely planet tour listings based on specified countries, categories and price range. The service was built in Ruby (Sinatra) using Slim and Bootstrap for the client application.

      <br><br><b><i>Gained experience in developing a service following a modern service oriented architecture design:</i></b>

      <br>- Followed Agile development model
      <br>- Ruby gem created for lonely planet web scraping (OGA)
      <br>- Continuos integration (Travis CI)
      <br>- Continuos deployment (Heroku, Codeship)
      <br>- Distributed Postgres database
      <br>- Heavy emphasis on testing (Minitest, Stubs)
      <br>- Interface design and testing (mobile first interface)
      <br>- Data visualization (HighCharts, Chartkick)
      <br>- Reactive user experience using background jobs, queues, web sockets, web caching
      <br>- Refactored MVC with OOP (service, value, form objects)

      <br><br><i>Developed by ZhongMeiZhou 中美洲 Team
      <br>National Tsing Hua University (Hsinchu, Taiwan) </i>

      <figure>
      <a href="images/soa.png"><img src="images/soa.png"></a>
      <figcaption>Sample architecture design</figcaption>
      </figure>

      </li>

      <li class="list-group-item">
      <span class="underline"><b>Advanced Database (2015)</b> </span>
      <br><b><a href = "https://github.com/rjollet/NeverAloneNTHU">Never Alone Dating Service</a></b> 
      <br>We developed a dating service that recommends potential matches to users. We used Django Framework and Neo4J Graph Database. We wrote recommendation algorithms and made use of concepts such as Jaccard Similarity in order to recommend matches based on similar interests.

      <br><br><i>Developed by Never Alone Team
      <br>National Tsing Hua University (Hsinchu, Taiwan) </i>
      </li>

      </ul>
</div>


<p><br><p>

<h1>Passtime/Freelance Projects</h1>
<div class="panel panel-primary">
      <ul class="list-group">
      
      <li class="list-group-item">
   
      <br><b><a href = "https://nikki-resource-stop.herokuapp.com/">Nikki's Resource Stop (2015) </a></b> 
      <br> Developed an application to manage popular online IT resources I have found useful. I used a popular Javascript framework called the MEAN stack (Mongo, Express, Angular, NodeJS). I used additional modules including Mongoose and Passport for google authentication and database modeling.
      </li>

      <li class="list-group-item">
      <br><b><a href = "http://c-armsinc.com/">C-ARMS Inc. (2014)</a></b> 
      <br> Developed a static information based website using Joomla CMS.
      </li>

      </ul>
</div>