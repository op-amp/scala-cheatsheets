# Scala explained

Scala is a programming language that let you write **cool stuff** like:

```scala
def sing(i: Int) = s"Happy Birthday ${ if (i == 3) "dear Tom" else "to You" }"
(1 to 4).map(sing).foreach(println)
/* -->
Happy Birthday to You
Happy Birthday to You
Happy Birthday dear Tom
Happy Birthday to You
*/
```

This website **explains Scala features** that will help you understand
Scala programming.
Each explanation is illustrated by a **code snippet**
that can be **copy-pasted** into a Scala interpreter.

Talking about a Scala interpreter, here's how you can set up
Scala programming tools:

## Setup Scala environment

- **Install Scala** from the official website:
  [https://www.scala-lang.org/download/](https://www.scala-lang.org/download/)

- Verify the installation by checking **Scala version** with the command:
  ```bash
  scala -version
  # --> Scala code runner version 2.12.19 -- Copyright 2002-2024, LAMP/EPFL and Lightbend, Inc.
  ```

- Create a **Scala source code file** named `HelloWorld.scala`
  with the following content:

  ```scala
  // aligning the main class with the file name is not compulsory but recommended
  object HelloWorld {
    // the `main` method is the program entry point
    def main(args: Array[String]): Unit =
      println("Hello, world!")
  }
  ```

- Compile and run your **Scala program** using your favorite Scala environment
  (IntelliJ, sbt) or through a terminal:

  ```bash
  scala HelloWorld.scala
  # --> Hello, world!

  # or alternatively
  scalac HelloWorld.scala
  scala HelloWorld
  # --> Hello, world!
  ```

- Note that for most cases **JVM** (usually provided by JDK) must be
  pre-installed in order to run Scala codes.

- You can also use **Scala REPL**, an interactive command-line environment
  for evaluating and executing small code snippets.

## Start!

First of all, we will talk about [Scala basic syntax](syntax.md).

If you are already familiar with Scala, you can learn more about
[Scala cool functional programming (FP) features here](functions.md).

If you want to build beautiful software architectures,
you can take a look at [Scala mind blowing object concepts](classes.md).

For the most curious among you, there is also an exhaustive list of
Scala [keywords](keywords.md) and [symbols](symbols.md) with plenty of examples.

Enjoy.
