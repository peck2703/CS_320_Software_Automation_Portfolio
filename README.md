# CS_320_Software_Automation_Portfolio
Portfolio for CS 320 - Software Automation, QA - Southern New Hampshire University

How can I ensure that my code, program, or software is functional and secure?

By writing tests that are written well enough to capture and test for various cases of failures versus successes is what makes a good test. And while no software can be 100% tested for every possible answer, making a documented list of all commonly used inputs, or lack of, while simultaneously accounting for attacks or vulnerabilities can make the software secure, but also functional.

How do I interpret user needs and incorporate them into a program?

When you receive a contract for a client, they will have requirements that they themselves have to meet to their customers and from there you have the initial test basis for your tests. So if your customer's project requires some input from a user standpoint, you know you will have to write tests to simulate good, poor and even abysmal user experiences. These tests will be extensive but not always exhaustive, but will prove to the client that your software should be able to catch even the dumbest customers' mistakes when operating the software. Beyond their initial requirements, there will also be other requirements that may arise as a result of the rest of the coding structure that will require testing, and keeping all tests and doing regression testing will help to reduce technical debt as you continue writing the code, knowing that if any changes affect previous work, the tests will reveal it long before it goes to deployment.

How do I approach designing software?

First off when designing software, you must understand the requirements that the customer requires, and any requirements that the customer is not aware of that should be required for the project. Including these test cases into your basis will keep the project standing publicly visible. If you write the tests long after defined sprints or before final deployment, you may find issues that you could have fixed long ago and now the project has technical debt that must be fixed before the customer can sign off on it. So taking this into consideration, writing the tests immediately after writing code and testing it alongside the developed code during the same sprint seems to be effective in refactoring the code right then and there.
