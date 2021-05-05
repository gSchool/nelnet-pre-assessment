# Pre-Assessment  

Welcome to the nelnet pre-assessment.  This assessment is designed to gauge how much of the material in this class you are *already familiar with.*  It comprises a number of questions about TypeScript, Angular, C#, .NET, and Object-oriented design principles.  Here are a few things you should know before you get started:

  - You should plan on spending no more than 1 hour on this assessment.  If you have worked on it for an hour, you should stop working on it.
  - You are *not* expected to answer most of these questions correctly.  You are not even expected to answer *any* of these questions correctly.  
  - This pre-assessment will not contribute to any official assessment in this class-- the only purpose of this pre-assessment is to give your instructors greater insight into your existing skillset, which will help us tailor the course to your needs and, hopefully, produce a more engaging and relevant course for you.
  - Please *do not* look up answers or use external resources.  If you do, instructors may skip over information that we think you already know.

Thank you for taking the time to complete this assessment.  We look forward to working with you in the coming months!

## SECTION 1: TypeScript

<!--BEGIN CHALLENGE-->

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

<!--BEGIN CHALLENGE-->

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

<!--BEGIN CHALLENGE-->

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

<!--BEGIN CHALLENGE-->

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



## SECTION 2: C#  8.0

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: af9f4ebd-a084-44d4-93db-6dbfb7d20cb6
* title: Reference types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Nullable reference types are backward compatible with previous versions of C#.
##### !end-question
##### !options

* True
* False

##### !end-options
##### !answer

False

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: fcd615ee-1a73-4d5e-b7f0-aa2fe647fd9e
* title: Array access
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Given an array with 9 elements, which index below will access the last element?
##### !end-question
##### !options

* ^9
* ^1
* ^0
* ^8

##### !end-options
##### !answer
^1
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: d535141f-b299-43f7-a678-4f8377c86cdf
* title: Asynchronous code
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of these is *not* a property of a method that returns an asynchronous stream?
##### !end-question
##### !options
* It is declared with the async modifier
* The method contains yield return statements
* It returns an `IAsyncEnumerable<T>`
* It adds await before the foreach keyword
##### !end-options
##### !answer

It adds await before the foreach keyword

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 1cfc6159-8c88-4ac9-a66a-c316e48c5691
* title: Nullable and non-nullable reference types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Enabling nullable and non-nullable reference types will cause compiler errors when a variable may potentially have null assigned to it.
##### !end-question
##### !options
* True
* False
##### !end-options
##### !answer
False
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: b9295284-3179-405a-a1bd-ebbe77636287
* title: Variable declarations
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What is the correct way to declare a variable named FirstName as a nullable reference type?
##### !end-question
##### !options
* `string! FirstName;`
* `string? FirstName;`
* `string FirstName!;`
* `string FirstName?;`
##### !end-options
##### !answer
`string? FirstName;`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 3e4ac8b7-60cf-4fbb-b15d-a7051f6095e3
* title: Null-forgiving operator
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
You can explicitly override the compiler warning for non-nullable types by using the null-forgiving operator. The null-forgiving operator is declared by appending the _________ character to the end of variable or field name and before any properties are accessed on that variable or field.
##### !end-question

##### !options
* $
* !
* ?
* &
##### !end-options
##### !answer
?
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 28ca691e-9279-42bf-9d84-b2b8626a4082
* title: Nullable reference types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which property must be set to "enable" in the csproj file to enable nullable reference types?
##### !end-question

##### !options
* NullableCompiler
* Nullable
* NullableReference
* ReferenceNullable
##### !end-options

##### !answer
Nullable
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 85d03d97-053f-4241-8cd4-a8edeb6fb47c
* title: Code comprehension
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will be the result of the following code?

```csharp
public namespace PropertyPatterns
{
  public class Address 
  {
    public string Street { get; set; }
    public string City { get; set; }
    public string State { get; set; }
    public string Zip { get; set; }
  }
  class Program 
  {
    static void Main(string[] args)
    {
      Address locationObject;
      locationObject = new Address(){ State = "MN" };
      var result = locationObject is { State: "MN" };
      Console.WriteLine(result);
    }
  }
}
```
##### !end-question
##### !options
* "True" is written to the console
* An "InvalidOperationException" is thrown
* "False" is written to the console
* PropertyPatterns.Address is written to the console
##### !end-options
##### !answer
"True" is written to the console
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 6cfc4f04-0a55-4d78-9030-6685805b1670
* title: Asynchronous code
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
In order to consume an asynchronous stream you must use:
##### !end-question
##### !options
* await foreach
* foreach await
* .forEach() on the method
* .awaitForEach() on the method
##### !end-options
##### !answer
await foreach
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: dc481f85-c1c1-4cf3-8dd0-67eb3da0f131
* title: Switch statements and expressions
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which is NOT a difference between a switch expression compared to a switch statement:
##### !end-question

##### !options
* The variable comes before, not after the `switch` keyword.
* The `=>` replaces The `case` and `:` elements
* The `default` case is replaced with a more concise `:` discard.
* Instead of statements, the bodies are expressions
##### !end-options
##### !answer
The `default` case is replaced with a more concise `:` discard.
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5c374ab7-0757-4102-a1bd-3a4a12bf588f
* title: Code comprehension
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
The following code will throw a null reference exception:

```csharp
public class Employee {
  public string? FirstName { get; set; }
  public string? LastName { get; set; }
  public string? Email { get; set; }
  public double? PayRate { get; set; }
}

class Program 
{
  static void Main(string[] args)
  {
    var employee = new Employee
    {
      FirstName = "John"
    }

    var nameLength = employee.FirstName.length + employee.LastName.length;
    Console.WriteLine($"The employee is called {employee.FirstName} {employee.LastName}.");
  }
}
```
##### !end-question
##### !options
* True
* False
##### !end-options
##### !answer
True
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 77f49187-b931-407b-9612-1460c609f5cd
* title: <!--A short title-->
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
If a switch expression does not include a default expression then the following will happen:
##### !end-question

##### !options

* A compiler error
* A compiler warning
* The last expression will be the returned
* Nothing

##### !end-options

##### !answer
A compiler warning
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: e0f37a23-2bc9-4bef-bcf9-15a0b7f7e11d
* title: Operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
The ^ operator is also known as:
##### !end-question
##### !options
* The carat operator
* The exponent operator
* The index operator
* The hat operator
##### !end-options
##### !answer
The hat operator
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: b90f883d-642c-4a09-b4a5-0d9171c683e0
* title: Switch expressions
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of these signify the start of a default expression in a switch expression
##### !end-question
##### !options
* =>
* default
* _ =>
* return
##### !end-options

##### !answer
_ =>
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5c674869-75c7-40f0-9f61-e06260530472
* title: Array access
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Given an array with 9 elements, which range below will access the 1st through 4th element?
##### !end-question
##### !options
* 0..4
* 0..5
* 1..4
* 1..5
##### !end-options
##### !answer
0..5
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 42024879-3980-4817-9c01-254f03f6b97c
* title: Async methods
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Async methods that return type IAsyncEnumerable<T> must have an await call within them.
##### !end-question
##### !options
* True
* False
##### !end-options
##### !answer
False
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->



<!-- HERE FOLLOWS THE .NET PORTION OF THE ASSESSMENT -->