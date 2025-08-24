# Artemis-Scan
Client and Requirements

Artemis Financial is a consulting company that develops personalized financial plans for clients, including retirement, investments, and insurance. They requested secure communication mechanisms for their public web application to protect sensitive financial information. Specifically, they wanted file verification using checksums, encryption enhancements, and HTTPS implementation.

What I Did Well & Importance of Secure Coding

I successfully refactored the application to include checksum verification, HTTPS protocol, and certificate generation. This ensured that sensitive data could be transmitted securely. Secure coding matters because it prevents breaches, maintains trust with clients, and protects the financial stability of the company. For a financial services business like Artemis, security directly impacts customer confidence and compliance with industry regulations.

Challenging or Helpful Parts of the Assessment

The most challenging part was configuring Java Keytool certificates and integrating them with Eclipse to validate secure connections. This process helped me better understand public/private key usage and TLS configuration. The most helpful aspect was using the dependency-check Maven plugin, which provided insight into vulnerabilities in project dependencies and confirmed that my refactored code did not introduce new risks.

Increasing Layers of Security & Future Approaches

I increased layers of security by:

Adding cryptographic checksum validation.

Implementing HTTPS communication through certificate configuration.

Running static and dependency checks to identify vulnerabilities.

In the future, I would use additional tools such as OWASP ZAP, SAST/DAST analyzers, and threat modeling frameworks to identify weaknesses and choose the best mitigation strategies.

Verifying Functionality and Security After Refactoring

To verify functionality, I ran the refactored application, executed checksum validation, and accessed the secure URL at https://localhost:8443/hash. I confirmed security by re-running the Maven dependency-check plugin and reviewing that no new vulnerabilities were introduced. Manual functional testing further validated that the software compiled and executed without errors.

Resources, Tools, and Practices Used

Java Keytool for certificate generation.

Maven dependency-check plugin for vulnerability scanning.

HTTPS/TLS protocols for secure communications.

OWASP Top 10 guidelines for applying secure coding practices.

These resources and practices will be useful in future projects, especially when working on enterprise-level applications that require secure deployment.

Value to Future Employers

This project demonstrates my ability to:

Identify and remediate software vulnerabilities.

Implement modern encryption and secure communication protocols.

Validate software security using both manual and automated testing tools.
Future employers will see my capability to deliver production-quality, secure applications that protect sensitive client data.

Repository Link:
https://github.com/Froyli
