## Stated simply...

**NUnit aims to be a best in breed test framework that enables end to end testing of .NET projects by individuals and teams. It is  unopinionated and supports a number of different kinds of tests, allows for alternative approaches to testing and is usable by team members in a variety of roles.**

On this page, we articulate the details of what that statement means to us. We don't specify features here - but try to provide set of guidelines that will help us when we are considering what features to add.

## A Bit More Detail

### Kinds of Tests

NUnit began as a **unit testing** framework and still has the best support for that type of test. In addition, we are working to fully support **integration, acceptance, performance** and other types of tests.

### Approaches to Testing

All of us are pretty excited about **Test-Driven Development**. However, we recognize that many programmers are either not yet using TDD or are working on legacy projects for which TDD is not even possible. NUnit supports various alternative approaches, including generation of tests for existing code bases.

### Developer versus Programmer

Even though NUnit started as a tool for **programmers**. we want to recognize and fulfill the needs of the **whole team**, including programmers, testers, interaction designers, web designers, data base specialists, customers and managers.

## Principles

**Runing tests everywhere.** We'll continue to expand the available choices regarding where tests are run. We now support use of multiple AppDomains as well as separate processes. We expect to expand this to cover test execution under a particular subsystem or on a separate machine.

**NUnit is extensible.** We can't do everything for everybody but we will make it reasonably easy to extend NUnit. In many cases, users will be able to implement a plugin that provides a special feature outside of our scope by simply creating a new attribute that embeds the required logic. In more complex cases, particularly in extending runners, we will rely on a plugin-architecture.

We'll continue to focus on **.NET development**. Testing non-.NET apps through tests written in a .NET language is an acceptable use of NUnit, but we won't give high priority to features that are needed only for that purpose.

We'll remain **language neutral**. We'd like to work with **any** supported .NET languages. We currently support C#, VB.NET, C++ and F#. We will support other languages where people ask for it, particularly if they are able to pitch in and help.

We'll remain **platform-neutral** and will **add more CLI platforms** as needed. We currently support the **NET Framework**, **.NET Core** and **Mono**. NUnit already allows running tests under different runtime platforms by use of a command-line option or by selecting an option in the Gui.

We will continue to be **IDE-neutral**. We'll continue to ship releases that run outside any IDE in order to reach as many people as possible. IDE-specific features - such as those now present for Visual Studio - will remain user-selectable and off by default. Any major IDE integration package - such as plugins or addins - will be packaged separately.

We will become more **usable by other programs**. We'd like to make it easy for other software to run tests programmatically using NUnit. To that end, we provide **standard interfaces** that make it easy for people to write their own clients. We can't guarantee that those interfaces will never change, but we'll make an effort to keep them reasonably stable.

We will improve our ability to **work with other open source tools** for .NET. This includes mock object frameworks, windows and web forms testers, Visual Studio addins, etc. We'll work with others to provide integrated installs of NUnit in combination with other tools. Some tools - those we use in our own tests - will be packaged with NUnit in the future.
