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

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: e3cdcfeb-e126-46e0-95ee-5e405f103379
* title: If statements
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will the following code write to the console?

```typescript
let firstVar: number = 15;
let secondVar: string = “hello”;
if(secondVar === “hello world”) {
  console.log(secondVar);
} else if (firstVar > 10) {
  console.log(firstVar);
} else {
  console.log(”goodbye”);
}
```
##### !end-question
##### !options
* undefined
* 15
* Error: Operator '>' cannot be applied to types 'string' and 'number'.
* “hello world”
* “goodbye”
##### !end-options
##### !answer
15
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 1cfc5464-fbc7-4613-aa5c-ba88b1fbac72
* title: For loops
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will the following code write to the console? 

```typescript
let myNum: number = 0;

for(let i:number = 36; i > 0; i = i - 3) {
  myNum = myNum + 1;
}

console.log("i is " + myNum);
```
##### !end-question
##### !options
* "i is 36"
* "i is 24" 
* "i is 12"
* "i is 6"
* "i is 3"
##### !end-options
##### !answer
"i is 12"
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5b00718c-28a4-4cb8-8939-e3e26ea561f1
* title: For...in loops
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will the following code write to the console? 
```typescript
const myObj: any = {
  firstname: "Ian",
  lastname: "Culleton",
  github: "ian-culleton",
  email: "ian.culleton@galvanize.com"
}

const myArray: string[] = [];
for(let key in myObj) {
  myArray.push(key);
}

console.log(myArray);
```
##### !end-question
##### !options
* [0, 1, 2, 3] 
* ["firstname", "lastname", "github", "email"] 
* ["Ian", "Culleton", "ian-culleton", "ian.culleton@galvanize.com"] 
* []
* Error: Assignment to constant variable. 
##### !end-options
##### !answer
["firstname", "lastname", "github", "email"] 
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 403343b0-5f05-4978-a60c-f6b56d77eceb
* title: Arithmetic operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following are _arithmetic_ operators in TypeScript? (Select all that apply)
##### !end-question
##### !options
* +
* =
* *
* ===
* /
* //
* &&
* %
* !
##### !end-options
##### !answer
* +
* *
* /
* %
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 6e9b4aa3-f3db-4e64-a686-3edc54a206ab
* title: Logical operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following are _logical_ operators in TypeScript? (Select all that apply)
##### !end-question

##### !options
* +
* =
* *
* ===
* /
* //
* &&
* %
* !
##### !end-options
##### !answer
* &&
* !
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: fa62f16f-969b-4be5-8cef-e855ecdb175c
* title: Comparison operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following are _comparison_ operators in TypeScript? (Select all that apply) 
##### !end-question
##### !options
* +
* =
* *
* ===
* /
* //
* &&
* %
* !
##### !end-options
##### !answer
 ===
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge
* type: multiple-choice
* id: 5e918c07-91e2-4187-b5d7-e2bbd9da4115
* title: Math
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->
##### !question
What will the following code write to the console?
```typescript
const foo = (22 + 4 * 2 - 2) / 4;
console.log(foo)
```
##### !end-question
##### !options
* 0
* 12.5
* 7 
* 11
* 13
##### !end-options
##### !answer
7
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 0a6bb3fd-d219-4cf8-b2cc-228ee497f17f
* title: Logical operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following expressions evaluates to true?
##### !end-question
##### !options
*  true && false === false || true
* 13 > 16 || 18 <= 13
* “foo” !== “bar” && “baz” === “bam”
* 3 + 4 + 2 * 5 >= 16 / 2 + 27 / 3 * (3 + 8 - 10)
##### !end-options
##### !answer
3 + 4 + 2 * 5 >= 16 / 2 + 27 / 3 * (3 + 8 - 10)
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: aa6a7612-1f40-46e6-8274-fcf09e98241e
* title: Logical operators
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following expressions evaluates to false? 
##### !end-question
##### !options
* "typescript".charAt(4) === "strings".charAt(6)
* "typescript".includes("JavaScript".substr(4, 9).toLowerCase())
* typeof “typescript”.charCodeAt(3) === “string”
* "type".concat('script').length === 10
##### !end-options
##### !answer
typeof “typescript”.charCodeAt(3) === “string”
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: e77ebe7f-bc47-4080-82b1-90da7fda848c
* title: Destructuring
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What will the following code write to the console? 
```typescript
const myObj: any = {
  myKey: 42,
  mySecondKey: 'forty-two'
}
const { mySecondKey } = myObj;
console.log(mySecondKey);
```
##### !end-question
##### !options
* {myKey: 42, mySecondKey: 'forty-two'}
* ‘forty-two’
* 42
* undefined
##### !end-options
##### !answer
‘forty-two’
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

## SECTION 2: Angular

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: cc553cdf-3eb8-469d-b7d0-6c813c3d146c
* title: Modules
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following is used to declare components that belong to a module within `@NgModule`?
##### !end-question
##### !options
* `declarations`
* `imports`
* `bootstrap`
##### !end-options
##### !answer
`declarations`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 17d8a869-69e4-49cd-9804-3d9f57d3322b
* title: Data Binding
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Below are some statements about data binding. Check all that are **true**
##### !end-question

##### !options
* Event binding allows components to respond to user actions.
* Property binding allows components to respond to user actions.
* Event binding is achieved using `[ ]` syntax in a template.
* Event binding is achieved using the `@Output` decorator in component class definitions.
* property binding is achieved using `[ ]` syntax in a template.
* Property binding is achieved using the `@Input` decorator in component class definitions.
* All of the above.
##### !end-options

##### !answer
* Event binding allows components to respond to user actions.
* Event binding is achieved using the `@Output` decorator in component class definitions.
* property binding is achieved using `[ ]` syntax in a template.
* Property binding is achieved using the `@Input` decorator in component class definitions.
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 816fcca2-bed1-4156-b5d7-75333bec8726
* title: Data binding
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Consider the template code below: 
```
<app-profile
  [name]="'Alton Brown'"
  [email]="alton@foodnetwork.com"
  (profileSelected)="handleProfileClick($event)"
></app-profile>
```

which line above contains event binding?
##### !end-question

##### !options
* `<app-profile`
* ` [name]="'Alton Brown'"`
* ` [email]="'alton@foodnetwork.com'"`
* ` (profileSelected)="handleProfileClick($event)"`
##### !end-options

##### !answer
` (profileSelected)="handleProfileClick($event)"`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: c0fd35ff-bcce-4be4-b709-79cd5d89e1c4
* title: Types of directives
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What are the three types of Angular directive? (Select all that apply)
##### !end-question

##### !options
* circular
* structural
* attribute
* prime
* component
* display
* implicit
##### !end-options

##### !answer
* structural
* attribute
* component
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: c7cef33a-b38e-46f6-a3b3-1cd9b4c3e284
* title: Structural directives
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What are structural directives used for?
##### !end-question
##### !options
* They control the appearance and behavior of a region of the screen.
* They are used to create, arrange, or remove DOM elements.
* They change the appearance or behavior of DOM elements
##### !end-options
##### !answer
They are used to create, arrange, or remove DOM elements.
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: f6c2ff8b-dcb4-4c15-a44f-488ff43b6c9d
* title: Attribute directives
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What are attribute directives used for?
##### !end-question
##### !options
* They control the appearance and behavior of a region of the screen.
* They are used to create, arrange, or remove DOM elements.
* They change the appearance or behavior of DOM elements
##### !end-options
##### !answer
They change the appearance or behavior of DOM elements
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 826d543f-d5a1-4da8-b348-e6e4dfc75348
* title: Dependency Injection
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following is **NOT** true of Angular's dependency injection system?
##### !end-question
##### !options
* Dependencies are registered with Angular using the `Injectable` decorator.
* Each component instantiates a new instance of the injected service.
* Dependencies are injected into components using a parameter in the component constructor.
##### !end-options
##### !answer
Each component instantiates a new instance of the injected service.
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 8afe2819-55d4-40e5-a398-d1b1e9f1817f
* title: Forms
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following best describes the relationship between a `FormControl` and a `FormGroup`?
##### !end-question
##### !options
* A `FormControl` controls the validation of a `FormGroup`.
* A `FormControl` contains all of the `FormGroup` instances for a single form.
* A `FormGroup` contains all of the `FormControl` instances for a single form.
* A `FormGroup` returns a new `FormControl` every time the value of an input changes.
##### !end-options
##### !answer
A `FormGroup` contains all of the `FormControl` instances for a single form.
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 513312c6-73ab-4f7c-bfac-3e555a2a123f
* title: FormGroup
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which of the following directives is used to bind an input in the template to a specific field in a `FormGroup`?
##### !end-question
##### !options
* `formGroup`
* `formControl`
* `formControlName`
* `ngFormField`
##### !end-options
##### !answer
`formControlName`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: fb953206-0e5a-41f5-aba0-3f7a4885d30d
* title: Routing
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which built-in directive is used to specify the location in a template the router should render its content?
##### !end-question
##### !options
* `NgModule`
* `routerLink`
* `router-outlet`
* `NgRouter`
* `AppRoutingComponent`
##### !end-options
##### !answer
`router-outlet`
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

## SECTION 3: C#  8.0

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
* title: Switch expressions
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


## SECTION 4: .NET
<!-- HERE FOLLOWS THE .NET PORTION OF THE ASSESSMENT -->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 981d5c0c-3552-4467-b754-0e8ce15a3aa9
* title: Operating Systems
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
.NET Core 3.0 can only run from a Windows operating system.
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
* id: fe462366-5720-4db8-b938-bbf20c0de059
* title: Garbage Collection
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Is the default garbage collection heap size larger or smaller in .NET Core 3.0?
##### !end-question
##### !options
* larger
* smaller
##### !end-options
##### !answer
smaller
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 26ecd1da-602c-4b1a-a867-bf9a8de615d4
* title: Operating Systems
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
WPF and WinForms can now run on Linux and MacOS operating systems with .NET Core 3.0.
##### !end-question
##### !options
* True
* False
##### !end-options
##### !answer
* False
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 06cbd5ed-9303-4b94-9b1f-d1be9aa646e1
* title: licensing
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
.NET Core and it's libraries are provided under which license(s)? (Select all that apply)
##### !end-question

##### !options
* Ms-RSL (Microsoft Reference Source License)
* MIT License
* Apache 2 License
* GPL 3.0 (General Public License)
* BSD License 2.0 (Berkeley Software Distribution)
##### !end-options
##### !answer
* MIT License
* Apache 2 License
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 46ef5184-e9dc-4bab-b2d7-1240fc33aebd
* title: .NET Framework vs. .NET Core
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Select the reasons you should use .NET Framework instead of .NET Core: (select all that apply)
##### !end-question
##### !options
* Your app uses third-party .NET libraries not available for .NET Core
* You need side-by-side .NET versions per application
* You need high-performance and scalable systems
* You are targeting microservices.
* Your app uses a platform that doesn’t support .NET Core
##### !end-options
##### !answer
* Your app uses third-party .NET libraries not available for .NET Core
* Your app uses a platform that doesn’t support .NET Core
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 40ced5f8-e3a6-4a1e-b242-ef11abd32363
* title: Application types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which application types are NOT found in .NET Core 3.0? (Select all that apply)
##### !end-question
##### !options
* UWP
* WebForms
* WinForms
* WebHooks
* ASP.NET
* Console
* WCF
* Windows Services
* SignalR
##### !end-options
##### !answer
* WebForms
* WebHooks
* WCF
* Windows Services
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: short-answer
* id: 7bca2299-4bb2-47ad-8661-7f09233ce7b8
* title: .NET versions
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
The next version of .NET Core after 3.1 will be:
##### !end-question
##### !answer
5
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5deacf21-bd6f-4065-9e40-d5fe99b78ed2
* title: COM callable components
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
.NET Core 3.0 does not support COM callable components.
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
* id: 70d180d2-3572-4543-9006-8fafe5e99890
* title: WPF Applications
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
What language is used when defining the user interface of a WPF application?
##### !end-question
##### !options
* HTML
* CSS
* XAML
* Javascript
##### !end-options
##### !answer
* XAML
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: checkbox
* id: 98847ac4-4a56-438e-b3aa-3700642a5d40
* title: .NET Core feature support
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
The following are C# 8 features supported by .NET Core 3.0 (select all that apply)
##### !end-question
##### !options
* Spread Operator
* Nullable Reference Types
* YAML file format
* Ranges
* Switch Expressions
* Fat Arrow Syntax
##### !end-options
##### !answer
* Nullable Reference Types
* Ranges
* Switch Expressions
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: fa8b353c-21d4-42aa-aac8-9d273c17e057
* title: .NET standards
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
.NET Core 3.0 implements which .NET Standard?
##### !end-question
##### !options
* 5.0
* 4.8
* 3.5
* 2.1
* 2.0
##### !end-options
##### !answer
2.1
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 70977b44-bcd1-4729-9278-46d1fe385790
* title: Deployment types
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Which deployment type is the default in .NET Core 3.0?
##### !end-question
##### !options
* FDD
* FDE 
* SCD
* EXE
##### !end-options
##### !answer
FDE
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 036c5191-0268-4893-b4f9-2a97991976c7
* title: JSON and POCOs
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Use which method to create a JSON string from a POCO:
##### !end-question

##### !options
* JsonSerializer.ConvertToString()
* JsonSerializer.SerializeToString()
* JsonSerializer.Serialize()
* JsonSerializer.ToSring()
##### !end-options
##### !answer
JsonSerializer.Serialize()
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: c7418b56-c141-40a7-b01c-9a5e8937471a
* title: JSON and POCOs
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
Use which method to create a POCO from a JSON string?
##### !end-question
##### !options
* JsonSerializer.ConvertToObject()
* JsonSerializer.DeserializeToObject()
* JsonSerializer.Deserialize()
* JsonSerializer.ToObject()
##### !end-options
##### !answer
JsonSerializer.Deserialize()
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5c951543-c9f6-4271-8903-22537d7b3d04
* title: JSON
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question
The JsonSerializer class must be imported from the Newtonsoft JSON package library.
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