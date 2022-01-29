>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \:  35     |            |
|-------------------|------------|
| Student Names:    |    UCID    |
| Luis Sulbaran     | 30090906   |
| Adam Abouelhassan | 30087777   |
| Jaxson Waterstreet| 30095706   |  
| Sadia Khan        | 30090271   |

# Introduction

Exploratory Testing:

Exploratory testing is a software testing approach that is unstructured and intuitive to humans. It is performed without a set plan/script. For exploratory testing, it is necessary for the tester to have a solid understanding of what the application being tested does, as it will give the tester general context and a firm grasp on testing requirements. Thus, a tester should increase their knowledge and learn about the software by exploring it. It also grants testers greater freedom as they are released from testing restraints that come along with following a script. Tests are designed and executed at the same time, and the following tests are designed based on the current step. Testers have the ability to traverse in any direction they desire, as they move along in the application and look for bugs.

Manual Functional/Scripted Testing:

Manual scripted testing is another software testing approach that is much more structured and systematic, as it has a set of guidelines to be followed. The given path is called a script and is written by the tester themselves, or possibly someone else. It must be followed with no deviation during testing. The script includes the documented test cases and test steps that were designed and reviewed by the tester. Execution of the tests occur after the script has been created. Since the sequence and process of test cases can be shared with others, manual scripted testing can be performed by different testers as well. A drawback of this testing is that with a script, the same fault is missed every time if the fault is outside of the testing range.

# High-level description of the exploratory testing plan

The exploratory testing plan we followed was quite simple, as this testing approach is generally unplanned and goes with the flow. We intended to test the system by exploring each and every option that could be selected. Functions that were targeted included
-    	turning the ATM on and off
-    	entering the number of bills into the ATM
-    	inserting/ejecting a card
-    	entering the card’s pin
-    	choosing the transaction type
-    	withdrawing money from checking, savings, money market
-    	amount withdrawn
-    	inserting deposited money into an envelope
-    	depositing money to checking, savings, money market
-    	amount deposited
-    	transferring from/to checking, savings, money market
-    	amount transferred
-    	inquiring account balance
-    	accepting/declining another transaction
-    	taking the receipt
-    	showing, clearing, and hiding the log
The approach taken to test these functions was to test the functions once and see if a bug was present. If it functioned appropriately, we just continued to the next step of the simulation. We tested the most common paths to see if a user could follow through to get their job done successfully.

# Comparison of exploratory and manual functional testing

During the first stages of our testing, we conducted Exploratory Testing, which required us to divide into pairs. One partner would use the ATM app conducting several different operations while the other would record any observed defects. Further into the testing stages, we conducted Manual Functional Testing, where we all joined together to test each of the test cases in Appendix C. We had one group member using the ATM app, one member describing the test case, and two members recording the defects on the back log. The Exploratory Testing allowed us to freely test the ATM app, using our experience to target potential defects and corner cases. This testing was faster and required less people than the Manual Functional Testing, however it failed to cover many defects observed during the Manual Functional Testing phase. The Exploratory Testing sacrificed quality of testing while allowing for faster, and less resource extensive testing. The Manual Functional Testing ensured testing of all major ATM functionalities where the exploratory tests may have missed, and properly documents the defects including the steps to reproduce the defect as well as the actual and expected outcomes. This method of testing is tedious and resource extensive however it is essential in verifying the core functionality of any app. Both the Exploratory Testing and Manual Functional Testing methods have their pros and cons, which makes them both very important when finding defects in any app.

# Notes and discussion of the peer reviews of defect reports

Before breaking into pairs, we as a group decided on a general format of how we want our bug reports to be formatted and did one together as a group of four to set a standard. After each pair had finished their portion of the testing we got back together as a group and went over the reports and addressed any issues that came up. Both teams had overlapping findings, but also a few different ones.

# How the pair testing was managed and team work/effort was divided 

During the pair testing, we were able to split off into pairs and agree to come back in roughly 30 minutes once we recorded the defects we discovered. This allowed us to then all come back together, compare our results, and submit them into the backlog system. As for teamwork/effort, our team was able to efficiently communicate with each other via Discord to organize the time and days we were going to meet up. This made it easy for us to progress through the lab together and learn from each other as we did each of the testing methods. As we were all able to meet up when working in the lab, everyone was able to equally contribute and put in the effort to be successful in the lab. For the lab report, we all went together through each of the questions to jot down what we learnt and points we were going to mention in our paragraphs. We each took on two questions and gathered before submitting the report to review everyone's answers and made sure we met the requirements for the lab.

# Difficulties encountered, challenges overcome, and lessons learned

Throughout this lab when working through the test cases on Appendix C for the Manual Scripted Testing, we encountered some difficulties in some of the test cases. Test cases 36-40 had unclear initial state systems conditions, which then drew some confusion towards the input the system test case wanted. We also had some difficulty when coming up with the steps to reproduce the defect/bug in the backlog tracking system. We didn't know if this meant to include all steps leading up to the bug from the moment the system turned on, or if it was the steps taken from the initial state of the system in the test case. Some challenges that we overcame during this lab was getting comfortable with the backlog tracking system and being able to test in pairs. Through these challenges we were able to learn a lot about the importance of being able to report and track bugs. We are able to obtain a lot of information through these reports and how useful it was in recording the version and status of the project we were working with along with any other crucial details. We also learnt the techniques and methods that the different testing methods use, when they are used, and the advantages/disadvantages in each of them as mentioned throughout this report.

# Comments/feedback on the lab and lab document itself

For the majority our first lab for this course and our first time working as a group went smoothly. The only real issue that our group came across was some instructions being a bit unclear. Some of the test cases in Appendix C were hard to understand. And some of the Backlog instructions took longer than they should have as we tried to figure out this new tool, this could easily be avoided with a few more visuals.
