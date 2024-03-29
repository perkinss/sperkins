---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
<!-- You can set your favicon here -->
<link rel="shortcut icon" type="image/x-icon" href="/favicon.ico" >
<!-- end custom head snippets -->
title: Susan Perkins || Resume
permalink: /
---
Enthusiastic and proficient senior developer with a keen interest in scalable software architecture and high-quality user experiences.
# Education
Bachelor of Software Engineering, <em>with Distinction</em><br/>
2001 - 2007 <br/>
University of Victoria
# Skills
* **Languages:** Ruby, Python, Typescript, JavaScript, PHP, Java, Groovy, SQL, CQL, Bash, C*
* **Frameworks, Platforms and Tools:** Kubernetes, Docker, Kafka,
  RabbitMQ, Flink, Flink Stateful Functions, Ruby on Rails, React, Vue, Groovy on Grails, Django, Flask, Laravel
* **AWS:** VPC, EC2, Lambda, Batch, ECR, ECS, S3, RDS, Route 53, API Gateway, IAM, Secrets Manager, Key Management Service (KMS), Step Functions, SNS
* **Google Cloud Platform:** GKE, IAM, Compute Engine, Cloud Storage, BigQuery
* **Processes:** Agile, SAFE, Scrum, Kanban

# Experience
----
### Senior Software Developer, Kudos
***March 2023 - Present***
###### [Kudos](https://kudos.com) is an employee recognition platform and people analytics software.
* Building Nodejs microservices on AWS

----
### Senior Software Developer, OfficeSpace Software
***January – November 2022***
###### [OfficeSpace Software](https://officespacesoftware.com) is a desk booking and facility management service.
* Developed React components and Rails functions for a new Shifts feature to allow clients to configure shifts on their bookable desks and rooms, providing deeper value to end users.
* Built a stateful function real-time processing application that laid the groundwork for a micro service architecture, wherein the state acts as a distributed single source of truth for multiple services without having to manage transaction rollbacks in the event of failures in downstream services.
1.	Captured Rails event data, such as desk bookings, and streamed them as protobuf messages to a Kafka event stream.
2.	Wrote stream processing functions using the Flink Stateful Functions TypeScript API that inserted transformed data into BigQuery (BQ)
3.	Queried data in BQ from Looker to create informative real time business analytics views and insights.
4.	Created React dashboard display for Looker widgets, providing clients with invaluable data visualizations and allowing them to make timely and cost-effective decisions regarding their resources
5.	Developed yaml scripts to build and deploy the infrastructure and code that ran our stateful functions on GKE.

----
### Senior Software Developer, Benevity
***September 2019 – November***
###### [Benevity](https://benevity.com) is an enterprise CSR platform, providing employees a way to volunteer and donate to the causes they care about, while being supported by their company and their peers.
* Developed a cloud-based batching system with AWS that produced an order of magnitude performance improvement for the ingestion of large amounts of user-data, such as employee payroll commitments.
* Created functionality in new notification and peer-matching systems, using a combination of VueJS, Javascript, PHP, Laravel, and Drupal. Peer matching helped client giving campaigns grow significantly by allowing employees to motivate each other through matching donations to causes they and their colleagues care about.

----
### Architect, Lead Developer, Markury.xyz
***Multiple contracts 2019-2022***
###### [Markury](https://markury.xyz) is a student assessment and reporting web application developed for BMJ Educational Services that makes standards-based assessment simple!
* Collaborated with a small group of teachers to bring their ideas to life, designing and building software that makes standards-based assessment and reporting simpler and more accurate for teachers.
* Worked from the ground up on UX design and followed iterative agile practices to ensure the right end result in Markury.
* Markury is a test-driven Rails and React web application running on Heroku and AWS S3, deployed using the Heroku CI pipeline.

----
### Senior Consultant, CGI Canada
***Jan 2018 – April 2019***
###### CGI, Victoria BC
* Built test-driven custom applications for government ministries using ReactJS and VueJS frontend frameworks, and python and NodeJs server-side APIs, deploying by continuous integration on Openshift.
* Replaced aging government legacy applications with modern web applications, and improved access to government services for the people of BC!
* Created a responsive “User Map” in ReactJS to guide users through the enormous number of legal documents they must fill, sign and serve in order to make or respond to an appeal through the BC Court of Appeal.

----
### Software Developer, Illumina Clarity LIMS
***Jan 2016 – Jan 2018***
###### [Illumina](https://illumina.com) builds instruments that help scientists unlock the power of the genome.
* Transformed an aging application built in JavaScript and deployed on an outdated version of JBoss, to a very snappy user-friendly interface using ReactJS running in a tomcat server and deployed via a Bamboo CI pipeline.  The changes made the core product development team substantially improved supportability, performance and maintainability of the Illumina Clarity Lab Information System (LIMS) and added a high degree of customer value.

----
### Architect, Lead Developer, Solvation.xyz
***Multiple contracts 2013 - 2022***
###### [Solvation](https://solvation.xyz) provides fully-worked solutions and video instruction for textbook problems.
* Lead the design and creation of this responsive, Ruby on Rails-based textbook-solutions web application.  Created automated processes to convert pdf and word documents into clean HTML and MathML, using bash, Python, ruby, Visual Basic and Automator scripts.  Added Oauth2 authentication via Edvantage Science moodle server, enabled video uploads and display, carried out software maintenance, upgrades and updates, and added a CI CD pipeline to the deployment process.

----
### Software Developer, Ocean Networks Canada / NEPTUNE
***Apr 2011 – Jan 2016***
* Incrementally improved the data acquisition, processing, management and distribution software for Ocean Networks Canada projects, to make data downloads faster and more efficient, and to make the UI simpler, cleaner and more functional.  Replaced the formerly ad-hoc development process with a more streamlined and functional Agile - Scrum development process. Created a process to parse grid data from Acoustic Doppler Current Profilers, writing to a NoSQL DB, and make it available on an OPeNDAP server.  Developed the Coast Buster iOS App for reporting marine debris, specifically in response to the 2011Japanese tsunami.

----
### Software Developer, Remote Sensing Lab, University of Victoria
***July 2010 – April 2011***
* Performed final phase of development of SAFORAH forestry hyperspectral image processing grid-integrated project and brought project online on time and under budget.

----
# Training
* AWS Certified Architecture Associate training, 2020-2021
* Openshift Training — at Continuous Service Improvement (CSI) Lab, Victoria BC, 2019
* UberConf 2019, 2017 - Architecture track.

* Leadership certification — Workplace Communications, Camosun College, 2017
* Project Management Professional Training & Certification, 2015
* Compiler Construction — UVic, 2014

____
____

# Blog Posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
