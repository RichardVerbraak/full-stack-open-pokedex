### Language of choice

I've picked Python as an example here, I've only ever coded a Hello World example in Python.

### Questions

#### Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

1. Linting

For linting I'd use Flake8. It's in my opinion the better documented linter out of the other choices like Pylama or Pylint. From what I've read, Flake8 is better if you only care about code being correct on a basic level and on white-space issues while Pylint is more thorough - which in turn would cause you to spend a lot more time getting code _exactly_ right.

2. Testing

It's a hard pick between pytest and using the inbuilt python module, unittest. However after taking a closer look at Pytest and, again, seeing good documentation and the multitude of plugins it supports, it would seem to be the obvious choice. It's the no-boilerplate version of unittest and at a glance, it doesn't seem all that hard to setup.

3. Building

Since Python is an interpreted language and not a compiled language (it does not have to be compiled manually to source code), Python for this assumingly small project without a bunch of extensions, does not need a build tool.
