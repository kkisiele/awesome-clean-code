# Awesome Clean Code [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
## Design Principles
### [SOLID](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
Acronym coined by Robert C. Martin (Uncle Bob) to descibe the following five principles:
1. [The Single Responsibility Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk) A class should have only one reason to change.
2. [The Open Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en) Software entities should be open for extension, but closed for modification.
3. [The Liskov Substitution Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh/view) Derived classes must be substitutable for their base classes.
4. [The Interface Segregation Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi/view) Make fine grained interfaces that are client specific.
5. [The Dependency Inversion Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz/view) Depend on abstractions, not on concretions.

A local copy of ["Design Principles and Design Patterns"](https://github.com/kkisiele/awesome-clean-code/raw/master/principles_and_patterns.pdf) by Robert C. Marin from _objectmentor.com_ website.
More about this principles with examples can be found [here](https://lostechies.com/wp-content/uploads/2011/03/pablos_solid_ebook.pdf)

### [Kent Beck's Four Rules of Simple Design](https://martinfowler.com/bliki/BeckDesignRules.html)
![Kent Beck's Four Rules of Simple Design](https://github.com/kkisiele/awesome-clean-code/raw/master/kent_beck_simple_design.jpg "Kent Beck's Four Rules of Simple Design")

A design which:
1. Passes all tests.
2. Reveals intention.
3. No duplication.
4. Fewest elements.

### [Elegant Objects](http://www.elegantobjects.org)
1. No null.
2. No code in constructors.
3. No getters and setters.
4. No mutable objects.
5. No static methods, not even private ones.
6. No instanceof, type casting, or reflection.
7. No public methods without @Override.
8. No statements in test methods except assertThat.
9. No implementation inheritance.

### [CUPID](https://dannorth.net/2022/02/10/cupid-for-joyful-coding/)
1. Composable: plays well with others
2. Unix philosophy: does one thing well
3. Predictable: does what you expect
4. Idiomatic: feels natural
5. Domain-based: the solution domain models the problem domain in language and structure

## Featured Articles
* [When A Method Can Do Nothing](https://michaelfeathers.silvrback.com/when-it-s-okay-for-a-method-to-do-nothing)
* [Tell Don't Ask](https://martinfowler.com/bliki/TellDontAsk.html)
* [Converting Queries to Commands](https://michaelfeathers.silvrback.com/converting-queries-to-commands)
* [Object Calisthenics](https://www.bennadel.com/resources/uploads/2012/ObjectCalisthenics.pdf)
* [How Interfaces Are Refactoring Our Code](http://www.amihaiemil.com/2017/08/12/how-interfaces-are-refactoring-our-code.html)
* [Your Constructors are Completely Irrational](http://blog.thecodewhisperer.com/permalink/your-constructors-are-completely-irrational)
* [Class naming](http://objology.blogspot.com/2011/09/one-of-best-bits-of-programming-advice.html)
* [Names objects after things, not actions!](http://matteo.vaccari.name/blog/archives/743)
* [Interfacing with hard-to-test third-party code](http://misko.hevery.com/2009/01/04/interfacing-with-hard-to-test-third-party-code/)
* [How to Think About the "new" Operator with Respect to Unit Testing](http://misko.hevery.com/2008/07/08/how-to-think-about-the-new-operator/)
* [Avoiding Repetition](https://www.martinfowler.com/ieeeSoftware/repetition.pdf)
* [Design Principles from Design Patterns - A Conversation with Erich Gamma](https://www.artima.com/lejava/articles/designprinciplesP.html)
* [Programming Like Kent Beck](https://blog.iterate.no/2012/06/20/programming-like-kent-beck/)
* [How Immutability Helps](https://www.yegor256.com/2014/11/07/how-immutability-helps.html)
* [Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
* [Hexagonal Architecture: three principles and an implementation example](https://blog.octo.com/en/hexagonal-architecture-three-principles-and-an-implementation-example/)
* [Getting Started With DDD When Surrounded By Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf)
* [Clean Code in Python](https://testdriven.io/blog/clean-code-python/)
* [Refactoring Legacy Code with the Strangler Fig Pattern](https://shopify.engineering/refactoring-legacy-code-strangler-fig-pattern) also available in [video](https://www.youtube.com/watch?v=zZ95_5y_iPk)
* [Immutable architecture](https://enterprisecraftsmanship.com/posts/immutable-architecture/)
* [The Humble Dialog Box by Michael Feathers](https://martinfowler.com/articles/images/humble-dialog-box/TheHumbleDialogBox.pdf)
* [The Transformation Priority Premise by Uncle Bob](https://blog.cleancoder.com/uncle-bob/2013/05/27/TheTransformationPriorityPremise.html)

## Tutorials
* [Refactoring a JavaScript video store](https://martinfowler.com/articles/refactoring-video-store-js)
* [Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
* [Refactoring from anemic model to DDD](https://blog.pragmatists.com/refactoring-from-anemic-model-to-ddd-880d3dd3d45f)
* [Writing Testable Code](http://misko.hevery.com/code-reviewers-guide)
* [Essential Skills for Agile Development](http://www2.cpttm.org.mo/cyberlab/softdev/ESAD/)
* [First Pop Coffee Company](https://buildplease.com/pages/fpc-1/)
* [Testing legacy by Sandro Mancuso](https://codurance.com/2011/07/16/testing-legacy-hard-wired-dependencies/), [part 2](https://codurance.com/2011/07/18/testing-legacy-hard-wired-dependencies_17/), and [video](https://www.youtube.com/watch?v=_NnElPO5BU0)
* [Live Refactoring Towards Solid Code](https://www.youtube.com/watch?v=jwJnd9ycs6Q)
* [Introducing the Gilded Rose kata and writing test cases using Approval Tests by Emily Bache](https://www.youtube.com/watch?v=zyM2Ep28ED8), [part 2](https://www.youtube.com/watch?v=OJmg9aMxPDI) and [part 3](https://www.youtube.com/watch?v=NADVhSjeyJA)
* [Domain Driven Design Crash Course](https://vaadin.com/learn/tutorials/ddd)
* [Reactive in practice: A complete guide to event-driven systems development in Java](https://developer.ibm.com/series/reactive-in-practice/)
* [Writing Clean Tests](https://www.petrikainulainen.net/writing-clean-tests/)
* [Tic-Tac-Toe Speedrun live coding](https://www.youtube.com/watch?v=z4qvIaJhSkU)
 
## Videos
* [How To Design A Good API and Why it Matters by Joshua Bloch](https://www.youtube.com/watch?v=aAb7hSCtvGw)
* [Inheritance, Polymorphism, & Testing](https://www.youtube.com/watch?v=4F72VULWFvc)
* [Don't Look For Things!](https://www.youtube.com/watch?v=RlfLCWKxHJ0)
* [Don't Create Objects That End With -ER](https://www.youtube.com/watch?v=WpP4rIhh5e4)
* [8 Lines of Code by Greg Young](https://www.infoq.com/presentations/8-lines-code-refactoring) Accompanied [slides](https://github.com/kkisiele/awesome-clean-code/raw/master/GregYoung_8LinesOfCode.pdf)
* [19 1/2 Things to Make You a Better Object Oriented Programmer](https://vimeo.com/17151526) Nice [summary](http://www.simpletechture.nl/blog/2011/objectoriented/)
* [Railway oriented programming: Error handling in functional languages](https://vimeo.com/113707214)
* [Yves Reynhout - Trench Talk: Evolving a Model](https://www.youtube.com/watch?v=7StN-vNjRSw)
* [Seven Ineffective Coding Habits of Many Programmers by Kevlin Henney](https://www.youtube.com/watch?v=ZsHMHukIlJY)
* [Java Optional - The Mother of All Bikesheds by Stuart Marks](https://www.youtube.com/watch?v=Ej0sss6cq14)

## Code Examples
* [Code Katas](https://github.com/kkisiele/codekata)
* [hentai](https://github.com/jakubnabrdalik/hentai)
* [Source code for the book, "Growing Object-Oriented Software, Guided by Tests"](https://github.com/sf105/goos-code)
* [jcabi-email](https://github.com/jcabi/jcabi-email)
* [Assignment done for some interview](https://github.com/kkisiele/loganalyzer)
* [Library project](https://github.com/ddd-by-examples/library)
* [Factory project](https://github.com/ddd-by-examples/factory)
* [Aggregates by Example](https://github.com/mariuszgil/aggregates-by-example)
* [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2)
* [ddd-wro-warehouse](https://github.com/michal-michaluk/ddd-wro-warehouse)
* [Cargo](https://github.com/citerus/dddsample-core)

## Git Hub
* [Nat Pryce](https://github.com/npryce)
* [Steve Freeman](https://github.com/sf105)
* [Matteo Vaccari](https://github.com/xpmatteo)

## Blogs
* [Martin Fowler](https://martinfowler.com/bliki)
* [Michael Feathers](https://michaelfeathers.silvrback.com)
* [Robert C. Martin (Uncle Bob)](https://blog.cleancoder.com)
* [Yegor Bugayenko](http://www.yegor256.com)
* [Code Cop](http://blog.code-cop.org)
* [The Code Whisperer](http://blog.thecodewhisperer.com)
* [jbrains.ca](http://blog.jbrains.ca)
* [Nat Pryce](http://www.natpryce.com)
* [Steve Freeman](http://www.m3p.co.uk/blog)
* [Miško Hevery](http://misko.hevery.com)
* [Matteo Vaccari](http://matteo.vaccari.name/blog)
* [Carlo Pescio](http://www.carlopescio.com)
* [Jeffrey Palermo](http://jeffreypalermo.com)
* [Kenneth Truyers](https://www.kenneth-truyers.net)
* [Vaughn Vernon](http://forcomprehension.com/blog/)
* [Codurance](https://codurance.com/publications/)
* [Mihai](https://www.amihaiemil.com)
* [Enterprise Craftsmanship](https://enterprisecraftsmanship.com)
* [The Iterate Blog](https://blog.iterate.no)
* [The Holy Java](https://theholyjava.wordpress.com)

## Twitter
* [Kent Beck](https://twitter.com/kentbeck)
* [Martin Fowler](https://twitter.com/martinfowler)
* [Robert C. Martin](https://twitter.com/unclebobmartin)
* [Ron Jeffries](https://twitter.com/RonJeffries)
* [Michael Feathers](https://twitter.com/mfeathers)
* [Yegor Bugayenko](https://twitter.com/yegor256)
* [Carlo Pescio](https://twitter.com/carlopescio)
* [Matteo Vaccari](https://twitter.com/xpmatteo)
* [Jeffrey Palermo](https://twitter.com/jeffreypalermo)
* [Kenneth Truyers](https://twitter.com/kennethtruyers)
* [Greg Young](https://twitter.com/gregyoung)
* [Eric Evans](https://twitter.com/ericevans0)
* [Vaughn Vernon](https://twitter.com/VaughnVernon)

## Books
* [Refactoring: Improving the Design of Existing Code by Martin Fowler](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Technology-ebook/dp/B007WTFWJ6) errata for the book can be found [here](https://martinfowler.com/refactoringErrata.html)
* [Clean Code by Robert C. Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship-ebook/dp/B001GSTOAM)
* [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8)
* [Elegant Objects by Yegor Bugayenko](https://www.amazon.com/gp/product/1519166915/)
* [Growing Object-Oriented Software, Guided by Tests](https://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests-dp-0321503627/dp/0321503627/)

## Other
* [Code Katas](http://codekata.com)
