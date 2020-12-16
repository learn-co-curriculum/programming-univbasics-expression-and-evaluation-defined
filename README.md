# Defining Expression and Evaluation

## Learning Goals

* Define "Expression"
* Identify the Parts of an Expression
* Identify Core Operators in Ruby
* Define "Evaluation"

## Introduction

We've seen that we can have a conversation with Ruby by using the IRB program.
Conversations, we've seen, are the things that result when two individuals
&mdash; be they human or machine &mdash; communicate _expressions_ to one
another.

We've been imprecise in defining "expression" while we were getting the hang
of it. Let's propose formal definitions for _expression_ and _evaluation_.

## Define Expression

An expression in a programming language is like a sentence in a spoken
language.

Some sentences are simple: "He wept." Some sentences are complex: "I sing of
weapons and a man, an outcast of Troy who was driven to the shores of Italy..."

Some expressions are simple: `2`. Some expressions are complex `1 + 2`. Some
expressions are _really_ complex: `10 + (3 * ( -1 ** 3) + 2) / 18`.

> **Definition**: Expression: A combination of information called _data_ and
> _symbols_ indicating how to combine _data_ called _operators_.

## Define "Evaluation"

_Evaluation_ is the process of interpreting an expression, according to rules,
to produce a return value.

## Expression and Evaluation with Ruby

![Expression being evaluated by Ruby](https://curriculum-content.s3.amazonaws.com/programming-univbasics/intro-to-programming-as-conversation/Image_67_ExpressEvaluation.png)

These definitions should align with your experience of having a conversation
with IRB from the previous lesson. Think about `255 / 5`.  Which parts of the
expression are _data_? Which parts are _operators_?

> *PRO-TIP*: Think it through yourself. Which is a given thing (_data_) and
> which parts tell you how to combine things (_operators_)?  When reading
> technical documents you can't simply read the answers, you ***have to***
> _think along_ not merely read.  You're not reading a gossip site or a sports
> story, co-participation is needed to help your brain learn that this stuff is
> important!

## Identify the Parts of an "Expression"

The _data_ are: `255` and `5`
The _operator_: is `/`

In this example, there is only one operator. It's certainly possible for
expressions to have multiple operators like `100 + 10 - 3`. In this example,
the _operators_ are `+` and `-`.

## Identify Core Operators in Ruby

Here's a table of other operators and their operations. Fortunately, all these
operators are either the same or nearly the same as their mathematical partner,
so you probably know all the operators you're going to need to get started.

|Operator|Operation|Note|
|--------|---------|----|
| `+` | Addition ||
| `-` | Subtraction ||
| `*` | Multiplication | We use `*` instead of `×` because it looks like `x`-the-letter|
| `/` | Division | We use `/` instead of `÷` because that's not on a keyboard|
| `**` | Exponentiation | We use `**` instead of `^` because `^` means something else in programming languages|
| `()` | Association | Expressions inside of `()` get evaluated earlier|

## Conclusion

In the next few lessons, we're going to introduce the **Essential Three
Expressions**:

![Three Essential Expression](https://curriculum-content.s3.amazonaws.com/programming-univbasics/expression-and-evaluation-defined/Image_86_EssentialExpressions.png)

1. The constant expression
2. The assignment expression (variable assignment)
3. The variable lookup expression

***All expressions, which are the core of every programming language are built
on these Essential Three Expressions.***

Let's visit the mysterious, yet oddly dull first of the essential expressions:
**The Constant Expression**.
