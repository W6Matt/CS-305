# CS-305

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial service company. Artemis is subject to many legal requirements to secure financial and private information. It is vital for a financial company to maintain the trust of its customers; for this reason, it is essential that Artemis software is secure and up today to minimize unauthorized access.

•	What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

The first thing I did when I found a vulnerability was check if the dependent package was used in the project. If the package was not used, I removed the package. Next, I updated the pom.xml to allow Maven to update the packages from Maven’s repository. Updating the packages typically solved all vulnerabilities.

•	What part of the vulnerability assessment was challenging or helpful to you?

It was difficult to identify false positives.

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Layers of security were added during this project. An SSL certificate is one of today's most basic but vital security tools. Knowing who you are communicating with is crucial to security.

•	How did you ensure the code and software application was functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I reran the Maven dependency checker tool and manually reviewed the code. I also use IntelliJ IDE, which has many built-in testing capabilities.

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Maven is a great plug-in. Maven has many testing capabilities that are useful in finding issues with dependencies. Maven repository and update function may be one of the more essential tools to keep packages up to date in the future.

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

Project Two is an excellent example of identifying issues and resolving them. During the project, I utilized the Vulnerability Flow Chart to step through business best practices and common problems to ensure security.
