## Hi, I’m @RebekahGrace4219. 
 
I am a Computer Science and Engineering Senior at University of California - Davis. You can also visit my [Linkedin](https://www.linkedin.com/in/rebekah-grace-2567b41a4/).

# Internships
## Software Engineering Intern - Flatiron Health
This is currently ongoing, as it is a Summer Intern Program, and it ends in September. It's been a lot of fun so far, I am working on a great project. To put it simply, medical data is often stored in PDF reports. This is a problem. When people are looking to see what pharmaceuticals are working or trying to guage rates of diseases amongst demographics, they need structured data. To move PDFs to CSVs, abstractors with medical backgrounds are tasked with translating the documents. This is both time consuming and expensive. It would be much preferred to run an Optical Character Recognition (OCR) program on the PDF and extract the data that way. My project started out as a proof of concept, just to see if using Amazon Textract's Table function was even viable. As I have moved forward, with a lot of set up, the pdf extraction is actually more accurate than the human readers. Also, it runs in less than an hour and costs a tiny fraction compared to the human readers. Now, the scope has grown to adding many different types of reports, and building functions around them. One of the foundational changes that I made for this project was that I wrote code to determine report structures, rather than examining each type of report specially. There is still some work to do, but I have made a lot of progress and I am excited to see where it goes.

## Lecturer - UC Davis
Technically, this is not an internship. I work for UC Davis as a student lecturer on ECS 98F: The Missing CS Quarter, which was inspired by a similar MIT course. Through my own internships and seeing my classmates, it was very clear that there were some skills that Software Engineers should have, but are not explicitly taught in core CS classes. For example, Regex, Git, Unit Testing, and Debugging are all units in this 10 week long class. I have re-written homework assignments, held office hours, and given lecures for the last 3 quarters (my junior year). It's a valuable way to get more experience in these concepts, while also enhancing my soft skills.

## Web Developer/Data Science Intern - UC Davis ECO Team
I worked for my University, analyzing their environmental data. I worked split between the web developement and data science team, which gave me a breadth of experience. I got the see the data pipeline from start to finish. For the data science team, I mostly focused on examining data and finding faults. Sometimes meters go down, and sometimes they are not properly aligned. The faster an anomaly is detected, the faster it can be fixed. I created a neural network model so the engineers could see detected anomalies with a User Interface. As a web developer intern, I also worked on multiple websites for the ECO team. There were internal facing websites, to show the board and managers that financial goals were being met. Additionally, I added features and bug fixes to student facing websites. Working at the ECO team taught me a lot about "Big Data" and the approaches we take with it. It was also a much larger and varied team than I had previously experienced. I worked with UI designers, Front-End specific designsers, Data Scientists, and Data Engineers. That experience was really valuabele, in terms of getting used to real-world teams.

## Software Engineering Intern - UC Davis
Working for Professor Matthew Butner, I lead a 3-intern team in developing a matching program for study groups. I designed the core algorithm, an alteration of the Stable Roommates problem. I assigned portions of the project and folded them into the real version. The program worked directly with the Canvas API to both make groups and notify students, so it was very easy to run. It was an excellent learning experience for working in a team. I was exposed to alternative perspectives and balanced timelines against additional added features. We were always trying to balance what features we could get in with the next release. The final project was presented to other CS Professors at Computer Education Research at Davis (CERD).

# Top 2 Projects
## Smart Traffic
If you're willing to read this, you should really watch the [video](https://smart-traffic-embedded-systems.glitch.me/). I am immensely proud of this project and all the technical work that went into it. Beyond the fact that it won the competition it was made for, it really exempflies my passion for CS. Smart Traffic has two real sides, hardware and software. 

On the physical side, there are TI Launchpads. Each TI Launchpad has two sets of pedestrian walking signals, LED traffic lights, and two Force Sensitive Resistors (FSRs). The FSR are used to measure the weight of little toy cars. The TI Launchpads and server communicate back and forth, sharing information. The TI launchpad will take its orders and control the signals.

The software handles the bulk of the logic. The state of each launchpad is stored and used to calculate the next move. The logic prevents various issues, such as incompatible timing, starvation, and deadlock. There are additional configurations beyond the usual traffic lights. For example, the forward and left turn lane of only one side of a street can be turned on at once, while the opposite side pedestrian light is moving.

Several potential modes exist. One, "Priority Mode" allows the traffic light to be overridden, most likely for a first responder. Others take into account things like pedestrian safety, a mode where all four sides of the traffic stop for the pedestrians to cross. Of course, there are modes that take into account the weighted plates and give priority to the configuration that allows the most cars to run.

## Credit Card Comparator
Credit cards have been giving cash back offers and sign on bonuses for some time. "Churning" is the concept of maximing one's cash back by collecting cards based on their specific offers. For example, a frequent traveler may prefer a card with a 5% hotel offer, even if that card has a $95 dollar annual fee. On the other hand, someone who does not may prefer a card that gives 6% back on groceries. Unfortuneately, the process of finding cards and determining what ones work best for you can be time consuming. Existing comparators, like Nerd Wallet, do not take into account the cards you already own and your budget. Credit Card Comparator does.

Credit Card Comparator is very easy to use. First, estimate your annual expenses in each of the categories. Then, check off the cards you already own from the list. Then, submit your response and wait for a comprehensive list.

# Contact
email: My school email is rmgrace@ucdavis.edu. I also use rebekahgrace234@gmail.com for recruiting, so either is fine. Please reach out if you have a position you're recruiting for or any questions.


<!---
RebekahGrace4219/RebekahGrace4219 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
