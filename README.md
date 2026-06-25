# CS305
Through the analysis of advanced security concepts, students will learn how to develop secure code that complies with security testing protocols. In addition to exploring and implementing security concepts through code, students will also learn why and how to apply encryption technologies and techniques to communicate securely.

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
- Artemis Financial is a financial consulting company that develops personalized financial plans for its clients. The company wanted to improve the security of its web application by implementing secure communications and data verification mechanisms. My task was to identify security vulnerabilities and refactor the application to use HTTPS and SHA-256 checksum verification.
  
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
- I successfully identified areas where secure communications and data integrity protections were missing and implemented solutions to addres those vulnerabilities. Coding securely is important because it helps protect sensitive information from unauthorized access, tampering, and cyberattacks. Strong software security helps maintain customer trust, reduces business reisk, and supports regulatory compliance.
  
Which part of the vulnerability assessment was challenging or helpful to you?
- The most challenging part was running and troubleshooting the dependency-check tool because of issues with reaching the vulnerability database and vulnerability database updates. However, this process was also helpful because it provided experience using industry-standard security scanning tools. It reinforced the importance of identifying vulnerabilities in third-party dependencies.
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
- I increased security by implementing HTTPS with SSL/TLS, generating a self-signed certificate, and adding SHA-256 checksum verification to protect data integrity. These measures created multiple layers of protection for data in transit and during verification. In the future, I would continue using vulerability scanners, dependency analysis tools, and secure coding best practices to assess risks and determine appropriate mitigation strategies.
  
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
- I tested the application after each modification to verify that it complied, executed correctly, and produced the expected results. I confirmed secure communications by accessing the application through HTTPS and verified that the checksum functionality worked properly. I also used OWASP Dependency-Check to evaluate the project for known vulnerabilities after refactoring.
  
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
- I used Java Keytool, OWASP Dependency-Check, Eclipse, and Spring Boot configuration tools throughout the project. I also applied secure coding practices such as using cryptographic hashing and encrypted communications. These tools and practices will be valuable for future software development and security related projects.
  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
- I would show employers the refactored application and the accompanying security report that documents the implementation of HTTPS, SSL certificates, and SHA-256 hashing. This project demonstrates my ability to identify vulnerabilities, implement security controls, and apply secure software development practices. It also highlights my experience using industry-standard security tools and documenting technical work.
  
