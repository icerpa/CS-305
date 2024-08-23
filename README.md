# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting firm that develops individualized financial plans for its customers, including saving, retirement, investments, and insurance. The company wanted to modernize its operations and ensure they were using the most current and effective software security measures. They sought our help to protect their client data and financial information. Specifically, they wanted to add a file verification step to their web application to ensure secure communications, which involved implementing a checksum mechanism.

# What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

When identifying the client’s software security vulnerabilities, I effectively updated dependencies to the latest secure versions, replaced hardcoded passwords with environment variables, and improved exception handling. Coding securely is crucial because it protects sensitive information, prevents unauthorized access, and ensures data integrity. Software security adds immense value to a company’s overall well-being by safeguarding its reputation, fostering client trust, and ensuring compliance with regulatory requirements. For a financial consulting firm like Artemis Financial, protecting client data is paramount to maintaining their credibility and success.

# Which part of the vulnerability assesment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was identifying and updating the dependencies to the latest secure versions while ensuring compatibility with the existing codebase. This step was also the most helpful as it provided a comprehensive understanding of the potential risks associated with outdated libraries and the importance of keeping dependencies up-to-date.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by replacing hardcoded passwords with environment variables, implementing proper exception handling, and ensuring that all dependencies were updated to the latest secure versions. In the future, I would use tools like OWASP Dependency-Check, static code analysis tools, and regular security audits to assess vulnerabilities. I would also stay informed about the latest security best practices and apply them to decide which mitigation techniques to use.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure the code and software application were functional and secure, I conducted thorough testing, including unit tests and integration tests. After refactoring the code, I used tools like OWASP Dependency-Check and static code analysis to identify any new vulnerabilities. I also compared the Dependency Check I took before refactoring the code to the Dependency Check after refactoring to check that no new vulnerabilites were flagged. Finally, I then reviewed the code again to ensure that the changes did not introduce any security flaws and maintained the application’s functionality.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

In this project, I used resources like the OWASP Dependency-Check plugin, the dotenv library for managing environment variables, and logging frameworks like SLF4J for improved exception handling. These tools and practices are valuable for future assignments as they help maintain code quality, enhance security, and ensure better manageability of sensitive information.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employeers from this assignment?

From this assignment, I would show future employers the implementation of the checksum mechanism, the use of environment variables to manage sensitive information securely, and the improved exception handling. These examples demonstrate my ability to apply industry-standard best practices for secure coding, my attention to detail in identifying and mitigating security vulnerabilities, and my commitment to maintaining high code quality and security standards.
