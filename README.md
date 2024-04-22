# CS-305-Software-Security
# Module 8: Journal Questions
1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address? 
Artemis Financial is a financial services company that handles sensitive financial data and also deals with cross-border data transfers. Their software requirements focused on secure communication and data encryption. The key issues they wanted me to address included threats like SQL injection, Distributed Denial of Service (DDoS) attacks, and the need for compliance with international regulations. They required efficient security measures to safeguard sensitive information and ensure business continuity

2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
In my addressing of software security vulnerabilities, I performed a comprehensive code review in order to identify potential risks. This included checking for injection vulnerabilities and hardcoded sensitive information. It's important to code securely to prevent data breaches and ensure business operations are not disrupted. Software security adds significant value to a company's wellbeing by protecting sensitive data, maintaining customer trust, and reducing the risk of reputational damage​​.

3. What part of the vulnerability assessment was challenging or helpful to you?
The challenging part of the assessment was dealing with the number of outdated dependencies and the need for manual code reviews. However, these tasks were also helpful because they allowed me to gain even more hands-on experience in identifying vulnerabilities, such as SQL injection and insecure error handling. I also found it useful to work with static testing tools to discover security flaws in the codebase​​.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
In order for me to increase security layers, I upgraded vulnerable dependencies, implemented input validation, and replaced hardcoded database connections with secure environment variables. I also focused on secure client-server communication and used secure frameworks like OAuth2.0. In the future, I would continue using dependency check reports and static analysis tools to assess vulnerabilities. My choice of mitigation techniques would depend on the severity of the identified vulnerabilities and best practices in secure coding​​.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the application was functional and secure, I conducted extensive testing, including static and dynamic analysis. After refactoring the code, I checked for new vulnerabilities by running more automated tests and reviewing logs for any unusual activity. I also employed proper error handling practices to ensure sensitive information wasn't leaked through error messages​​.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The resources and tools that were most helpful to me included static analysis tools and dependency check reports. These tools allowed me to identify vulnerable dependencies and other security risks. I also used secure coding practices like encapsulation, input validation, and secure API interactions to strengthen my codebase​​.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I would show future employers the vulnerability assessment reports and demonstrate how I identified and mitigated security risks. This includes me upgrading outdated dependencies, implementing input validation, and creating a comprehensive mitigation plan. These examples highlight my ability to improve security and protect sensitive information for companies such as Artemis Financial where financial data is critical to protect. 
