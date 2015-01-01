---
layout: post
title: Glossaries of Software Testing
category: english
description: 
tags: [softwaretesting]
---
##What is 'Software Testing'?
Testing involves operation of a system or application under controlled conditions and evaluating the results. The controlled conditions should include both normal and abnormal conditions. Testing should intentionally attempt to make things go wrong to determine if things happen when they shouldn't or things don't happen when they should. It is oriented to 'detection'. 

##Test Plan
A software project test plan is a document that describes the objectives, scope, approach, and focus of a software testing effort. The process of preparing a test plan is a useful way to think through the efforts needed to validate the acceptability of a software product. The completed document will help people outside the test group understand the 'why' and 'how' of product validation. It should be thorough enough to be useful but not so overly detailed that no one outside the test group will read it. 

##Test Case
A test case describes an input, action, or event and an expected response, to determine if a feature of a software application is working correctly. A test case may contain particulars such as test case identifier, test case name, objective, test conditions/setup, input data requirements, steps, and expected results. The level of detail may vary significantly depending on the organization and project context. 

## Test approach
###White box testing 
White box testing is when the tester has access to the internal data structures and algorithms including the code that implement these.
The following types of white box testing exist:
API testing (application programming interface) - testing of the application using public and private APIs
Code coverage - creating tests to satisfy some criteria of code coverage (e.g., the test designer can create tests to cause all statements in the program to be executed at least once)
Fault injection methods - improving the coverage of a test by introducing faults to test code paths
Mutation testing methods - Static testing - White box testing includes all static testing
###Black box testing
Black box testing treats the software as a "black box"—without any knowledge of internal implementation. Black box testing methods include: equivalence partitioning, boundary value analysis, all-pairs testing, fuzz testing, model-based testing, traceability matrix, exploratory testing and specification-based testing.
###Grey box testing 
Grey box testing involves having knowledge of internal data structures and algorithms for purposes of designing the test cases, but testing at the user, or black-box level.
##Testing levels
### Unit testing 
Unit testing refers to tests that verify the functionality of a specific section of code, usually at the function level. 
<br/>These types of tests are usually written by developers as they work on code (white-box style), to ensure that the specific function is working as expected.
### Integration testing 
Integration testing is any type of software testing that seeks to verify the interfaces between components against a software design. 
### System testing 
System testing tests a completely integrated system to verify that it meets its requirements and to any external or third party systems defined in the system requirements.
### Regression testing 
Regression testing focuses on finding defects after a major code change has occurred. Specifically, it seeks to uncover software regressions, or old bugs that have come back.
<br/>Typically, regressions occur as an unintended consequence of program changes, when the newly developed part of the software collides with the previously existing code.
<br/>Common methods of regression testing include re-running previously run tests and checking whether previously fixed faults have re-emerged. The depth of testing depends on the phase in the release process and the risk of the added features. They can either be complete, for changes added late in the release or deemed to be risky, to very shallow, consisting of positive tests on each feature, if the changes are early in the release or deemed to be of low risk.
###Acceptance testing 
Acceptance testing can mean one of two things:
<br/>A smoke test is used as an acceptance test prior to introducing a new build to the main testing process, i.e. before integration or regression.
<br/>Acceptance testing performed by the customer, often in their lab environment on their own hardware, is known as user acceptance testing (UAT). Acceptance testing may be performed as part of the hand-off process between any two phases of development.
###Alpha testing 
Alpha testing is simulated or actual operational testing by potential users/customers or an independent test team at the developers' site. 
It is often employed for off-the-shelf software as a form of internal acceptance testing, before the software goes to beta testing. 
###Beta testing 
Beta testing comes after alpha testing. Versions of the software, known as beta versions, are released to a limited audience outside of the programming team.
###Software performance testing
Performance testing is executed to determine how fast a system or sub-system performs under a particular workload. It can also serve to validate and verify other quality attributes of the system, such as scalability, reliability and resource usage.
###Stress testing
Stress testing is primarily concerned with testing that can continue to operate under a specific load, whether that be large quantities of data or a large number of users. 
###Internationalization and localization 
will verify that the application still works, even after it has been translated into a new language or adapted for a new culture (such as different currencies or time zones).
###Compatibility Testing
Compatibility Testing verifies the application still works with different remote devices.

##Appendix
![sample testing cycle](/assets/images/english/sampletestingcycle.png)
##Reference
* [Software testing on wiki](http://en.wikipedia.org/wiki/Software_testing)   
