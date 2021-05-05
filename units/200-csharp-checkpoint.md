
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

<!--TBD-->

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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 1cfc6159-8c88-4ac9-a66a-c316e48c5691
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: b9295284-3179-405a-a1bd-ebbe77636287
* title: <!--A short title-->
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
<!--The _text_ of the answer-->
##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 3e4ac8b7-60cf-4fbb-b15d-a7051f6095e3
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 85d03d97-053f-4241-8cd4-a8edeb6fb47c
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

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

<!--The _text_ of the answer-->

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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5c374ab7-0757-4102-a1bd-3a4a12bf588f
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: e0f37a23-2bc9-4bef-bcf9-15a0b7f7e11d
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: b90f883d-642c-4a09-b4a5-0d9171c683e0
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 5c674869-75c7-40f0-9f61-e06260530472
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->

<!--BEGIN CHALLENGE-->

### !challenge

* type: multiple-choice
* id: 42024879-3980-4817-9c01-254f03f6b97c
* title: <!--A short title-->
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

<!--The _text_ of the answer-->

##### !end-answer
### !end-challenge

<!--END CHALLENGE-->