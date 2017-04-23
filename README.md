# Assignment-15.2

1.Explain the working and the differences between Maven, Gradle and SBT in detail.

Ans.SBT
SBT is very simple and it is focused on Scala it relies on Ivy for dependency management.

Maven
Maven it's a great build tool and it enables to control the entire software lifecycle with XML files. Using the Project Object Model you can intercept all points of the software lifecycle from compile to test, packaging and deploy. Maven has it's own dependency manager. Issue in Maven is the XML syntax, writing a POM can be annoying and too much expensive.

We can not compare Gradle with Maven (or SBT). Gradle is built on top of Maven, Ant and Ivy. It uses Maven repositories. Gradle doesn't use XML, it's a polyglot build tool. It combines the Ant API with the Groovy language to enable developers to write a build script with an intuitive DSL. With a few lines of code you can write a Gradle build script that can do the same things that Maven can do. With Gradle you can define your own task with the Groovy language and intercept programmatically your build execution. This functional approach is not for all developers,infact Maven it's good if you don't want this behavior in your build environment. Both Maven and Gradle have plugins to integrate your build with technologies used in your projects.

Maven
Maven was released in 2004. Its goal was to improve upon some of the problems developers were facing when using Ant.
Maven continues using XML as the format to write build specification. However, structure is diametrically different. While Ant requires developers to write all the commands that lead to the successful execution of some task, Maven relies on conventions and provides the available targets (goals) that can be invoked. As the additional, and probably most important addition, Maven introduced the ability to download dependencies over the network (later on adopted by Ant through Ivy). That in itself revolutionized the way we deliver software.


