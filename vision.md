Stated simply...

**NUnit 3 is a world-class platform for individuals and teams using a test-based approach to .NET software development.**

On this page, we articulate the details of what that statement means to us. We don't specify features here - but try to provide set of guidelines that will help us when we are considering what features to add.

> Note that our vision as outlined here is substantially changed from the earlier vision of NUnit as a framework. Some of the changes are explained in more detail below. You can read the [[Original Vision]] if you would like to compare them directly.

### A Bit More Detail

NUnit began as a relatively simple **framework** with a console-based runner. A Gui runner was added for version 2.0 along with a long list of features, but it remained essentially a test framework with a few runners. With NUnit 3.0, we began expanding the role of NUnit so that it provides a broader platform for test-based development.

Such an approach puts increased demands on NUnit as a tool. It must support a number of different kinds of tests, allow for alternative approaches to testing and be usable by team members in a variety of roles.

#### Kinds of Tests

NUnit began as a **unit testing** framework. In later releases of NUnit 2 we decided to support use of NUnit for integration and acceptance testing, but only to the extent that this support didn't interfere with our primary goal. With NUnit 3, we plan to fully support integration, acceptance, performance and other types of tests in addition to unit tests.

#### Approaches to Testing

All of us are pretty excited about **Test-Driven Development**. However, we recognize that many programmers are either not yet using TDD or are working on legacy projects for which TDD is not even possible. NUnit 3 supports various alternative approaches, including generation of tests for existing code bases.

#### Developer versus Programmer

NUnit has always been viewed primarily as a tool for **programmers**. With NUnit 3, we want to recognize and fulfill the needs of programmers, testers, interaction designers, web designers, data base specialists, customers, managers and any other members of the **whole team**.

#### NUnit as a Platform

All of this is a pretty tall order. We expect to satisfy many of these needs directly, but it would be impossible to satisfy - or even predict - all of them. By treating NUnit as a **platform**, we will make it possible for individuals, teams or third parties to add support for activities and approaches that are not provided out of the box.

### Future Directions

Taking the above into account along with the requests we've received from users and our own interests, here are some directions we expect the next few releases of NUnit to take

We'll continue to expand the available choices regarding **where tests are run**. We now support use of multiple AppDomains as well as separate processes. We expect to expand this to cover test execution under a particular subsystem or on a separate machine.

**NUnit will be extensible.** We can't do everything for everybody but we will make it reasonably easy to extend NUnit. In many cases, users will be able to implement a plugin that provides a special feature outside of our scope by simply creating a new attribute that embeds the required logic. In more complex cases, particularly in extending runners, we will rely on a plugin-architecture.

We'll continue to focus on **.NET development**. Testing non-.NET apps through tests written in a .NET language is an acceptable use of NUnit, but we won't give high priority to features that are needed only for that purpose.

We'll remain **language neutral**. We'd like to work with **any** supported .NET languages. We currently support C#, VB.NET, C++, J# and F#. We expect to add Iron Python and Iron Ruby and will support other languages where people ask for it, particularly if they are able to pitch in and help.

We'll remain **platform-neutral** and will **add more platforms**. When we use the term .NET, we don't only refer to MS.NET, but also to other ECMA-compliant implementations of the CLI. We currently support **MS.NET** and **Mono** and expect to add other platforms in the future. NUnit already allows running tests under different runtime platforms by use of a command-line option or by selecting an option in the Gui. We'll expand this to support running tests under the **compact framework** as well as **Silverlight**. We'll maintain separate download packages to support the different platforms, as we now do for Windows and Mono.

We will continue to be **IDE-neutral**. We'll continue to ship releases that run outside any IDE in order to reach as many people as possible. IDE-specific features - such as those now present for Visual Studio - will remain user-selectable and off by default. Any major IDE integration package - such as plugins or addins - will be packaged separately.

We will become more **usable by other programs**. We'd like to make it easy for other software to run tests programatically using NUnit. To that end, we will provide **standard interfaces** that make it easy for people to write their own clients. We can't guarantee that those interfaces will never change, but we'll make an effort to keep them reasonably stable.

NUnit will be **internationalized** and we'll work with those who want to provide **localized versions**.

We will improve our ability to **work with other open source tools** for .NET. This includes mock object frameworks, windows and web forms testers, Visual Studio addins, etc. We'll work with others to provide integrated installs of NUnit in combination with other tools. Some tools - those we use in our own tests - will be packaged with NUnit in the future.

