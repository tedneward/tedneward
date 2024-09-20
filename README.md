# Ted Neward
Hello! Welcome to my GitHub. I've got a bunch of things up here, many of which public (and more than a few private), reflecting the fact that I've always got my hands in five or six or twelve or twenty different projects and ideas at a time. :-)

If you'd like to see a more "professional" presence on the Interwebs, try [my professional site](https://www.newardassociates.com) (which is actually a JBake-based static site), and if you're looking for more of a bloggish kind of thing, check out [my blog there](https://blogs.newardassociates.com). Someday I will revive my "personal" website and blog at tedneward.com, but that's low on the backlog right now.

### Pronouns: he, him, his
Pronouns matter to people, because they matter to people. It's the simplest of courtesies to refer to someone as they wish to be referred. If you are somehow triggered by somebody asking you to show them courtesy the way they wish, then you and I are really not going to get along. *Caveat emptor.*

### I'm currently working on ...
... a number of different projects outside of work. 

[Azgaarnoth](https://github.com/tedneward/Azgaarnoth) is a world for the players (buddies from college lo these many years ago) in my D&D 5e game, and probably won't be much help to anyone unless you're in that game--unless you want to use it as a template or something for your own games. *shrug* That's up to you. Fork away.

The official [Architectural Katas](http://www.architecturalkatas.com) repositories are here: one for the [katas themselves in raw form](https://github.com/tedneward/ArchKatas), one for the [web client](https://github.com/tedneward/ArchKatasCode), and one for a [Katas CLI](https://github.com/tedneward/ArchKatasCLI). Hopefully this makes it easier for people to suggest some new kata ideas (in the form of a pull request, of course).

I just recently made public my [XML-and-Markdown slide system](https://github.com/tedneward/pptbuilder), which is a v2 of a tool I originally built over a decade ago in F# using Office Automation to drive PowerPoint; the new version uses Apache POI to write the office XML format directly, which is a lot faster and (I expect) a lot more CI/CD'able. It can currently generate either PPTs or HTML/Slidy formats, and I have it in a CI/CD (GitHub Action-based) pipeline from my private presentation repo, with the PPTXs and HTMLs on a web-accessible storage site. (I call it that because the domain, slides.newardassociates.com, isn't really a website on its own, just a static storage bucket for all the PPTXs and HTML. You can certainly browse to it, but there's no "index" pages to help you find anything--the links are all on my professional site, under "Presentations".)

Another is [my collection of links and pages for research purposes](https://research.tedneward.com), which is another JBake-based static-generated site from the [repo](https://github.com/tedneward/Research). It's a pretty random collection, and I'm generally always adding stuff to it. It's public, feel free to fork it, and if you find a better way to organize it or find a whole slew of new topics you think I'd like, feel free to set up a PR for it. (Honestly, I don't know that it's of any use to anyone but me, but hey, you never know.)

There's a few "working labs" kind of project repos, which I use for conference workshops and the like:

* [Angular](https://github.com/tedneward/AngularLabs)
* [React](https://github.com/tedneward/ReactLabs)
* [Vue](https://github.com/tedneward/VueLabs)
* [Virtual Machine Implementation](https://github.com/tedneward/Workshop-VMImpl)

... none of which are guaranteed to make much sense without having taking the workshop, but you're welcome to explore anyway. Note that many (if not all) of them use a branch-based "step" model, so while the easiest way to do the workshop is to start on "main" and just do each step in that branch, if you want or need to fast-forward (or reset) to the start of a particular step, you can check out "step*n*begin" to start step *n*. There's a corresponding "step*n*end" branch to show you my solution. 

### Demos
I've recently been putting all the demo code that goes into my presentations into GitHub repositories and referencing the salient parts from the presentations (via HTTP references). Those repositories are all going to be prefixed by "Demo-", and many of them have "{{ BEGIN ... }}" and "{{ END }}" comments in the code; those are my markers for extracting snippets into slides.

### UW Homework Assignments
If you're one of my UW students, here's a partial list of the homework assignments for the various courses I've taught. If you're not one of my UW students, maybe you want to take a crack at one or more of them, just for funsies. :-)

***INFO 314 (Networking and Distributed Systems)***

* http://github.com/tedneward/INFO314-SocketClient
* http://github.com/tedneward/INFO314-QOTDServer
* http://github.com/tedneward/INFO314-UDPChat
* http://github.com/tedneward/INFO314-HTTPServer
* http://github.com/tedneward/INFO314-Servlets
* http://github.com/tedneward/INFO314-NATS
* http://github.com/tedneward/INFO314-TicTacToeRFC
* http://github.com/tedneward/INFO314-XMLRPC
* http://github.com/tedneward/INFO314-RMIByHand
* http://github.com/tedneward/INFO314-TLSByHand

Python or Java is the assumed language for these assignments, though there's nothing Python- or Java-specific in here (aside from the Servlets assignment, which is clearly and firmly Java-only).

***INFO 330 (Databases)***

* http://github.com/tedneward/INFO330-ExploringRelations1
* http://github.com/tedneward/INFO330-ExploringRelations2
* http://github.com/tedneward/INFO330-CreatingRelations1
* http://github.com/tedneward/INFO330-CreatingRelations2
* http://github.com/tedneward/INFO330-ExploringXML
* http://github.com/tedneward/INFO330-ExploringDocDBs
* http://github.com/tedneward/INFO330-AccessingDatabases

These use SQLite for the relational assignments, and Mongo for the DocDB assignment. Python or Java is the assumed language for the AccessingDatabases assignment.

***INFO 448 (Android)***

* http://github.com/tedneward/INFO448-KotlinBasics
* http://github.com/tedneward/INFO448-KotlinAdvanced
* http://github.com/tedneward/INFO448-HelloAndroid
* http://github.com/tedneward/INFO448-ActivitySpy

***INFO 449 (iOS)***

* http://github.com/tedneward/INFO449-SwiftSimpleCalc
* http://github.com/tedneward/INFO449-SwiftComplexCalc
* http://github.com/tedneward/INFO449-SwiftStore

There's a more than a few other kinds of projects in here, most of which are probably horribly out of date and should be deleted, or are forks of other people's/orgs' projects that I wanted to hold a copy of in case they got deleted at some point.

### I'm currently learning ...
... a long list of different things that I wouldn't even begin to try to list out here. Collectively, it's a list of "how to implement languages", "how to implement games", "how to implement virtual machines" (like the JVM or CLR), "how to build a database", and some other various development tools. I'm deeply curious about the intersection of programming language and storage, though, and I'm tinkering with a few ideas there.

### Ask me about ...
... whatever comes to mind?

### How to reach me ...
You can always [email](mailto:ted@tedneward.com), [tweet](https://twitter.com/tedneward), [LinkedIn](https://www.linkedin.com/in/tedneward/), and if that doesn't give you enough options I suppose you could always [Google](https://lmgtfy.com/?q=ted+neward) me and see what comes up.

### Fun fact:
I don't have a degree in Computer Science, and in fact I maintain that my liberal arts degree (International Relations) prepared me better for a career in development and programming than any CompSci degree program I've ever seen. (And I am fully prepared to defend this position--to die on this hill, so to speak.)
