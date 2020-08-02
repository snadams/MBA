# Week 9

## [SSDLC 101: What is the secure software development life cycle?](https://dzone.com/articles/ssdlc-101-what-is-the-secure-software-development)

**Software Development Life Cycle (SDLC)**: a framework that defines the process used by organizations to build an application from its inception to its decommission

* Requirements and Analysis
* Design
* Development
* Testing/QA
* Deployment
* Rinse and repeat! It is a continuous cycle.

It was common that security-related activities were only done as a part of testing but this would result in high number of issues being discovered too late (or not at all). Secure SDLC has the following advantages:

* More secure software as security is a *continuous* concern.
* Awareness of security considerations by stakeholders.
* Early detection of flaws in the system.
* Cost reduction as a result of early detection and resolution of issues.
* Overall reduction of intrinsic business risks for the organization.

Secure SDLC is usually done by adding secure-related activities to an existing development process.

Some models include:

* *MS Security Development Lifecycle (MS SDL)*. One of the first models, proposed by Microsoft.
* *NIST 800-64*. Provides security considerations within the SDLC.
* *OWASP CLASP (Comprehensive, Lightweight Application Security Process)*. Simple to implement and based on MS SDL. Maps the security activities to roles in an organization.

## [A step-by-step guide to secure software development](https://www.scnsoft.com/blog/secure-software-development-guide)

A golden rule is that *the earlier software providers integrate security aspect in an SDLC, the less money will be spent on fixing security vulnerabilities later on*.

### Requirements Analysis Stage

The two ways to incorporate security controls into this stage are:

* Employ a combination of use and misuse cases.
  * Attempt to foresee possible threats to the software and express them in misuse cases. They should then be covered by mitigation actions described in use cases.
  * Examples:
    * *Misuse case*: An unauthorized user attempts to gain access to a customer's application.
    * *Corresponding use case*: All such attempts should be logged and analyzed by a SIEM system.
* Conduct security risk assessment and create a risk profile.
  * Use authoritative sources like HIPAA and SOX.
  * Find additional requirements specific to your business domain.
  * **application risk profile**: contains application surfaces that are sensitive to malicious attacks and security risks categorized by the security level

### Design Stage

Secure design stage involves six security principles to follow:

* *Least privilege*. Minimal user privileges for normal functioning.
* *Privilege separation*. Specific actions in software should be allowed to a limited number of users with higher privileges.
* *Complete mediation*. Every user access to the software should be checked for authority. Decreases the chances of privilege escalation for a user with limited rights.
* *Multiple security layers*. Eliminate the threat of single point of security failure that will compromise the entire software (i.e. defense-in-depth).
* *Secure failure*. In case your software ceases to operate, it should fail to a secure state.
* *User-friendly security*. Should incorporate security aspects in a way that hinder UX. Users are likely to turn off if they are too obtrusive.

### Development Stage

Their main goal is to defend software against high-risk vulnerabilities.

* Open Web Application Security Project (OWASP) provides a comprehensive checklist for secure coding practices.

### Code Review

This is the stage that adds an additional layer of defense.

* Ensure software security before it enters the production stage, where fixing vulnerabilities will cost a bundle.
* OWASP has a guide to review code for certain vulnerabilities, and get guidance on how to structure and execute the effort.

### Testing Stage (Penetration Testing)

Typically, the testing stage is focused on finding errors that don't allow the application to work according to the customer's requirement. It's also a prime time to check whether the application can handle security attacks through pen testing.

* Should be performed **in every build**.
* To drive down cost, do it through automated penetration testing that fish out the most critical vulnerabilities.
* Exploratory pen testing should be performed in every stage when the application enters the release stage, where engineers check the system for potential security defects, relying on experience and intuition.
  * Helps to be trained on software attack methods and have understanding of how the software is being developed.

### Production and Post-Production Stages

SSDLC does not stop once an application is installed on the production system. Microsoft has a set of practice to stick to after the product has gone to production.

* Create an incidence response plan to address new threats.
* Conduct ultimate security review.
  * May uncover vulnerabilities missed during the previous checks.
* Certify and archive the final product.
* Be prepared to execute incidence response plan.

## [Security testing in the SDLC: A beginner’s guide](https://www.checkmarx.com/2016/02/26/security-testing-sdlc-beginners-guide/)

**security testing**: a process intended to reveal flaws in the security mechanisms of an information system that protect data and maintain functionality as needed

* Makes sure all security requirements that were mapped at the beginning stages of SDLC are being implemented and implemented correctly
* It ends up being a barometer of security quality within your SDLC.
* Best way to develop and maintain applications efficiently and in line with organizational needs and risks

### Four Key Steps to Security Testing in SDLC

1. Make it measurable.
   * You can't control what you can't measure.
   * Being able to look through testing history and compare it over time is essential in qualifying improvement.
2. Ensure testing tools are easy to adopt.
   * If a tool is difficult to use or not well-integrated into developer's current tool, it will be hard to get developers to adopt.
3. Automate wherever possible.
   * Get developers to focus on coding securely and try to automate security testing to make it consistent.
4. Align security testing activities to your current SDLC process.

## [Static testing vs. dynamic testing](https://www.veracode.com/blog/2013/12/static-testing-vs-dynamic-testing)

**static application security testing (SAST)**: testing process that looks at the application from the inside out without executing the program, but examining the source code, byte code or application binaries for signs of security vulnerabilities

* More thorough approach and more cost efficient with ability to detect bugs at an early phase of the SDLC

**dynamic application security testing (DAST)**: testing process that looks at the application from the outside in by examining it in its running state and trying to manipulate it in order to discover security vulnerabilities

* Simulates attacks against an application and analyzes the application's reactions
* More capable of exposing a subtle flaw or vulnerability to complicated for static analysis alone to reveal

Both are necessary. The existence of one does not solve everything.
