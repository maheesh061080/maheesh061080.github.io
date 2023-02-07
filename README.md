<html>
   <head>
      <style>
         /* CSS styles for the resume */
         h1 {
         font-size: 36px;
         font-weight: bold;
         text-align: center;
         margin-bottom: 20px;
         }
         .section-header {
         font-size: 24px;
         font-weight: bold;
         margin-top: 50px;
         margin-bottom: 20px;
         }
         .section {
         margin-bottom: 50px;
         }
         .section p {
         font-size: 18px;
         margin-bottom: 20px;
         }
         .section ul {
         list-style-type: none;
         padding: 0;
         }
         .section li {
         font-size: 18px;
         margin-bottom: 10px;
         }
         .section li::before {
         content: "•";
         margin-right: 10px;
         font-size: 20px;
         }
         .box {
         border: 1px solid black;
         width: 150px;
         height: 150px;
         display: inline-block;
         margin: 10px;
         vertical-align: top;
         text-align: center;
         }
         img {
         display: block;
  		 float: left;
  		 margin-right: 10px;
         top: 30%
         }
         .text {
    	 position: absolute;
    	 left: 20%;
    	 top: 23%;
    	 transform: translate(-50%, -50%);
  	     }
         .text2 {
    	 position: absolute;
    	 left: 22%;
    	 top: 67%;
    	 transform: translate(-50%, -50%);
  	     }
         .highlighted-text {
  		 background-color: yellow;
  		 position: relative;
  		 padding: 0 10px;
		 }
		 .highlighted-text:before {
  		 content: "✔";
  		 position: absolute;
  		 left: 0;
  		 top: 0;
  		 bottom: 0;
  		 margin: auto;
  		 height: 15px;
  		 width: 15px;
  		 color: green;
  		 font-size: 20px;
		 }
         .tick {
         position: relative;
  		 padding: 2 2px;
         }
         .tick:before {
  		 content: "✔";
  		 position: absolute;
  		 left: 0;
  		 top: 0;
  		 bottom: 0;
  		 margin: auto;
  		 height: 15px;
  		 width: 15px;
  		 color: blue;
  		 font-size: 20px;
		 }
      </style>
   </head>
   <body>
   
      <!-- Header with name and contact information -->
      <header>
         <h1><div class="highlighted-text" class="highlighted-text:before">Mahesh Pisari</div></h1>
         <p><b><div class="highlighted-text" class="highlighted-text:before">City</div></b> - Bangalore</p>
         <p><b><div class="tick" class="tick:before">Phone:</b> +91 96111 44761</p>
         <p><b>Email:</b> pisari.mahesh@email.com</p>
      </header>
      <!-- Summary section -->
      <section class="section">
         <h2 class="section-header"><div class="text"><u>Expertise</u></h2>
         <p>
         <ul>
            <li>
               16 years of robust industry experience in building products.
               </div>
            </li>
            <li>
               Solutioning to marketers for a full stack marketing automation suite.
            </li>
            <li>
               Building virtual environments and container orchestration using docker and utilities. On demand Spawning containers with docker, docker swarm, slat stack.
            </li>
            <li>
               Build CI/CD environments with selenium grid, Jenkins, gitbucket and automated test suite.
            </li>
            <li>
               Technical coordination with QA and development teams and transforming thebusiness requirements into solution modules.
            </li>
            <li>
               Setup and mentor team(s) who can delivery world class products.
            </li>
            <li>
               Results-oriented product specialist and data analyst, architect solutions on big data and IoT and M2M products.
            </li>
            <li>
               Extensive experience in Linux, SDLC, resources optimisation / utilisation, automation, SRS, HLD / LLD, planning resource and cost.
            </li>
            <li>
               Working in Agile and Scrum methodologies and principals.
            </li>
            </div>
         </ul>
         </p>
      </section>
      <!-- Summary section -->
      <section class="section">
         <h2 class="section-header"><div class="text2"><u>Achievements</u></h2>
         <p>
         <ul>
            <li>
               Innovative employee award in 2014 and nominated in 2012
            </li>
            <li>
               Start performer awards quarter on quarter (instance of 6 consecutive quarters)
            </li>
            <li>
               200+ mobile apps integrated with our SDK.
            </li>
            <li>
               Introduced and drive innovative projects at NetCORE including automated testing and Continuous Integration.
            </li>
         </div>
         </ul>
         </p>
      </section>
      <!-- Summary section -->
      <section class="section">
         <h2 class="section-header"><u>Professional Experience</u></h2>
         <p>
            <b>Current Company – Netcore Solutions Pvt Ltd</b>
         <ul>
            <li>
               Associate Vice President – BA (Apr 2019 to Till date)
            </li>
            <li>
               Group Manager– BA (Oct 2016 – March 2019)
            </li>
            <li>
               Group Manager – QA (Environments Specialist) (April 2014 – Sept 2016)
            </li>
            <li>
               Team Manager – QA (April 2010 – March 2014)
            </li>
            <li>
               Lead QA and Linux Admin (Netcore Solutions) (July 2007 – March 2010)
            </li>
            </ul>
            </p>
            <p>
            <ul>
            <li>
               Worked at <b>SEraja technologies pvt. Ltd</b> from Oct 2005 to June 2007 as Network engineer and content aggregator.
            </li>
         </ul>
         </p>
      <!-- Education section -->
      <section class="section">
         <h2 class="section-header">Education</h2>
         <ul>
            <li>
               <p>
                  <strong>Bachelor of Engineering with major in Electronics and Communication</strong>
                  <br />
                  1999 - 2003
               </p>
               <p>
                  Diploma in Embedded Systems - VLSI, Assembly Programming.
               </p>
            </li>
         </ul>
      </section>
      <!-- Skills section -->
      <section class="section">
      <h2 class="section-header">Skills</h2>
      <div class="skills-table">
      <div>
         <div class="box">Development</div>
         <div class="box">Testing</div>
         <div class="box">Project Management</div>
         <div class="box">CI/CD</div>
         <div class="box">ECA</div>
      </div>
      <!-- Projects section -->
      <section class="section">
      <h2 class="section-header">Projects</h2>
