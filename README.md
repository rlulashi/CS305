# CS305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial wanted to add a verfication step to helpe keep secure transactions between their clients. 


What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I felt comfortable being able to run a dependancy check to find the vulnerabilities in the first place. They were behind on the latest updates to SpringBoot applications which would eliminate their problems. Without secure coding, valuable assets are at risk which can be detrimental depending on the type of personal identifiable information present. Software security adds a layer of protection and safety to a company. There's already a large stress held in any company, having a safety net with a strong software security team will aid greatly to the company's success. 


What part of the vulnerability assessment was challenging or helpful to you?
I struggled to generate a self-signed certificate but I was able to get one, but later ended up having difficulty in getting the code to demonstrate the secure connection. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Introducing an algorithm cipher, specifically SHA-256 due to its ability to hash. Taking time to learn which algorithms do what task will help me in the future. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Comparing the reports from before I introduced SHA-256 and after showed a reduction in vulnerabilities but did not remove them all. The biggest vulnerabilities were the SpringBoot application was on 2.3.4 when updating to the latest either 3.0.6 or 2.7.11 would be beneficial. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Learnining about algorithms and implementing a dependancy check are tools I will be using as often as possible moving foward. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show the refactored code and the ability to generate a self signed certificate. 

