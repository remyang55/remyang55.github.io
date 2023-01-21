---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---
<img src="/assets/profile_pic.jpg" alt="Profile Picture" style="float:left; margin-right:5%" width="23%" />

Hope you're having a great day! I am a fourth-year undergraduate student studying computer science at the [University of Illinois Urbana-Champaign](https://cs.illinois.edu/) (UIUC). Please send me an email if you'd like to talk about anything at all! My CV and contact information are available below.  


<span style="display:block">Email: <a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a></span>
<span>Github: <a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><span class="username">{{ site.github_username| escape }}</span></a></span>  
[My CV](/assets/RemYang_CV.pdf)

## News ##
<hr style="margin-top:-1em; margin-bottom:1em; height:2px; background-color:black; border:none" />
**[01.2023]** Our paper has been accepted at ICLR 2023 (notable top 25%)  
**[12.2022]** Received an Honorable Mention for the CRA Outstanding Undergraduate Researcher Award  

## Research ##
<hr style="margin-top:-1em; margin-bottom:1em; height:2px; background-color:black; border:none" />

**Provable Defense Against Geometric Transformations**  
<u>Rem Yang</u>, Jacob Laurel, Sasa Misailovic, Gagandeep Singh  
_Accepted (<span style="color:red">notable top 25%</span>) at the International Conference on Learning Representations (ICLR) 2023._  
[Full Text](/assets/Geometric_Provable_Defense.pdf) &bull; [OpenReview](https://openreview.net/forum?id=ThXqBsRI-cY)

**Multi-Modal Self-Supervised Learning for Satellite Image Time Series Segmentation**  
Jayanth Shenoy*, <u>Rem Yang*</u>, Han Zhao, Deepak Vasisht  
_Under review._  

**A General Construction for Abstract Interpretation of Higher-Order Automatic Differentiation**  
Jacob Laurel, <u>Rem Yang</u>, Shubham Ugare, Robert Nagel, Gagandeep Singh, Sasa Misailovic  
_ACM SIGPLAN Conference on Object-oriented Programming, Systems, Languages, and Applications (OOPSLA) 2022._  
[Full Text](/assets/OOPSLA2022_Final.pdf) &bull; [ACM DL](https://dl.acm.org/doi/10.1145/3563324)

**A Dual Number Abstraction for Static Analysis of Clarke Jacobians**  
Jacob Laurel, <u>Rem Yang</u>, Gagandeep Singh, Sasa Misailovic  
_ACM SIGPLAN Symposium on Principles of Programming Languages (POPL) 2022._  
[Full Text](/assets/POPL2022_Final.pdf) &bull; [ACM DL](https://dl.acm.org/doi/10.1145/3498718)

**Statheros: Compiler for Efficient Low-Precision Probabilistic Programming**  
Jacob Laurel, <u>Rem Yang</u>, Atharva Sehgal, Shubham Ugare, Sasa Misailovic  
_ACM/IEEE Design Automation Conference (DAC) 2021._  
[Full Text](/assets/DAC2021_Final.pdf) &bull; [IEEE Xplore](https://ieeexplore.ieee.org/document/9586276)

**Federated Machine Unlearning**  
<u>Rem Yang</u>, Supriyo Chakraborty, Parijat Dube  
_Illinois Scholars Undergraduate Research (ISUR) Expo 2022._  
[Poster](/assets/ISUR2022_Poster.pdf)

## Experience ##
<hr style="margin-top:-1em; margin-bottom:1em; height:2px; background-color:black; border:none" />

### **Connected Systems Lab** ###
(*Current*: Spring 2022 - ) Working with [Professor Deepak Vasisht](https://deepakv.web.illinois.edu/) and [Jay Shenoy](https://jayshenoy.web.illinois.edu/index.html) on wireless and satellite systems research.

### **Approximate and Resilient Computing Group** ###
(*Current*: Spring 2020 - ) Working with [Professor Sasa Misailovic](https://misailo.cs.illinois.edu/), [Professor Gagandeep Singh](https://ggndpsngh.github.io/), and [Jacob Laurel](https://jsl1994.github.io/) on programming languages and machine learning research.

### **Teaching (Course Assistant)** ###
(Fall 2020 & Spring 2021) [CS 225 Data Structures](https://courses.engr.illinois.edu/cs225/sp2021/).
Helped students with machine problems and labs in weekly lab sections and office hours.  

(Spring 2020) [CS 126 Software Design Studio](https://courses.grainger.illinois.edu/cs126/sp2020/staff/).
Facilitated weekly 2-hour code reviews with 5 students, which consisted of project presentations and discussions of program design, style, and testing; also graded students' projects.

### **Psyonic** ###
(Fall 2020) Part-time internship: developed mobile application that interfaces with [Psyonic](https://www.psyonic.io/)’s bionic arm in React Native and deployed app on Android and iOS.


## Projects ##
<hr style="margin-top:-1em; margin-bottom:1em; height:2px; background-color:black; border:none" />

### **Illinois Computer Science Sail Website** ###
[Source Code](https://github.com/SAIL-UIUC/sail-website). _Created with Django and hosted on an Apache server with a MySQL database._  
I wrote a brand-new website over the 2020 summer for UIUC's Sail event, [linked here](https://sail.cs.illinois.edu/), which is currently maintained by the wonderful 2022 Sail Staff. The website allows teachers and students to easily sign-up for accounts and create/register for courses; it also has an interface for administrative tasks like sending massmails to participants.

### **Tranzlate: The Zoom Translator** ###
[Source Code w/ Demo](https://github.com/remyang55/tranzlate). _Created with React.js._  
I made this for HackIllinois' [HackThis](https://hackthis.hackillinois.org/) virtual hackathon. The web app provides a convenient interface to translate Zoom meetings on-the-fly: on the top is a zoom meeting window, while on the bottom is a scrolling text box that transcribes and translates the meeting audio.

### **Finger Ninja** ###
[Source Code](https://github.com/remyang55/finger-ninja). _Created with C++ openFrameworks._  
I created this as a final project for UIUC's CS 126 Software Design Studio class. The game uses openFrameworks' openCV library so that you can play the classic Fruit Ninja game by swiping your finger in front of your laptop's webcam.
