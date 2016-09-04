# Go: Robot Name

Write a program that manages robot factory settings.

When robots come off the factory floor, they have no name.

The first time you boot them up, a random name is generated in the format
of two uppercase letters followed by three digits, such as RX837 or BC811.

Every once in a while we need to reset a robot to its factory settings,
which means that their name gets wiped. The next time you ask, it will
respond with a new random name.

The names must be random: they should not follow a predictable sequence.
Random names means a risk of collisions. Your solution should not allow
the use of the same name twice when avoidable. In some exercism language
tracks there are tests to ensure that the same name is never used twice.

The tests are written using the `testing` package in the standard library.

To run a test file use the `go test` command:

    go test

## Source

A debugging session with Paul Blackwell at gSchool. [http://gschool.it](http://gschool.it)

This exercise is from the [Go][go] track on [Exercism][exercism]

[exercism]: http://exercism.io
[go]: http://exercism.io/languages/go



