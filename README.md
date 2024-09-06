# POOP-Lang
POOP lang (pythonesque object oriented programming language)
# Documentation
# Types and datastructures
Variables in POOP lang are set with the `turd` keyword. Take this example:

```stringy turd name = "finn"```

The syntax for variables goes as follows:

<code>_type_ turd _variable name_</code>

POOP lang is a statically typed language. Here are the different types:

The `runny` type is used for floating point numbers

The `chunky` type is used for integers

The `stringy` type is used for string literals

The boolean types are represented by the `shart` keyword. True is represented by `shit` and false with `fart`

Lists are represented by the `diarrhea` keyword. `diarrhea` can only contain `turd`.

# Input and Output
POOP lang has a powerful built-in io libary with numerous capabilities referred to as `butt`(output) and `mouth`(input)

The standard output is known in POOP lang by the `toilet` keyword.

To include a library, use the `eat` keyword followed by the package name.

Below is an example of outputing a `stringy turd` to the `toilet` using the `butt` group of functions.

```
eat butt
stringy turd name = "finn"
butt.dump(name, toilet)
```

The `butt.dump()` function has 2 arguments position 1 is what to be dumped to the output, and the second argument is where to dump it to, in this case the `toilet`.

In the next example, we will take an input from the user and asign it to a `stringy turd` and `dump` it to the `toilet`.

```
eat butt
eat mouth
stringy turd name = mouth.swallow("What is your name?", mouth)
butt.dump("Your name is" + name, toilet)
```

# Conditionals

In POOP lang conditionals are using the `if` keyword, and returns with the `flush` keyword. here we will compare to `solid` type turds and if they are the same, `flush shit` , otherwise `flush fart`

```
solid turd num1 = 3
solid turd num2 = 4
if num1 == num2:
  flush shit
else:
  flush fart
```
If run this programm would return fart as 3 != 4.
