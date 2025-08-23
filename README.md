# CS-305-Final-Journal

•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

*Artemis Financial is a consulting company that develops financial plans for clients including savings, retirement, investments, and insurance. They are working with my company, Global Rain, which specializes in custom software design and development to modernize their operations. Artemis Financial currently has a RESTful web API and a public-facing web interface, and they are seeking to enhance the security of their systems to better protect client data and financial information.* 

•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

*When discovering Artemis Financial’s software security vulnerabilities, I did well at systematically identifying security weaknesses across the project. Starting with transport security by choosing appropriate ciphers. Then application-layer risks including input validation, authentication and session handling. Finally, I identified dependency risks in the outdated libraries. 
Coding security matters because it prevents data breaches, service outages, and regulatory exposure.  Secure software protects client trust, preserves brand reputation, and reduces long-term operational costs by avoiding emergency fixes and incident response.*

•	Which part of the vulnerability assessment was challenging or helpful to you?

*The most challenging aspect of the vulnerability assessment was establishing a functional development environment. I had to repeatedly reinstall Eclipse and multiple Java versions to resolve compatibility issues, which was both time-consuming and disruptive. Identifying outdated libraries within the codebase also proved difficult, as the available resources often didn’t address the specific problems I encountered. Additionally, some packages in the codebase were incorrectly named, which required several hours of troubleshooting before discovering.*

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

*I increased layers of security by implementing the use of both ciphers and cryptographic hash functions. Utilizing these complimentary security measures covers securing data during transmission or storage and protects the certificate keys. In the future I will do a full assessment of the code base from package names to dependency versions. When receiving a nearly complete code base it is essential to ensure that it was created properly. Once this is established I would ensure the libraries are all up to date and implement Spring boot and Maven to check for vulnerabilities.* 

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

*To ensure functionality and security, I wrote unit and integration tests for cryptography utilities and configured the project to run static analysis and dependency scans. After refactoring, I performed regression tests and searched for any newly introduced weaknesses utilized the dependency scanner and ensuring the checksum was properly implemented.* 

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

*This project introduced me to Spring Boot, a Java framework that helps create and run java applications and Maven, a build tool that simplifies packaging, testing, and deploying Java projects. I will continue to use these resources in future projects.* 

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

*Rather than focusing on specific code excerpts to showcase induvial methods, I’d choose to highlight the lessons learned from the code I wrote and integrated. One key takeaway was the importance of thoroughly reviewing an inherited code base, examining it closely pixel by pixel to ensure it was structured and implemented correctly. Another valuable lesson was realizing the need to maintain a single JDK version on my system, as multiple installations can cause compatibility issues and confusion within Eclipse.* 
