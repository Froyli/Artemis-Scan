 Artemis-Scan
Customer and Preferences

Artemis Financial is an advising firm that prepares custom financial plans to individual clients, retirement, investment and insurance. They wanted secure communication channels in their public web application that would secure sensitive financial data. More precisely, they desired file verification with the help of checksums, strengthened encryption, and HTTPS support.

What I Did well and the importance of secure coding

I was able to refactor the application to support checksum validation, secure HTTP protocol and certificate generation. This helped in that sensitive data could be communicated in a secure way. Secure coding is important since it avoids breaches, builds confidence in clients and safeguards the economic welfare of the company. In the case of a financial services company like Artemis, security has direct implications on customer confidence and compliance to the laws of the industry.

The difficult or good sections of the assessment

Configuring Java Keytool certificates and integrating them was the most tricky thing and able to validate secure connections in Eclipse. This process opened my eyes to learn more about the public/private keys as well as TLS set-up. The most useful thing was the dependency-check Maven plugin, which gave some insight into how my project was vulnerable to dependencies and served to verify that refactoring code I did did not create new vulnerabilities.

Improving the Layers of Security & Approaches to the Future

I enhanced additional security by:

Included shape checksum proofreading

The HTTPS communication through certificate implementation

It checks the program using dependency and static tests to identify the vulnerabilities.

I would utilise more tools in future including OWASP ZAP, SAST/DAST tools and threat modelling frameworks that would help me find the vulnerabilities so that I can select the most appropriate mitigation measures.


Testing functions abilities and security following refactoring

To confirm that functionality is intact I tested the code by running the refactored application, performed the checksum validation and retrieved the secure address at https://localhost:8443/hash. I also verified that security was not undermined by re-executing Maven dependency-check plugin and checking that no new vulnerabilities were revealed as a result. Manual functional testing also confirmed the accuracy of the fact that the software was compiled, and running without errors.

Sources, Tools, and Practices in Use

Java Keytool in order to generate certificate.

maven dependency-check plugin to perform vulnerability scanning.

Secure communications protocols include HTTPS/TLS.

OWASP Top 10 guidelines of putting secure coding practices into place.

These tools and techniques will be applicable in future projects and specifically in cases where there is need to deploy enterprise level applications, which require secure deployment.

Value to future employers

This project will show my capacity to:

Pick up and correct software vulnerable points.

Employ up to date encryption and secure communication standards.

Test software security, both manually and through automated [in]put.
Future employers will learn that I have the ability to provide production quality, secure applications that prevent client data exposure.

Repository Link:
(https://github.com/Froyli)
