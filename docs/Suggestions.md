# Suggestions for Additional Study

These suggestions are aimed at learning various aspects of software
development with PHP.

## PhpStorm

* For video tutorials, check out both JetBrains and Laracasts
* You can run various tools directly from PhpStorm, including
static analysis, code sniffer, PHPUnit

## Unit Testing

* Check the PHPUnit tutorials at https://phpunit.de/
* Learn Test-Driven Development (TDD)
* An alternate mocking library is http://docs.mockery.io/en/latest/

## Web Request/Response Cycle

* Be sure you understand the full web request/response cycle
and where the PHP code fits into that cycle

## Possible Exercises

Work with a framework:

1. Install one or more frameworks with a database connection.
(My personal preference is CakePHP at https://cakephp.org/)
1. Create and run a command-line PHP script.
1. Have the command-line script show its command-line arguments.

Work with unit tests:

1. Create a function to add two integers.
1. Test it with PHPUnit.
1. Test it with the PHPUnit dataProvider.
1. Design (not write/implement) a class method to add two numbers.
1. Test it. The test should fail, since the method isn't yet written.
1. Write enough code for all tests to pass.
1. Change the tests to require the method be static.
1. Verify that at least one test now fails.
1. Change the method to be static.
1. All tests should now pass.