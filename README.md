# Mockito.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)
* [What is Mockito?](#what-is-mockito)
* [Types of Mocks.](#types-of-mocks-aka-test-doubles)
* [Mockito Annotations.]()
* [Mocks. A fake implementation of a class used for testing.](#mocks-a-fake-implementation-of-a-class-used-for-testing)
* [Spy - Like a mock, but real object is used.](#spy---like-a-mock-but-real-object-is-used)
* [Important Terminology.](#important-terminology)
* [Help.](#help)





## About.





## Documentation.





## General.





## What is Mockito?
* Mockito is the most popular mocking framework for testing Java.
* Mocks (aka Test Doubles) are alternate implementations of objects to replace real objects in tests.
* Works well with Dependency Injection.
* For the class under test, injected dependencies can be mocks.





## Types of Mocks (aka Test Doubles)
* Dummy - Object used just to get the code to compile.
* Fake - An object that has an implementation, but not production ready.
* Stub - An object with pre-defined answers to method calls.
* Mock - An object with pre-defined answers to method calls, and has expectations of executions.
  Can throw an exception if an unexpected invocation is detected.
* Spy - In Mockito Spies are Mock like wrappers around the actual object.





## Mocks. A fake implementation of a class used for testing.
* A test double for dependent objects - like a datasource.
* Can provided expected responses.
* Can verify expected interactions.





## Spy - Like a mock, but real object is used.
* Mocks completely replace expected object.
* Spy are wrappers, but whit real object inside.





## Important Terminology:
* Verify - Used to verify number of times a mocked method has been called.
* Argument Matcher - Matches arguments passed to Mocked Method & will allow or disallow.
* Argument Captor - Captures arguments passed to a Mocked Method.
* Allows you to perform assertions of what was passed in to method.





## Help.
