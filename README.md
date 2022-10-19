# CS-305

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for their customers.  This aids their clients with matters regarding retirement, savings, investments, and insurance.  

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Security is always the top priority when coding, but it was even more evident in this project.  This is becaus Artemis Financial's data will include very sensitive information about their customers, including banking passwords, SSNs, and more.  Not only could a breach ruin the integrity of Artemis Financial, it could ruin the lives of their customers.  

# What part of the vulnerability assessment was challenging or helpful to you?
Manually reviewing the code can be tedious and tiresome, but it can often save us from making obvious mistakes.  For example, by manually reviewing the code, I noticed that the request parameters weren't validated in the pom.xml file.  Noticing and fixing this error made proper input validation possible.  

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To increase the layers of security of an application, one should focus on the input validation, the API, and the cryptography.  Proper input validation will ensure that users can't give your application malicious input.  Proper use of an API will ensure that transactions are safe and secure.  Proper cryptography ensures that data remains secure, whether it be at rest or in transport.  When assessing vulnerabilities to decide which mitigation technique to use, it is best to focus on the dynamics of the data, such as how often it will need to be transported, how much of it is inputted by the user, etc.  

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
A dependency check allowed me to ensure that the application didn't depend on outdated software.  Though this doesn't cover all possible vulnerabilities, it does provide greater assurance that the application isn't open to attack.  

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Maven's Dependency Check proved to be invalubale, as it instantly provided me with a list of all possible dependencies.  It showed me why the dependencies were occurring, what they were doing to the application, and how to fix them.  

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I would show employers my attention to detail in the Manual Review section, and my thought process behind my choices for the most important areas of security.  
