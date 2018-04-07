# Unit Testing with Spring, JUnit and Mockito

## Todo
- Intro and Conclusion
- Course Journey Overview Video
- Intermediate Overview Videos
  - Intro to Mockito Section
    - Why are we talking in depth about Mockito in a Spring Unit Testing course?
  - Intro to the Spring Unit Testing Section
    - Why are we creating controllers?
  - Approach to the Multiple Layers Part

## Learn Unit Testing with most popular frameworks - Spring Boot, JUnit and Mockito

Spring Boot is the most popular framework to develop RESTful Services. It has awesome unit testing capabilities through Spring Boot Starter Test. Mockito is the most popular mocking framework. JUnit is most popular Java Unit Testing Framework.

In this course, you will learn to build unit tests for simple RESTful Services with Spring Boot Starter Test, Mockito and JUnit. You will learn to write independent unit tests for RESTful web services talking with multiple layers - web, business and data. You will learn how to write integration tests using an in memory database H2.

You will build the unit tests step by step - in more than 50 steps. This course would be a perfect first step as an introduction to unit testing with Spring Boot and Mockito Frameworks.

You will be using Spring (Dependency Management), Spring Boot, Maven (dependencies management), Eclipse (IDE), in memory database H2 and Tomcat Embedded Web Server. We will help you set up each one of these.

You will use all the frameworks that are part of Spring Boot Starter Test - JUnit, Spring Test, Spring Boot Test, AssertJ, Hamcrest, Mockito, JSONassert and JsonPath.

You will learn to use the most important Unit Testing Annotations - @RunWith(SpringRunner.class), @SpringBootTest, @WebMvcTest, @DataJpaTest and @MockBean.

### Recommended Tools
- Java 8 or Later
- Eclipse Oxygen or Later
- Spring Boot 2.0.0.RELEASE or Later

### Installing Java 8 and Eclipse
- Installation Video : https://www.youtube.com/playlist?list=PLBBog2r6uMCSmMVTW_QmDLyASBvovyAO3
- GIT Repository For Installation : https://github.com/in28minutes/getting-started-in-5-steps
- PDF : https://github.com/in28minutes/SpringIn28Minutes/blob/master/InstallationGuide-JavaEclipseAndMaven_v2.pdf

### References
- Intellij
  - https://www.jetbrains.com/help/idea/configuring-testing-libraries.html
  - https://blog.jetbrains.com/idea/2016/08/using-junit-5-in-intellij-idea/
- Spring & Spring Boot Framework - https://www.youtube.com/watch?v=PSP1-2cN7vM&t=893s
- Introduction to JPA and Hibernate using Spring Boot Data Jpa - http://www.springboottutorial.com/introduction-to-jpa-with-spring-boot-data-jpa
- Functional Programming - https://youtu.be/aFCNPHfvqEU
- JUnit - https://junit.org/junit5/docs/current/user-guide/
- AssertJ - https://joel-costigliola.github.io/assertj/
- Mockito - https://github.com/mockito/mockito/wiki/FAQ
- JsonPath - https://github.com/json-path/JsonPath
- Setting up JUnit 5 with Mockito and Spring Boot 2.0 - https://medium.com/@dSebastien/using-junit-5-with-spring-boot-2-kotlin-and-mockito-d5aea5b0c668
- Good Unit Testing 
  - https://github.com/mockito/mockito/wiki/How-to-write-good-tests
  - FIRST. https://pragprog.com/magazines/2012-01/unit-tests-are-first
  - Patterns - http://xunitpatterns.com
- Mocking Static, Private Methods and Constructors 
  - https://github.com/in28minutes/MockitoTutorialForBeginners/blob/master/Step15.md
  - https://github.com/in28minutes/MockitoTutorialForBeginners/tree/master/src/test/java/com/in28minutes/powermock

### Mockito

Easier Static Imports
```
Window > Preferences > Java > Editor > Content Assist > Favorites
org.junit.Assert
org.mockito.BDDMockito
org.mockito.Mockito
org.assertj.core.api.Assertions
org.hamcrest.Matchers
org.hamcrest.CoreMatchers
org.hamcrest.MatcherAssert
```
### What You will learn
- You will learn to write great Unit and Integration tests using Spring Boot Starter Test
- You will learn to write unit tests using Mocks and Spys created with Mockito
- You will learn to write independent unit tests for RESTful web services talking with multiple layers - web, business and data
- You will learn to write integration tests using an in memory database - H2
- You will learn to use all the frameworks that are part of Spring Boot Starter Test - JUnit, Spring Test, Spring Boot Test, AssertJ, Hamcrest, Mockito, JSONassert and JsonPath.
- You will learn to use the most important Unit Testing Annotations - @RunWith(SpringRunner.class), @SpringBootTest, @WebMvcTest, @DataJpaTest and @MockBean.

### Requirements
- You should have working knowledge of Java and Annotations. 
- We will help you install Eclipse and get up and running with Maven and Tomcat.
- You should have basic knowledge about Spring, Spring Boot and JPA/Hibernate. We provide resources that can be used to enrich your knowledge in the course.

## Mockito

### Step By Step Details

- Step 01: Setting up the project using Spring Initializr
- Step 02: Writing Unit Test for a Simple Business Service
- Step 03: Setting up a Business Service to call a Data Service
- Step 04: Writing your first unit test with Stub
  - Exercise - Update Tests 2 & 3
- Step 05: Exercise Solution - Updating Tests 2 & 3 to use Stubs - Problem with Stubs.
- Step 06: Writing Unit Tests with Mocking using Mockito
  - Exercise - Updating Tests 2 & 3 to use Mockito
- Step 07: Exercise Solution - Updating Tests 2 & 3 to use Mockito
- Step 08: More Refactoring - @Mock, @InjectMocks and @RunWith(MockitoJUnitRunner.class)
- Step 09: Mockito Tips - Multiple Return Values and Specific Argument Matchers
- Step 10: Mockito Tips - Argument Matchers
- Step 11: Mockito Tips - Verify method calls
- Step 12: Mockito Tips - Argument Capture
- Step 13: Mockito Tips - Argument Capture on Multiple Calls
- Step 14: Introduction to Spy
- Step 15: Mockito FAQ


## Spring Boot & Mockito - Unit Testing

### Step By Step Details

- Step 01: Creating a Hello World Controller
- Step 02: Using Mock Mvc to test Hello World Controller
- Step 03: Using Response Matchers to check status and content
- Step 04: Creating a Basic REST Service in Item Controller
- Step 05: Unit Testing Item Controller and Basic JSON Assertions
- Step 06: Digging deeper into JSON Assert
- Step 07: Writing a REST Service talking to Business Layer
- Step 08: Writing Unit Test for REST Service mocking Business Layer
- Step 09: Prepare Data Layers with JPA, Hibernate and H2
- Step 10: Create Item Entity and Populate data with data.sql
- Step 11: Create a RESTful Service talking to the database
- Step 12: Writing Unit Test for Web Layer - Controller - Using Mock MVC
- Step 13: Exercise & Solution - Writing Unit Test for Business Layer - Mocking
- Step 14: Writing Unit Test for Data Layer - Data JPA Test
  - Exercise - Write Unit Test for findById method retrieving item with id 10001
- Step 15: Writing an Integration Test using @SpringBootTest
  - Exercise - Make Asserts Better
- Step 16: Tip : Using @MockBean to mock out dependencies you do not want to talk to!
- Step 17: Tip : Creating Different Test Configuration
- Step 18: Writing Unit Tests for Other Request Methods
- Step 19: Refactor SomeBusinessImpl to use Functional Programming
  - Exercise - Convert the second method to use Functional Approach
- Step 20: Better Assertions with Hamcrest - HamcrestMatcherTest
- Step 21: Better Assertions with AssertJ - AssertJTest
- Step 22: Better Assertions with JSONPath - JSONPathTest
- Step 23: Easier Static Imports
- Step 24: Tip : Measuring Test Coverage with Eclipse
- Step 25: Tip : Keep an eye on performance of unit tests!
- Step 26: Good Unit Tests


- Step 25: Tip : Keep an eye on performance of unit tests!
- Step 16: Tip : Using @MockBean to mock out dependencies you do not want to talk to!
- Step 17: Tip : Creating Different Test Configuration
- Step 18: Writing Unit Tests for Other Request Methods
- Step 19: Refactor SomeBusinessImpl to use Functional Programming
- Step 24: Tip : Measuring Test Coverage with Eclipse
- Step 20: Better Assertions with Hamcrest - HamcrestMatcherTest
- Step 21: Better Assertions with AssertJ - AssertJTest
- Step 22: Better Assertions with JSONPath - JSONPathTest
- Step 23: Tip Patterns - http://xunitpatterns.com REUSE
- Step 26: Good Unit Tests



### Course Recording Notes

 #### Preview Video
- Welcome to course on *** in ** simple steps.
- I'm Ranga Karanam. I've so and so much experience with ... I've been using this framework for ...
- At in28minutes, we ask one question everyday - How to create more effective courses? All our success - *** students on Udemy and *** subscribers on Youtube - is a result of this pursuit of excellence.
- You will develop *** and *** using ***
- You will  learn the basics like *** and move on to the advanced concepts like ***.
- You will use 
  - ... todo ...
  - Maven for dependency management, building and running the application in tomcat.
  - Eclipse IDE
- All the code for this course and the step by step details are in our Github repository. 
- We have an awesome installation guide to help you install Maven and Eclipse. You are NOT expected to have any experience with Eclipse, Maven, or Tomcat.
- What are we waiting for? Lets have some fun with *** in *** steps. We had a lot of fun creating this course for you and We are confident that you will have a lot of fun. I hope you are as excited as we are to learn more. Go ahead and enroll for the course. Or take a test drive with a free preview. See you in the course.

#### Conclusion Video
- Congratulations! You have successfully completed the course on ... We covered a wide range of topics starting from Spring, Spring Boot to ..... I'm sure you had a lot of fun doing this course. If you loved this course, we would love to hear from you. Do not forget to leave us a review. Until we see you in another in28minutes course, here's bye from the team here at in28minutes.
- To find out more about *** use these References  

## Templates

### Welcome Message
```

## ADD A FEW SAMPLE REVIEWS AFter a couple of months
## ADD A FEW SAMPLE REVIEWS - in the description of the course 

Congratulations on joining this course from in28Minutes. 

We have 6800+ 5 Star reviews on our courses.  

I hope that by the time you are prompted to leave a review, that you think this course is an amazing course and can write a few sentences about what you like about the course for future students to see. If you do not think this course is a 5-star course, we want to make it a better course for you! Please message me with ways that I can make it the best course for you.

There are three things you need to understand before you start this course!

1...... Listen + See + Do Hands-on + Repeat = 90% Retention
For the first 2 hours, we repeat a few concepts to help you retain them. .

2...... Set Yourself a Goal
Set 1 hour aside every day for the next week for this course! No exceptions allowed :) 

3...... Udemy asks you for a review very early in the course! If you are not ready for giving a review, you can skip giving a review.

Thank you and enjoy the course,
Ranga
```

### Thank You for completing the course message

```
Congratulations on completing the course from in28Minutes.

We have 6800+ 5 Star reviews on our courses. We hope you think this course is an amazing course and can write a few sentences about what you like about the course for future students to see.

We are on a constant journey to improve our courses further. Do message me if you have any suggestions.

Good Luck for your future.

Ranga from in28Minutes
```

### Bonus Lectures

```
Our Best Selling Courses
Get unbelievable offers on all our best-selling courses!
http://eepurl.com/bOJulL

```
  
### Useful Links
- [Subscribe and get Amazing Offers](http://eepurl.com/bOJulL)
- [Our Website](http://www.in28minutes.com)
- [Facebook](http://facebook.com/in28minutes)
- [Twitter](http://twitter.com/in28minutes)
- [Google Plus](https://plus.google.com/u/3/110861829188024231119)
