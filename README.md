# Software-Security
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
-Artemis Financial is a consulting company that creates individualized financial plans for their customers, there main goal is to modernize their operations, which includes creating their own custom software. However they also need this software to be very secure to protect the sensitive information of their institution as well as their customers. This includes creating a channel for secure communications as well as data verification.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
-One of the things I think I did well on was visually going over the code and realizing where things like input validation were missing, as well as where code quality or error was. Utilizing the vulnerability assessment process flow diagram was very helpful to assess the code and make sure it was secure. Its important to code securly because what you are coding could be a product used by the public, and having that code be vulnerable could be detrimental to a business or an individual. The value that software security adds to a company is feeling protected, we see all the time that companies experience data leaks, and usually a negative imaage is formed for some of those companies, but having that secure software to prevent all of that from happening is what should be aimed for. Keeping the data that belongs to customers private is very important to keeping customer satisfaction and having a good image for a business or organization.

What part of the vulnerability assessment was challenging or helpful to you?
-The part of the vulnerability assessment that was challenging to me was the "secure API interactions" before I hadnt quite understood how API's worked entirely, I knew what they were, but not the inner workings of them, so grasping that and being able to realize when it wasnt up to par was challenging.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
-Layers of security that were added include a SSL certificate and using https protocol. Another layer of security was running dependency checks, however in the future I will need to use different mitigation techniques because identifying false positives in the dependecy check was not my strong suit, rooting out false positives and finding the real vulnerabilities will be improved upon in the future.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
-One way I checked and made sure new vulnerabilities were not introduced is by running a dependency check prior to altering the code base, and the after I had refactored the code, I ran one again and compared results. When making sure it was functioning properly I ran the project multiple times, messing with various lines, or properties to make sure it was up to the standards.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
-The vulnerability assessment process flow diagram is a resource that I will probably use for many future tasks, that is because it lays out a good foundation of what to look for while trying to create secure software. In this class, this was also my first time utilizing the dependency check report, which is something I will also be using for many future tasks that it may be beneficial for.


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
-I feel like theres a few things that could be taken away, one is static testing, such as being able to internalize the dependency checks, as well as utilizing ciphers such as SHA-256. Certificate generation is also something that may be a good take away from this project.
