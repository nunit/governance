# Original NUnit Vision

> **Note:** This is a copy of the original NUnit Vision document created for NUnit 2.4. It has been superceded by the [current vision document](https://github.com/nunit/governance/blob/master/vision.md).

## Stated simply...

##### NUnit is a unit testing framework for developers working with the .NET framework.

On this page, we articulate the details of what that statement means to us. We don't specify features here - see the NUnit Roadmap for that - but try to provide set of guidelines that will help us when we are considering what features to add.

### A Bit More Detail

NUnit began as a **unit testing framework** and that's still its primary role. Many people use NUnit for integration testing, acceptance testing, etc. We support this **_where it doesn't interfere_** with our primary goal. That is, if a feature enables acceptance testing but makes it harder to do unit testing, we won't implement it.

When we talk about unit testing, we use the term as it is used in XP and other agile development methods. This is different from its use in traditional QA. In particular, unit testing is done **by the programmer**. Testers may also want to use NUnit, but they are not our primary audience.

All of us are pretty excited about **Test-Driven Development**. However, we recognize that many programmers are not yet using TDD, but would like to write unit tests to run under NUnit. We support this use of NUnit, and will add features that are needed by this group, **_but not if the feature gets in the way_** of doing test-driven development with NUnit.

### Future Directions

Taking the above into account along with the requests we've received from users and our own interests, here are some directions we expect the next few releases of NUnit to take

We'll expand the available choices regarding **where tests are run**. For example, we may use multiple AppDomains or separate processes. Some tests may need to run under a particular subsystem or on a separate machine.

**NUnit will be extensible.** We can't do everything for everybody but we will make it reasonably easy to add plugins to NUnit. The use of plugins is our main strategy for dealing with feature requests falling outside the basic unit-testing orientation of NUnit. In many cases, users will be able to implement a plugin that provides a special feature outside of our scope.

We'll continue to focus on **.NET development**. Testing non-.NET apps through tests written in a .NET language is an acceptable use of NUnit, but we won't give high priority to features that are needed only for that purpose.

We'll remain **language neutral**. We'd like to work with any supported .NET languages. We will make special efforts to support C#, VB.NET, C++ and J#. We'll support other languages (e.g. Delphi, Python) where people ask for it, particularly if they are able to pitch in and help.

We'll remain **platform-neutral** and will **add more platforms**. When we use the term .NET, we don't only refer to MS.NET, but also to other ECMA-compliant implementations of the CLI. We currently support **MS.NET** and **Mono** and expect to add other platforms in the future. We'll support running tests under the **compact framework**. We'll maintain separate download packages to support the different platforms, as we now do for Windows and Mono.

We will continue to be **IDE-neutral**. We'll continue to ship releases that run outside any IDE in order to reach as many people as possible. IDE-specific features - such as those now present for Visual Studio - will remain user-selectable and off by default. Any major IDE integration package - such as plugins or addins - will be packaged separately.

We will become more **usable by other programs**. We'd like to make it easy for other software to run tests programmatically using NUnit. To that end, we will provide **standard interfaces** that make it easy for people to write their own clients. We can't guarantee that those interfaces will never change, but we'll make an effort to keep them reasonably stable.

NUnit will be **internationalized** and we'll work with those who want to provide **localized versions**.

We will improve our ability to **work with other open source tools** for .NET. This includes mock object frameworks, windows and web forms testers, Visual Studio addins, etc. We'll work with others to provide integrated installs of NUnit in combination with other tools. Some tools - those we use in our own tests - will be packaged with NUnit in the future.
