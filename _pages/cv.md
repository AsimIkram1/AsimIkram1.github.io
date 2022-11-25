---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="https://github.com/AsimIkram1/asimikram1.github.io/raw/master/files/Asim_Ikram_CV.pdf" download>Download CV</a>

Work experience
======
* ## Graduate Research Assistant
  * **Washington University in Saint Louis, MO, USA**
  * **Aug 2021 - Sep 2022**
  * Implemented various strategies to improve the performance of the Cilk runtime written in C and C++
  * Wrote code to enable fine-grained instrumentation in the runtime
  * Wrote Python scripts to plot interactive graphs using the instrumentation data. Added the ability to select a subsection of the data to ease rendering of the graphs

* ## Research Associate
  * **National Center for Cyber Security**
  * **Mar 2020 - Jul 2021**
  * Designed and implemented code architecture
  * Wrote asynchronous server side code using socket.io
  * Performed analysis on the extracted data and added interactive plots to show the analysis
  * Wrote automated test cases (using UI Vision RPA)
  * Set up code integration and deployment. Wrote an installer package (.deb) for Linux based systems using debconf. Implemented a method that would only allow the code to run only when a provided USB flashdrive was inserted into the system.
  * Coordinated tasks between group members using JIRA and set up integrations to the repository for easier task tracking, management and time-saving.
  * Conducted technical interviews and helped new members get on-board with the project

* ## Research Assistant
  * **National Center for Cyber Security**
  * **Mar 2019 - Mar 2020**
  * Research and development on mobile device forensics
  * Wrote code to get a physical copy (iso) of an Android device
  * Wrote backend code to extract and parse data from an extracted image. Each part could work standalone and could easily be called using REST API calls
  * Used ORM to communicate to data stored in databased
  * Wrote front-end code to display extracted data

*  ## Software Design Engineer
  * **XFlow Research Inc**
  * **Jul 2018 - Mar 2019**
  * **Virtual BNG**: Studied and implemented the PPPOE and LCP protocols. Also tested the protocols using the rp-pppoe client. Both versions of the code were written such that they could be easily extended.
  * **Virtual BRAS**: Implemented a central command line interface to manage virtual machines. Wrote a deployment script to automatically install the tool on the required system. Helped the testing team by running the provided unit test cases as well as reporting and fixing bugs. 

Education
======
* ## Master of Computer Science
  * National University of Computer and Emerging Sciences, Islamabad
  * CGPA: 3.77/4.00
  * 2016 - 2018
* ## Bachelor of Computer Science
  * National University of Computer and Emerging Sciences, Islamabad
  * CGPA: 3.30/4.00
  * 2012 - 2016

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
Projects
======
* **DNS Spoofing**
  * A DNS spoofer that consisted of setting up a DNS server and redirecting a user to a fake website. The project was part of the Stanford CS-155 course.
    * Tools and Technologies: Python, Scapy, Bind9.

* **Distributed Password Cracking System**
  * A system that used concepts of distributed systems to crack a password.
    * Tools and Technologies: Golang, Atom

* **GPU Cache Bypassing**
  * A code that automatically modified Nvidia PTX code to include cache bypasses to improve GPU cache performance.
    * Tools and Technologies: Java, Nvidia Visual Profiler, Nvidia Geforce GT 630m.

* **CodePlay**
  * A tool that automatically converted code written in Java to C# and vice versa.
    * Tools and Technologies: Java, C#.

Skills
======
* Python
* C\C++
* Javascript/JQuery
* Latex
* Linux
* Git

Awards
======
* Gold Medalist in MS (CS)
* Multiple time Dean's list award holder

Languages
======
* **English** - Excellent (IELTS Score: 8.0/9.0)
* **Urdu** - Native Language
