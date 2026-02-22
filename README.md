# SoftwareSecurity
# Briefly summarize your client, Artemis Financial, and its software requiresments. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial services firm that focuses on managing client portfolios and offering tailored investment planning. Due to the sensitive nature of the financial and personal information they manage, it was essential for them to enhance the security of their current software systems. Their main priority was to ensure that the data exchanged through their web-based application was safeguarded against interception, tampering, and unauthorized access.

The company requested that I assess their existing code base, pinpoint potential vulnerabilities, and refactor the application to incorporate secure communication, encrypted data handling, and enhanced protection against prevalent software security threats.

# What did you do well when you found your client's software secuiry vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?
One aspect in which I excelled was the systematic approach to identifying vulnerabilities. I employed the vulnerability assessment process to pinpoint weaknesses within the application, including unencrypted communication and insufficient data integrity checks. Additionally, I assessed the dependencies to confirm that any outdated or vulnerable libraries were recognized.

The importance of secure coding cannot be overstated, as it safeguards against attackers who may exploit vulnerabilities that threaten sensitive data. For a financial institution such as Artemis Financial, robust software security is vital for maintaining client trust, minimizing legal and financial risks, and ensuring adherence to industry regulations. Furthermore, secure software plays a crucial role in the long-term stability of the company by averting expensive breaches and preserving the integrity of their services.

# Which part of the vulnerability assessment was challenging or helpful to you?
The most difficult aspect of the vulnerability assessment involved interpreting the outcomes of the static testing tools and comprehending how each vulnerability connected to the architecture of the application. Certain findings necessitated further investigation to grasp their severity and potential exploitation.

The most beneficial element was the structured process itself. The assessment diagram offered a clear guide for pinpointing issues, prioritizing them, and deciding on suitable mitigation strategies. It facilitated the division of a complex task into manageable steps.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I enhanced security measures by employing cryptographic hashing to safeguard data integrity and by setting up HTTPS to secure communication between the client and server. Additionally, I implemented secure certificate management to verify the server's authenticity.

Looking ahead, I plan to persist in utilizing tools such as OWASP Dependency-Check, static code analyzers, and vulnerability scanners to evaluate risks. Furthermore, I will depend on established frameworks like the OWASP Top Ten and NIST guidelines to identify the most effective mitigation strategies for various types of vulnerabilities.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduces new vulnerabilities?
To guarantee the application was both functional and secure, I examined the refactored code for any syntax errors, configuration problems, and compliance with secure coding standards. Additionally, I made an effort to execute the application to confirm that the newly added features, including hashing and HTTPS, were correctly implemented.

Following the refactoring process, I utilized the OWASP Dependency-Check tool once more to ensure that no new vulnerabilities had been introduced. Despite the application facing technical difficulties during execution, the static analysis procedure enabled me to ascertain that the modifications I implemented did not adversely affect the project's security posture.

# What resources, tools, or coding practices did you use that ight be helpful in future assignments or tasks?
A variety of tools and methodologies from this project will prove beneficial for future endeavors:

OWASP Dependency-Check for detecting vulnerable libraries

Spring Boot documentation for secure configuration and controller design

Java Keytool for generating certificates and configuring SSL

SHA-256 hashing for ensuring data integrity

HTTPS/TLS configuration for facilitating secure communication

Secure coding principles including least privilege, encryption, and dependency management

These tools and methodologies establish a robust foundation for developing secure applications in practical environments.

# What might you show future employers from this assignment?
Through this assignment, I was able to demonstrate to potential employers:

My capability to analyze and evaluate software vulnerabilities

My comprehension of secure coding methodologies

My experience with encryption, hashing, and HTTPS

My proficiency in utilizing industry tools such as OWASP Dependency-Check

My documentation abilities, which include crafting clear reports and articulating technical decisions

Although the application did not operate completely, the project illustrates my understanding of secure software development and my capacity to adhere to a systematic security workflow — both of which are advantageous to employers.
