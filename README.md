# DevOps Tycoon

![tycoon](images/Work_7.jpg)

Table top game to help illustrate the value of DevOps engineering practices in technology delivery. The game incorporates multiple game play approaches, including randomization from dice rolls, an element of choose your own adventure, and being strategic with risk/reward on decision making.

DevOps Tycoon is a quick 5-minute table top game designed for different presentations - at booths, video calls, and in-person workshops.  
The purpose of the game is to illustrate how investing in DevOps practices improves technology delivery, reduces incidents & mean time to resolve (MTTR), and reduce the cost of production defects by identifying and resolving issues early in the development lifecycle.

## Materials Needed

- Play money (approximately $1,500 per participant, if you have multiple players)
- (2) 6-sided dice
- Dry-erase board or notebook to keep leaderboard
- Print and cut [these cards](images/DevopsTycoon.pdf)

## Setup

1) Give participant **$500** in play money
2) Give participant 2 dice
3) The host keeps the rest of the play money and the cards.

## Gameplay

There are 10 rounds of dice rolling. Each round consists of evaluating the result of a dice roll and then presenting options to the participant to take action. The investment in DevOps practices listed below stack on top of each other.

Ultimately, the goal is to have the highest score (participant $) after the 10 rounds.

1) The participant rolls the dice.
2) If the participant rolls a 6 or more, then a production defect is found. The player must pay $80
3) Otherwise,  there was a successfull production deployment and the participant gets $50
4) If the player rolls a double,  then double the earnings or losses.  
   You can justify it by things like: "your app got featured in the app store",  
   or "your application got hacked, and the hacker deleted a bunch of data" 
5) After the turn is over, give the participant the option of investing in one of the DevOps practices. 
    - Explain that each one either reduces the risk of a production defect or reduces the cost of a production defect.
    - For example, the participant may decide to invest in a CI/CD pipeline,  this card has a +1 for risk,  and -10 for cost.
    - That means that on the next roll, the participant will only find a production defect on a roll of 7 or more instead of 6.  
    - If there is another production defect,  it will cost $70 instead of $80

> Note: This is also a great opportunity to explain what the practice is and how it can reduce the risk of a defect or help you recover faster.

6) Repeat 9 times.  Each time, the player rolls the dice, they pay or earn money, and have a chance to invest in another DevOps practice.
7) Keep a leader board of the participants if possible.  You might consider incorporating prizes for highest and/or lowest score, quickest to all the practices, or the like.
8) Let participants play multiple times if they want, so they can experiment with different strategies.

### DevOps Practice Investments

|Name|Benefit|Cost:
|---|---|---|
|CI/CD Pipeline|Reduce losses by $10 and increment defect score by one|$40|
|Feature flags|Reduce losses by $10|$20|
|End to end ownership|Reduce losses by $20 and increment defect score by one|$50|
|Pair programming|Increment defect score by one|$30|
|Test Driven Development (TDD)|Increment defect score by two|$70|
|Infrastructure as code|Reduce losses by $10 and increment defect score by one|$40|

#### Attribution

<a href="https://www.freepik.com/free-vector/business-man-working-hard-stock-financial-trade-market-diagram-vector-illustration-flat-design_13399753.htm#query=developer&position=29&from_view=search">Image by jcomp</a> on Freepik