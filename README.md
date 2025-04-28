Client Overview and Requirements:
Artemis Financial is a financial consulting company that develops individualized financial plans for their clients. They requested modernization of their operations with a focus on implementing the most current and effective software security practices. Specifically, they needed a file verification step (checksum) added to their web application to ensure secure data transmission, as they handle sensitive financial information through a public web interface.
Security Implementation Achievements:
The implementation of SHA-256 checksum verification and HTTPS/SSL security was particularly successful. The importance of secure coding cannot be overstated, especially for financial institutions. Software security adds multiple layers of value to Artemis Financial:
Protection of sensitive client data
Compliance with financial regulations
Enhanced client trust
Reduced risk of costly security breaches
Competitive advantage in the financial sector
Vulnerability Assessment Experience:
The most challenging aspect was managing the numerous dependencies and their associated vulnerabilities. The OWASP Dependency Check tool was particularly helpful in identifying potential security issues. The process of creating and maintaining the suppression.xml file provided valuable insights into vulnerability management and mitigation strategies.
Security Layer Implementation:
Security was enhanced through multiple layers:
Transport Layer Security (TLS 1.2/1.3)
SHA-256 cryptographic hashing
Certificate-based authentication
Secure port configuration (8443)
Input validation and proper error handling
For future vulnerability assessments, I would use:
OWASP Dependency Check
Static code analysis tools
Regular security audits
Automated testing frameworks
Industry security bulletins and updates
Code Security Verification:
The application's security and functionality were verified through:
Running dependency checks
Testing HTTPS implementation
Verifying checksum functionality
Ensuring proper certificate handling
Checking for secure configuration
After refactoring, new vulnerabilities were checked using:
Maven dependency checks
Manual code review
Security configuration validation
Testing with different data inputs
Valuable Resources and Tools:
Spring Boot framework
Maven dependency management
OWASP security guidelines
Java security packages
SSL/TLS protocols
Git version control
Dependency check tools
Portfolio Highlights:
For future employers, this project demonstrates:
Implementation of industry-standard security protocols
Understanding of cryptographic concepts
Ability to handle sensitive financial data securely
Experience with modern security tools and practices
Knowledge of secure coding principles
Problem-solving skills in addressing security vulnerabilities
Documentation and reporting capabilities
Understanding of financial sector security requirements
The project showcases practical experience in implementing real-world security solutions for financial applications, making it a valuable addition to a professional portfolio. It demonstrates both technical proficiency and understanding of business security needs in the financial sector.
