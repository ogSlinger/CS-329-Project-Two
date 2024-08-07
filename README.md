# CS-329-Project-Two

-How can I ensure that my code, program, or software is functional and secure?

  The way I can ensure my code is functional is by testing processes I learned in this class. When it came to initial testing, I would use unit testing, and test the individual components of a system. After all tests are clear from that point, I could use methods such as integration testing and system testing. This tests the components functionality between each other, and then the system as a whole. Business requirements are tested against in these three processes. If errors are found, and after fixes have been implemented, regression testing may be performed. To ensure that the code is secure is by static testing of the dependencies. Using static testing tools, such as OWASP, helps identify dependency related vulnerabilities.
  
-How do I interpret user needs and incorporate them into a program? 

  The way I can interpret user needs is by first testing against the business requirements. However, utilizing a bit of empathy helps in this process as well. Identifying outlier behaviour that may impede on the user's needs requires this. This is why 100% code coverage is a good goal to achieve when testing the behaviour of the software. This is especially true when incorporating other libraries into your codebase and certain behaviours may come up from such things.
  
-How do I approach designing software?

  When approaching designing software, I first take what the system as a whole needs to accomplish, what is the user input, and the system's output. Then, I decompose the system to smaller, modular components. These components are designed to work together to accomplish what the system is designed to do. Then, I try to identify dependencies that may be needed for the system to work. After this process, using static testing for depenency vulnerabilities are performed. This process is done regressively in every test cycle, as vulnerabilities are found daily on a global scale. Once the components are written, they are sent to unit testing. If the code is covered 100% with the tests, and there are no found errors or bugs, then it moves to integration and systems testing. Once clear, acceptance testing may be performed to ensure the user is satisfied with the product. Any additional adjustments could be made, and the necessary testing processes are utilized, then the product is complete.
