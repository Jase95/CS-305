CS 305 Module Eight Journal 
Jason McDaniel
CS 305
10-20-2026
Cory Thoma

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address? My client is a financial services company that goes by the the name Artemis Financial. Artemis creates custom financial plans as well as handle sensitive customer information. Due to the nature of the services they provide, Artemis needed its web-based financial application to be secure and adhere to the best practices in software security. The main objective to this project was to secure their codebase and provide encryption for data in transit and make sure their software development procedures met industry security standards.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being? In this project I worked to implement secure coding standards to mitigate vulnerabilities and reinforce the application's defenses. I was able to configure the HTTPS encryption with a self-signed certificate, rewrite the Spring Boot setup to require encrypted communication, then analyze the code for vulnerable dependencies and delete them. The importance of secure coding lies in the fact that flaws can result in data exposure, financial loss, and damage to reputation. A strong security posture in software will boost user trust, prevent illegal access and assure the continued reliability of an organization's operations.

Which part of the vulnerability assessment was challenging or helpful to you? The thing I found that was challenging was assessing which dependencies were vulnerable indicated by the OWASP Dependency-Check tool and identifying which dependencies were actually risky. Learning how to evaluate third-party libraries better and understand how they effect application security as well as balance the demand for functionality with the need for updates or replacements.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? I ran the application locally and tested all the endpoints using HTTPS to verify that the program still works. I also re-ran the vulnerability scan following the refactoring to ensure any issues that were previously identified were remediated and new vulnerabilities were not discovered. Regression testing and several scans were essential to verify functionality and security. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? The resources I've used were secure-coding references, certificate generation tools, and dependency-scanning using OWASP. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment? I would showcase my Artemis Financial report and refactored code to potential employers to show them that I can implement practical security principles. I can use these as references to demonstrate my ability to protect sensitive data as well as uphold secure coding standards when it comes to software projects. 
