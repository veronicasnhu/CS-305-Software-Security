# CS-305-Software-Security
	Throughout this project, Artemis Financial was used as the client case study. Artemis Financial is a financial consulting company that needed help improving the security of its software application. The main goal was to protect sensitive information during transmission. To do this, I added HTTPS, created a self-signed certificate, and used SHA-256 checksum verification.

	I think I did well reviewing the application for security concerns and using OWASP Dependency-Check. Secure coding is important because weak software can put customer data, company systems, and business operations at risk. Strong software security helps lower that risk and protect customer trust.

	One helpful part of the vulnerability assessment was learning that third-party dependencies can have known vulnerabilities even when the application still works. I added layers of security by switching from HTTP to HTTPS, adding a certificate, and using checksum verification. In the future, I would use Dependency-Check, manual code review, and vulnerability reports to decide which risks need to be fixed.
	
	To make sure the application was functional and secure, I tested it in the browser, confirmed that the hash page loaded through HTTPS on port 8443, and ran it in Eclipse to make sure it started without errors. I also ran OWASP Dependency-Check after refactoring to check for known vulnerabilities.

	Some tools and practices I used were Maven, Java Keytool, Spring Boot configuration, checksum verification, and secure coding review. These will be helpful in future assignments because they gave me a better process for testing and documenting security changes. This assignment also gave me work I could show future employers as an example of secure coding, testing, and documentation.
