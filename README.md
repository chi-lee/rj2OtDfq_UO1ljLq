# Get Tracking info from Courier

The goal of this challenge is to get the tracking information from the courier's system.

There are 3 tests:

```
Courier 1:
RC725823280CN
RL022869218CN
RC986104923CN
	
Courier 2: LBC Express
80009291893
139404375437		
1040719953

Courier 3:
RF253377797SG
RQ263146245SG

```


## The Output Format

The first thing you should do is read `test/index.js`. It is the **canonical reference**. As long as your crawler correctly implements the reference tests, it is considered a correct solution.


# Usage

## Instructions

1. [DOWNLOAD this repository](https://github.com/AfterShip/aftership-challenge/archive/master.zip) to your own Github `public` repository.
2. Create a new repo, name it by using [this shortGUID generator](http://www.shortguid.com/)
3. Do NOT fork, as other candidates would be able to see your solution easily.
4. Do preserve commit history so it is easy for us to add your repository as a remote.
5. Send us a link to the public repository you used and an estimate of how long you will take
6. Run `npm install`
7. Implement `Courier` in `lib/index.js`
8. Ensure all tests pass in node via `npm test`
9. When finished, send us an email to ask for a review
10. You may modify the test case, or using other tracking number. as the tracking number in the test case may be expired.

## Hints

* Before starting, try to see how AfterShip API work, you will get a better idea what tracking info should return.
* You can use ANY method to get the tracking result, including API, web crawler, or even you paid someone else to code for you. LoL

## Scoring

1. How do you identify the courier
2. How do you get the tracking result (By API, by web, by any other method)
3. If the code follow our guideline, easy to read, docmentaiton, etc.
4. Performance, the speed for getting the result
5. HOW do you solve the problems, if any.

Ideally your solution is **easily extensible** as we add additional types of test cases.

## Problem?
Contact us at jobs AT aftership.com

