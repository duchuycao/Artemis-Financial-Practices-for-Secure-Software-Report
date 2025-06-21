## CS 305 Reflection: Secure Software Practices – Artemis Financial

**Who was the client?**  
Artemis Financial is a company seeking to improve its software security. They requested help to identify and mitigate vulnerabilities in their financial software systems to better protect client data and maintain secure communication protocols.

**What did you do well and why is it important?**  
I performed secure coding practices by identifying vulnerabilities and mitigating them using SSL, checksum verification, and certificate-based communication. Coding securely prevents data breaches and increases client trust, which is essential to any business handling financial data.

**Challenges or helpful parts?**  
The vulnerability assessment was the most challenging because it required analyzing code for hidden risks. However, using tools like OWASP Dependency-Check was helpful in detecting outdated or risky libraries.

**How did you increase layers of security?**  
I added encryption for data in transit using SSL/TLS, generated certificates, and implemented checksum validation. In the future, I would use automated security scanning tools and threat modeling to better prioritize mitigation strategies.

**How did you ensure functionality and security after refactoring?**  
After refactoring, I tested the application thoroughly and verified that it still passed all functional tests. I also reran vulnerability scans to ensure that no new risks were introduced.

**Helpful tools and practices?**  
OWASP Dependency-Check, Java SSL certificate generation, checksum hashing, and Maven dependency management were especially useful. These tools will be reused in future secure software development tasks.

**What might you show future employers?**  
I would showcase this report and the secure code implementation as proof of my ability to apply security principles in real-world projects. It demonstrates both technical skill and practical understanding of secure development.
