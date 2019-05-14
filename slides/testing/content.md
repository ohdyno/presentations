## Testing

## Why do we test?

Surely it is because we are paid to test.

By this metric, the more tests we have, the higher code coverage we have,
the better we bring to the business.

Wrong!

To discuss testing, we have to understand the value of software.

What is the value of software?

Is software itself inherently valuable?  Maybe.  Since, done right, it captures
the mental model of a problem and solution space so precise that a computer is able to understand
the instruction set and execute.

However, fundamentally, software is only valuable when it delivers user value, and therefore, business
value.

So, if software is valuable only when delivering user value, and everything else we do is pretty much
a cost.  What's the value of testing?

**We test in order to increase confidence for stakeholders through evidence.**

To unpack, to increase confidence = being pragmatic, do things with balance.
Stakeholders = anyone that is affected by the software (users, business, developers, operations, legal)
Evidence = takes creativity and ingenuity to come up with evidence for all the stakeholders.

### To gain confidence that our software "does the right thing"


### Why automated testing?

Given that we've established the goal of testing.  Why do we want to automate testing?

We want to automate testing because in order to maintain confidence in our software doing the right thing,
we need to test often, ideally very often.

However, we know that humans are not very good at doing repetitive tasks well.  So, we offload that responsibility
to the machine.

Other considerations for automation.  Being able to automate a system requires a good understanding
of the system (state, inputs, and output).  It challenges us to understand our system and make improvements
if the system isn't easy to test in an automated fashion.

## Now, is it always necessary to do automate testing or testing in general?

As the rule of internet headline goes, the answer to any headline question is "No".
 
How could you get away from not testing?

## Why do we do TDD?

Deliver business value (long-term vs short-term)
Clean code
Refactor
Confidence
Tests
Test-first

## History TDD / BDD and Unit Testing
QA-written Tests
Developer Tests
Sequential / Interdependent Tests
Unit test
SUnit
JUnit

## The Testing Pyramid
Types of Tests
Unit Test
Integration Test
E2E Test
Names of test type should be reflective of what they do.

## Qualities of a Test Suite
Confidence
Clean
Freedom to Refactor
Fast

## Mocks and Test Doubles
