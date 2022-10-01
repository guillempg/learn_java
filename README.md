# Prerequisites
- Java SE: 
Oracle [releases](https://www.oracle.com/java/technologies/java-se-support-roadmap.html) new Java SE versions every 6 months, on March and September, but some of these are long-term supported versions.
Enterprises typically use these LTS versions, hopefully the latest available. As of this writing, the latest Java LTS version is Java 17,
which you have to download from [Oracle download's site](https://www.oracle.com/java/technologies/downloads/) and install.

- Integrated Development Environment (IDE):
This is a tool you'll use in your daily work as a developer. I've tried Eclipse, NetBeans, and IntelliJ Idea,
and I recommend you to [download IntelliJ Idea](https://www.jetbrains.com/idea/download/#section=linux), the community edition doesn't require paying a license to use it.

- Version control program (Git):
Git is a version control program developed by Linux Torvalds (Linux OS creator) which is commonly used to keep track of
source code versions. It can be downloaded [here](https://git-scm.com/). In that same website you can read (or download) an [ebook about 
Git](https://git-scm.com/book/en/v2), but I'd recommend first having a look at two common ways of working with Git:
  - [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow#:~:text=The%20core%20idea%20behind%20the,without%20disturbing%20the%20main%20codebase.) it's used frequently
  - [trunk based development](https://www.split.io/glossary/trunk-based-development/#:~:text=Trunk%2Dbased%20development%20(TBD),%2C%20the%20%E2%80%9Cmaster%20branch%E2%80%9D.) it's not used that often, but also worth knowing

# Java Virtual Machine (JVM), Java Runtime Environment (JRE), Java Development Kit (JDK), Java Standard Edition (SE) and JakartaEE
Java is a compiled language that, unlike C/C++ programs (which have to be compiled for a specific
CPU like x86_64 or arm64), runs in the Java Virtual Machine (JVM). Time ago, Java could be downloaded from Oracle as either the
Java Runtime Environment (JRE), which only comprised the JVM necessary to run Java compiled programs, or as the Java Development Kit (JDK) which
not only contains the JVM, but also the Java compiler as well as other tools.

Finally, Java programming language is a rich ecosystem, and there have been several tools/frameworks built on top of it, to ease development 
and deployment of enterprise applications, for instance JakartaEE (previously named JavaEE and even J2EE) or Spring

# Java learning paths
The Java ecosystem is wide, and there are many terms and concepts that can (and they did for me at the beginning) overwhelm
you. Before starting you journey, take a look at the image below, it maps concepts and skills common to developers and to Java:
![Java learning paths](images/Java_learning_paths.png)

I'd start with Java (start), get familiar with the [Java Language Specification (JLS)](https://docs.oracle.com/javase/specs/). 
The JLS is too "dry" to learn Java from, but Oracle has [tutorials for Java new joiners](
https://docs.oracle.com/javase/tutorial/tutorialLearningPaths.html#newtojava). 

If you're more into watching videos, [these ones are a first approach to it](https://testautomationu.applitools.com/java-programming-course/). 
If you're more into reading books, I'd recommend Cay Horstmann's 
Core Java books (there are two, first volume is the "Fundamentals", and volume 2 is the "Advanced"). But the best way to learn Java
is to write Java programs (TODO: add resources to simple Java program exercises).

When you start writing your first Java programs, use an IDE (Integrated Development Environment). I'd recommend IntelliJ Idea (the community edition
is free to use, if not, your local Java Users Group might help you get a license for it). It's not necessary to get Oracle's Certificate of professional
Programmer (OCP), but review the [list of topics](OracleCertTopics.md) that you would have to know in order to pass the certification exam, it's a good 
starting point on what are the most important things to learn from the Java Language Specification (JLS).

Once you knoThen follow up with Java (pro) and at the same time gain familiarity
with the other tools and processes: Version control with Git, Building with Gradle or Maven (you will have to work with
both of them, but I think Gradle might be easier to start with), and also the Team organization tools (Jira, Agile mindset,
code reviews, Pull requests, code style and static code analysis tools).












