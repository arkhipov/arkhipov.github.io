---
layout: page
title: Curriculum Vitae
permalink: /cv/
---

## Employment

### Head of Service, Yandex.Cloud IAM (Identity and Access Management)

June 2018–Present, [Yandex LLC (Moscow, Russia)](http://yandex.com/){:.external}

### Senior Software Engineer

December 2016–June 2018, [Yandex LLC (Moscow, Russia)](http://yandex.com/){:.external}

Skills used: Java Core, Real-Time Stream Processing, Spring, Zookeeper, MongoDB, Python.

### External Consultant

December 2016–Present, [Irkutsk Diagnostic Center (Irkutsk, Russia)](http://idc.ru/){:.external}

### Chief Technology Officer

July 2014–December 2016, [Irkutsk Diagnostic Center (Irkutsk, Russia)](http://idc.ru/){:.external}

Skills used: Java EE (Wildfly, Clustering and HA, Hibernate Envers, Hibernate Search), Java FX (ReactFX), APT, XSLT (Saxon, Xalan), XSL-FO (Apache FOP), PostgreSQL.

I was responsible for leading three teams of 10 software developers, reviewing and coding critical parts of the system, discussing requirements, training the personnel and interviewing candidates. The system I had been working on was a complex distributed ERP for a large healthcare enterprise written mainly in Java EE and running on CentOS, Wildfly Application Server, Mondrian BI and PostgreSQL with web-based and Java FX backends powered by REST, JSON and WebSockets.

My work in this position began with the replacement of the legacy document rendering system with templates in XSL-FO to generate medical documents in PDF using Apache FOP and Saxon. It provided much flexibility on the presentation layer and allowed end users to customize the views themselves. The main issues that we faced related to performance and scalability with large documents. It also offered an opportunity to brush up on my computer typography skills.

Other projects were mostly related to upgrading legacy UI using Java FX and ReactFX, refactoring of the existing domain model and integration with third-party services, including integration with the online payment solution of Sberbank via SOAP. It allowed customers to purchase medical services using credit or debit cards online.

While previously my experience was largely technical, this role allowed me to the opportunity to test both my interpersonal and technical skills. I found it both a challenging and rewarding experience.

### Senior Software Engineer

April 2010–July 2014, [Irkutsk Diagnostic Center (Irkutsk, Russia)](http://idc.ru/){:.external}

Skills used: Java EE (JBoss, EJB, JPA, Hibernate, SOAP, JAX-RS, WebSockets, JMS, JSF), MyBatis, OSGi, JUnit, Arquillian, JMeter, PostgreSQL (PL/pgSQL), JTAPI, SMPP, JasperReports, Maven, Bash, RPM, Git, Agile, SCRUM, Atlassian Confluence/JIRA/Bamboo/Stash.

My new role started with leading a team of two in migration of the database from MaxDB to PostgreSQL. The total scope of application migration was approximately two million lines of code. There were also significant technical challenges as the database had to be bitemporal, managing time-varying data and keeping a history of all data changes. We successfully completed the project on time in December, 2010.

The next project was to migrate to the application server, while still keeping the legacy applications operational. The majority of the work in that position involved managing a team of 2–3 developers and supervising and training staff. I also had to write and tune the most critical parts of the project and review the code of others.

There were also several new features added to the system. Aside from the routine integration tasks with SMSC providers via SMPP and JasperReports Server, we integrated the system with our Avaya phone system (AES and WFO) using JTAPI. The most interesting part of the project was building a solution to aggregate and distribute real-time events from the phone station across the clients using Websockets.

As a side project, I created an automated planning system for scheduling patients’ appointments, saving hours of tedious manual work. Since the problem is NP-hard in general, there had been a great deal of research done in which heuristic techniques had been applied. The optimal solutions were obtained via IDDFS for small dimensions and via a simulated annealing based algorithm for large dimensions.

While I was mostly concerned with my specific projects, I was also involved generally in the company with discussions about restructuring of process and architecture across teams. I initiated a move towards Agile software development techniques which resulted in a substantial gain in productivity. I developed the release policy and coding standards; code review and automated testing became an integral part of the development process. I also played a strong role in directing the business analysis and development process into a more formal model.

In addition, I also suggested using Atlassian products for issue tracking, collaboration and software development and developed a number of plugins for them.

### Software Engineer

February 2007–April 2010, [Irkutsk Diagnostic Center (Irkutsk, Russia)](http://idc.ru/){:.external}

Skills used: Java SE (Multithreading, JNI, Swing, Applets), Java EE (Tomcat, JSP, Servlets, GWT), MaxDB, Microsoft Visual C++, DirectX, Video4Linux, ffmpeg, DICOM (Dcm4Che), OLAP Mondrian (MDX), ABBYY FormReader, Javascript (jQuery), Ant, Autotools, Subversion.

I worked on a range of projects, including implementing ERP, data warehousing, developing video capture software for medical equipment. Since I had neither any contact with the Java language nor any experience developing cross-platform applications, this involved a steep learning curve of both the system and the language.

The ERP was a complex distributed healthcare information system written primarily in MaxDB (formerly SAP DB) stored procedures, relying on Java Applets and Mozilla XUL/Javascript on the client side. Much of my work focused on developing and tuning SQL scripts, Java applets and Swing-based configuration tools, followed by providing a solution for paper-based and electronic laboratory analysis referral forms processing using ABBYY FormReader (currently FlexiCapture).

Subsequently, I created cross-platform video streaming and recording software that allows to stream and store video from DICOM as well as and non-DICOM modalities to a PACS server. The software had to run on a variety of systems, so it was decided to write two different implementations using DirectX and Video4Linux/ffmpeg and integrate them with the clients using the JNI. There were lots of difficult threading and streaming situations as some codecs are not frame-based.

Among other things, I also took a minor part in the development of the client portal with GWT and the Business Intelligence Server with Mondrian ROLAP/BI and PostgreSQL.

### Junior Software Engineer

January 2004–February 2007, [Irkutsk State Technical University (Irkutsk, Russia)](http://istu.edu/eng/){:.external}

Skills used: Microsoft SQL Server (Transact-SQL), Borland C++ Builder (VCL).

While pursuing my studies, I worked part time as a junior C++ engineer for the company that won the government contract for development of the road network information system. At first, I was responsible for the design and implementation of the UI using Borland C++ Builder and then also for the server side using Microsoft SQL Server and Transact-SQL. By the middle of 2006, we had developed and had implemented algorithms to minimize the long-term life-cycle costs of maintaining the road network, which had eventually ended up in my master’s thesis and a series of journal articles.

## Open Source and Community

### [PostgreSQL Access Control List Extension](https://github.com/arkhipov/acl/){:.external}

The extension provides a mechanism to control the access to data by using ACLs. It works either with the PostgreSQL roles system or with application-specific roles and users.

### [PostgreSQL Temporal Tables Extension](https://github.com/arkhipov/temporal_tables/){:.external}

The extension allows you to maintain an audit trail of changes to PostgreSQL tables. Although it was never used as intended, as we switched to Hibernate Envers, [some people](http://clarkdave.net/2015/02/historical-records-with-postgresql-and-temporal-tables-and-sql-2011/){:.external} have found the extension useful.

I am also an occasional contributor to numerous open source projects, including Wildfly/JBoss Application Server, PostgreSQL, Apache FOP, Hibernate.

## Education

### MSc. in Applied Mathematics and Computer Sciences, with Honors
September 2001–June 2006, [Irkutsk State University (Irkutsk, Russia)](http://isu.ru/en/){:.external}

Selected Courses:

* Software Engineering
* Algorithms Complexity Analysis
* Database Theory
* Cryptography
* Game Theory
* Discrete Mathematics

## Certificates

* [Oracle Certified Associate, Java SE 8 Programmer (May 2015)](https://www.youracclaim.com/badges/ae0a7356-1c6a-4226-9269-55cee0ca9bf9/public_url/){:.external}
* [Oracle Certified Professional, Java SE 8 Programmer (June 2015)](https://www.youracclaim.com/badges/3da1a4cf-c1d2-4744-a213-95d83207923e/public_url/){:.external}
* [Oracle Certified Expert, EE 6 Java Persistence Developer (March 2016)](https://www.youracclaim.com/badges/9093f4d9-9c17-4413-a121-aa0de34115a7/public_url/){:.external}
* [Oracle Certified Expert, EE 6 Java EE 6 Enterprise JavaBeans Developer (June 2017)](https://www.youracclaim.com/badges/60f14510-62bf-4af8-84c1-45cc686e12cb/public_url){:.external}

## Publications

Martyanov V.I., **Arkhipov V.V.**, Katashevzev M.D., Pakhomov D.V. 2010 Logic-Heuristic Methods for Solving Combinatorial Problems of High Complexity Applications Preview *Modern Technologies. System analysis. Modelling* **4 (28)**, 61–67.

**Arkhipov V.V.**, Konstantinov Y.M., Martyanov V.I., 2010 Logic-Heuristic Methods for Considering Secondary Structure of RNA *Modern Technologies. System analysis. Modelling* **1 (25)**, 162–167.

Martyanov V.I., **Arkhipov V.V.**, Pakhomov D.V. 2009 Methods of Rational Management and Maintenance Planning of Road Networks *Modern Technologies. System analysis. Modelling* **2 (22)**, 42–50.

Martyanov V.I., Pakhomov D.V., **Arkhipov V.V.** 2005 Review of Methods of Maintenance Planning of the Road Network of the Irkutsk Region *New Technologies in Investment and Construction Activities* **1**, 123–129.
