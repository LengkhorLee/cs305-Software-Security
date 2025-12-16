# cs305-Software-Security
1) Client summary and software requirements

Artemis Financial is a financial services company that needed help improving the security of a Java-based web application used to handle sensitive customer and transaction data. The main issue was reducing security risk by identifying vulnerabilities (including dependency/library risks) and strengthening protections such as secure communications and secure coding practices.

2) What I did well / why secure coding matters / value to the business

I did well in systematically reviewing the application for security weaknesses and using tooling to identify known vulnerabilities in third-party dependencies. Secure coding is important because financial systems handle highly sensitive information, and weaknesses can lead to data breaches, fraud, downtime, and loss of customer trust. Strong software security improves confidentiality, integrity, and availability, which directly supports a company’s reputation, compliance needs, and long-term stability.

3) What was challenging in the vulnerability assessment

The most challenging part was interpreting scan results and prioritizing what mattered most. Not every finding is equally severe or even applicable, so it took careful judgment to separate true risks from low-impact items and to choose fixes that improved security without breaking functionality.

4) How I increased security layers / what I’d use in the future

I increased security by applying defense-in-depth concepts: reducing dependency risk, improving secure configuration, and strengthening communication security (such as using TLS/HTTPS and appropriate certificates when applicable). In the future, I would continue using dependency scanning (OWASP Dependency-Check), static analysis tools, secure code review checklists, and risk-based prioritization (severity, exploitability, and business impact) to decide which mitigation techniques to apply first.

5) How I ensured functionality and security after refactoring

After refactoring, I verified the application still worked by building and running it successfully, re-checking the main workflows, and confirming expected outputs. To ensure I did not introduce new vulnerabilities, I re-ran vulnerability scans and reviewed the changes for common security issues (input handling, secure configuration, and dependency updates), validating that improvements reduced findings without creating new risks.

6) Tools, resources, and practices I used

Resources and tools included OWASP Dependency-Check (and related reports), Java/Spring build tools (Maven), and secure coding best practices such as using updated dependencies, limiting exposure of sensitive data, and applying secure communication standards. I also relied on documentation, vulnerability databases, and structured security review methods to guide decisions.

7) What I would show an employer from this assignment

I would show my completed vulnerability assessment/practices report and the repository evidence that I can identify vulnerabilities, interpret scan results, prioritize fixes, and implement secure improvements in a real codebase. This project demonstrates practical secure development skills, tool usage, and the ability to communicate security findings clearly.
