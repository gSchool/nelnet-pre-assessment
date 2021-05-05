# Pre-Assessment  

Welcome to the nelnet pre-assessment.  This assessment is designed to gauge how much of the material in this class you are *already familiar with.*  It comprises a number of questions about TypeScript, Angular, C#, .NET, and Object-oriented design principles.  Here are a few things you should know before you get started:

  - You should plan on spending no more than 1 hour on this assessment.  If you have worked on it for an hour, you should stop working on it.
  - You are *not* expected to answer most of these questions correctly.  You are not even expected to answer *any* of these questions correctly.  
  - This pre-assessment will not contribute to any official assessment in this class-- the only purpose of this pre-assessment is to give your instructors greater insight into your existing skillset, which will help us tailor the course to your needs and, hopefully, produce a more engaging and relevant course for you.
  - Please *do not* look up answers or use external resources.  If you do, instructors may skip over information that we think you already know.

Thank you for taking the time to complete this assessment.  We look forward to working with you in the coming months!

## TypeScript

!<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 003a99f8-d2f3-49c7-8e16-c73156b6cf6f
* title: Primitive data types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following is NOT a primitive data-type in JavaScript / TypeScript?
##### !end-question
##### !options

* `string`
* `number`
* `boolean`
* `Date`
* `undefined`
* `null`
* `symbol`

##### !end-options
##### !answer
`Date`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

!<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 0bee0975-dafb-4fb2-bb94-ab22aff9d6f7
* title: Identifiers
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following is a valid TypeScript identifier?
##### !end-question
##### !options
* `switch`
* `$top-of-page`
* `dropdownAnimation`
* `1orMoreMenuItems`
##### !end-options
##### !answer
`dropdownAnimation`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

!<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 1d3cf623-104c-494e-bf0f-1ccbfe7969cf
* title: Variable Assignment
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will this TypeScript code log to the console, when it is run? 

```TypeScript
let firstVar: number = 15;
let secondVar: number = firstVar;
firstVar = 16;
console.log(secondVar);
```
##### !end-question
##### !options
* 15
* “secondVar”
* 16
* Error:  Identifier referenced before assignment
* undefined
##### !end-options
##### !answer
15
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

!<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: ee68702e-b539-40e9-a65a-d0b330837997
* title: Type Definitions
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following is **not** a valid type definition?
##### !end-question
##### !options
* `const a: Array<number>;`
* `const b: number[];`
* `const d: []number;`
* `const e: [number];`
##### !end-options
##### !answer
`const d: []number;`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->