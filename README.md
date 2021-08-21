# Software-Security

# Briefly Summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company. They develop individualized financial plans for savings, retirement, investments, and insurance. They currently have a RESTful web application programming interface and want to protect their organization from external threats. 

# What did you do particularly well in identifying their software vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?
In order to identify Artemis Financial's software security vulnerabilities, I first thought about what kind of information they hold which can be valuable and susceptible to threats. Since this is a financial company that develops financial plans for it's customers, they would have data that includes their customers' personal information which could include social security numbers, bank account numbers, date of birth, and much more. If hackers obtain this information, they could steal the user's identity, take out loans or credit cards in their name, and cause a lot of financial hardship. A security breach can also cost the complnay in terms of money and it can cause them to lose customers. I also wanted to see if there are regulations required for financial company's software security and found government regulations to implement into the security of their application. 

# What about the process of working through the vulnerability assessment did you find challenging or helpful?
I initially found the number of vulnerabilities overwhelming. However, I did find it helpful that each vulnerability explains why it may be considered a vulnerability which made finding solutions much easier. 

# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I used a dependency check to see vulnerabilities in the application. This showed me what could be a vulnerability in the application and helped me to find solutions to make it more secure. I also researched algorithm ciphers to use in securing the application. 

# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I removed business names from parameters so that it will not be easily visible to hackers. I also switched to HTTPs for all communications in the system. Using a cipher algorithm would also need to be implemented. After making changes, running another dependency check would be beneficial to ensure that there are no new vulnerabilities introduced. 

# What resources, tools, or coding practices did you employ? 
I used a maven dependency check which helped to identify vulnerabilities. I also found government resources regarding security which would be helpful to reference in future assignments. Use of algorithm ciphers are also very important and should be used in future assignments to increase layers of security and reduce risk of external threats. 

# What from this particular assignment would you want to showcase to a future employer?
I think that I did a very good job with researching security requirements that would apply to this kind of company. In previous courses, I based my decisions on only the information that I was provided with for the assignment, however in this course, I spent more time researching to find all of the requirements. This is important because when working on an assignment for a real client, there are more requirments that need to be implemented than just what the client tells you. This could include government requirements or requirements set by insurance companies on the type of application you may be creating and it is crutial to know these requirements. 
