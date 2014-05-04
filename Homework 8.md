##How to ensure the quality of a software system
I will  take the diandian as the target system to explain how to ensure the quality of a software system.
###Code-based analysis
The measurement of critical application characteristics involves measuring structural attributes of the application's architecture, coding, and in-line documentation, as displayed in the picture above. Thus, each characteristic is affected by attributes at numerous levels of abstraction in the application and all of which must be included calculating the characteristic’s measure if it is to be a valuable predictor of quality outcomes that affect the business. The layered approach to calculating characteristic measures displayed in the figure above was first proposed by Boehm and his colleagues at TRW (Boehm, 1978)[27] and is the approach taken in the ISO 9126 and 25000 series standards. These attributes can be measured from the parsed results of a static analysis of the application source code. Even dynamic characteristics of applications such as reliability and performance efficiency have their causal roots in the static structure of the application.
###Reliability
The root causes of poor reliability are found in a combination of non-compliance with good architectural and coding practices. This non-compliance can be detected by measuring the static quality attributes of an application. Assessing the static attributes underlying an application’s reliability provides an estimate of the level of business risk and the likelihood of potential application failures and defects the application will experience when placed in operation.
###Efficiency
As with Reliability, the causes of performance inefficiency are often found in violations of good architectural and coding practice which can be detected by measuring the static quality attributes of an application. These static attributes predict potential operational performance bottlenecks and future scalability problems, especially for applications requiring high execution speed for handling complex algorithms or huge volumes of data.
###Security
Assessing security requires at least checking the following software engineering best practices and technical attributes:
- Application Architecture Practices
- Multi-layer design compliance
- Security best practices (Input Validation, SQL Injection, Cross-Site Scripting, etc.[29] )
- Programming Practices (code level)
- Error & Exception handling
- Security best practices (system functions access, access control to programs)

###Maintainability
Maintainability includes concepts of modularity, understandability, changeability, testability, reusability, and transferability from one development team to another. These do not take the form of critical issues at the code level. Rather, poor maintainability is typically the result of thousands of minor violations with best practices in documentation, complexity avoidance strategy, and basic programming practices that make the difference between clean and easy-to-read code vs. unorganized and difficult-to-read code.
###Identifying critical programming errors
Critical Programming Errors are specific architectural and/or coding bad practices that result in the highest, immediate or long term, business disruption risk.
These are quite often technology-related and depend heavily on the context, business objectives and risks. Some may consider respect for naming conventions while others – those preparing the ground for a knowledge transfer for example – will consider it as absolutely critical.Critical Programming Errors can also be classified per CISQ Characteristics.
