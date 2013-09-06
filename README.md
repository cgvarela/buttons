# Buttons

> How many ways are there to assemble a button?

This project is an exercise in separation of concerns related to structure, style, content and data. The primary goal is to clearly demonstrate how to construct UI components, all while using buttons as the example,

## Conventions

For the purposes of this project let's agree that:

* **component** refers to a user interface abstraction, such as a navbar, modal dialog, or (as with the main attraction of this project) a button.
* **style** refers to CSS, including pre-processors (here we use LESS, possibly SASS).
* **structure** refers to HTML, including templates (here we use Handlebars templates).
* **content** refers to any audial (sound), visual (video or images) or textual content that can be experienced directly by the user on a website or web application.
* **data**, as distinguished from content, refers to any data that is used for configuration and will not be directly experienced by the user. So while "Click Me!" would be considered the "content" of a button, any "modifier classes" of the button stored in JSON or YAML would be considered "data".

## Approach

### Separation of concerns

As a rule of thumb, each example in the project demonstrates a different approach to separating concerns between content, structure and style and, in general, each example will build upon the last, in order to demonstrate:

* increasing levels of complexity
* progressively higher levels of abstraction
* when applicable, different approaches or conventions for accomplishing the same goal

However, not all examples explicitly focus on "separation of concerns" as the purpose of the example, some examples show how to leverage JavaScript helpers with advanced templates, some offer alternatives for maintaining metadata about the component, while others are simply intended to help non-programmers get started or to give experienced programmers ideas.

### Flow

In general, the examples progress from "basic" to "advanced", beginning with [button-000](button-000), which should be more approachable for designers who have very little to no programming experience, eventually building up to more "complex" examples that might appeal to more experienced programmers.

Also, since the project is expressly intended to be instructive, by necessity some of the examples _should not be idiomatic_ and no judgement is made concerning how much abstraction is necessary, good, bad, idiomatic or otherwise. The driving assumption being that _it is equally instructive to see examples where code is, say, more abstracted than it should be as it is to see shining examples of perfection_. Especially when the user has the larger perspective of seeing multiple approaches for solving the same or similar problems. This project will give you examples, but the opinions will be left to you.


## Contributing

Would you like to add an example? Please do! Just fork the project and do pull request. I only ask that you attempt to number the example appropriately, according to the relative level of complexity of the example.

Also, in lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [grunt][http://gruntjs.com/].


## Author

**[Jon Schlinkert](https://github.com/jonschlinkert)**

+ [http://twitter.com/jonschlinkert](http://twitter.com/jonschlinkert)
+ [http://github.com/jonschlinkert](http://github.com/jonschlinkert)


## Release History

 * 2013-08-14   v0.1.0   Generated by the [Yeoman Generator](https://github.com/assemble/generator-assemble) for [Assemble](http://assemble.io). First commit.


## License
Copyright (c) 2013 Jon Schlinkert, and the authors of examples utilized herein.

Licensed under the [MIT license](LICENSE-MIT).

