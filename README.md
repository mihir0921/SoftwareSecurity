# SoftwareSecurity

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
A provider of financial services, Artemis Financial helps its customers with insurance and financial planning. Secure data storage and transmission for data download and upload were the issues they needed me to handle.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I believe I did a great job implementing the keystore.jks. Even though there were times when the instructions were quite vague, I was able to get the keystore to function. Later, I was even able to assist a classmate in integrating and configuring the keystore in the SSL of the final project. Because there are threats everywhere, secure coding is essential. Data theft is an ongoing problem. Some businesses occasionally even want to steal your data. There are several dangers that can be reduced by secure coding.

What part of the vulnerability assessment was challenging or helpful to you?
The hash algorithm's implementation proved to be a little difficult, in my opinion. This is due to the fact that in order for the message digest to function, the source code needed to develop a class that threw an exception. Implementing that proved to be a challenge because the examples we had did not demonstrate things in the same manner. Also, getting the SSL to function correctly required some effort.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I started by performing the dependency checks before addressing the requirement to boost security. After that, I checked the source code to make sure there were no errors. I then put TLS and encryption into place. In the actual world, I would perform the same action.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
For functionality, I ensured first that I had no code errors in Eclipse. Once I had the code error-free, I ran the service and opened up the localhost to confirm that the output was correct. I also verified that the site was accessed via https using the self-signed certificate.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Creating SSL certificates was very useful. I think I will use that going forward to test secure communications while developing websites. I also really liked the dependency check tool. I think that is very helpful to analyze risks that are out there. I will definitely use that going forward.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would like to showcase the final document and my ability to learn how to search for security threats and apply what I have learned to mitigate them. I think that skill can be built upon to make me more security conscious and more of an asset to a future employer.
