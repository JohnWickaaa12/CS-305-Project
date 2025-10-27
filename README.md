# Artemis Financial – Secure Software Practices (Project Two)

**Course:** CS-305 Secure Software Development  
**Student:** Reice Morgan  
**Repository:** https://github.com/JohnWickaaa12/CS-305-Project  
**Artifact:** Practices for Secure Software Report (Project Two)

---

## Reflection

Artemis Financial is a company that provides financial services and works with sensitive client information, which means confidentiality and integrity of data are extremely important to their business. They needed a secure way for their application 
to transmit information so that attackers could not intercept or alter it. The main issue they wanted me to address was strengthening the security of their web application by introducing encryption, secure communication practices, and protections against 
common software vulnerabilities.

When I analyzed the application, I was able to identify where the security weaknesses were and apply improvements that made a meaningful difference. I feel I did well in bridging the gap between identifying vulnerabilities and fixing them in a clean and 
maintainable way. Instead of just listing security problems, I implemented HTTPS with an SSL certificate and used SHA-256 hashing to verify the integrity of transmitted data. It is important to code securely because even a small oversight can become a major 
vulnerability that hackers can exploit. Secure coding protects users, keeps systems reliable, and helps maintain customer trust — which is extremely valuable to a company’s reputation and long-term stability.

One of the more challenging but helpful parts of the assessment was working with the dependency scan results. The OWASP Dependency-Check tool reports a lot of information, and it can be difficult to judge which vulnerabilities are actually impactful. Going through
that process helped me better understand how third-party libraries affect an application’s security, and it reinforced the idea that secure development is not just about your own code — it also includes everything the code depends on.

I increased the layers of security by encrypting traffic using TLS (HTTPS), adding hashing for message integrity, and performing a code review to reduce exposure to potential risks. These layers ensure that even if one safeguard is bypassed, another is still in place. 
In the future, I would build on this approach by using continuous vulnerability scanning, automated pipeline checks, and NIST/OWASP guidelines to evaluate which risks need immediate mitigation and which can be monitored over time.

After refactoring the code, I made sure the application was still functional and secure by retesting the endpoints and verifying that the HTTPS connection worked correctly. I also repeated the dependency scan to make sure no new vulnerabilities were introduced 
during the changes. Functional testing after security updates is important because sometimes fixing one issue can unintentionally create another, so re-verification is necessary.

Throughout this project, I used tools and practices that I can easily reuse in future work, including Java Keytool for certificate generation, OWASP Dependency-Check for vulnerability scanning, and secure configuration via Spring Boot. These tools are common in 
modern secure development workflows, especially in DevSecOps environments, and gaining hands-on experience with them is valuable.

This artifact is a strong example of work I could show an employer because it demonstrates not only knowledge of cybersecurity concepts but also the ability to apply them in an actual codebase. It shows practical experience with encryption, secure configuration, 
vulnerability assessment, and safe programming habits — which are all essential skills in backend development and security-focused software engineering roles.

---

## Artifact Location

The full Secure Software Practices Report with screenshots and testing evidence is located in the `/docs/` folder of this repository.

---
