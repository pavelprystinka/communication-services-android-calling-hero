# Java vs Kotlin for Android development

* Status: proposed <!-- optional -->
* Deciders: <!-- optional -->
* Date:  <!-- optional -->

Technical Story: https://skype.visualstudio.com/SPOOL/_workitems/edit/2408674 <!-- optional -->

## Context and Problem Statement

There two widely adopted languages for Android development.

## Decision Drivers <!-- optional -->

* Reach more Android developers by using language they prefer, rather then language they know
* Future proof language for development Microsoft applications and SDKs for Android

## Considered Options

* Java
* Kotlin

## Decision Outcome

Chosen option: "", because...

### Positive Consequences <!-- optional -->

* [e.g., improvement of quality attribute satisfaction, follow-up decisions required, …]
* …

### Negative Consequences <!-- optional -->

* [e.g., compromising quality attribute, follow-up decisions required, …]
* …

## Pros and Cons of the Options <!-- optional -->

### Java

#### Pros

* Time proven
* Existing development resources who knows Java


### Kotlin

#### Pros

-	[Kotlin is the preferred language for Android development.](https://techcrunch.com/2019/05/07/kotlin-is-now-googles-preferred-language-for-android-app-development/)
-	[Currently over 60% of Android developers use Kotlin.](https://developer.android.com/kotlin)
-	Kotlin is what most of the companies ask for these days -> better for hiring.
-	Most of the most popular and important apps out there are written in Kotlin such as: Slack, Lyft, Evernote, Square Cash, Pinterest, Airbnb, Twitter, Netflix, and many of Google apps like Google Drive, Google Photos, etc.
-	[The language is expressive and concise](https://kotlinlang.org/docs/comparison-to-java.html#what-kotlin-has-that-java-does-not) -> you will write less code
-	Your code will be safer -> Kotlin provides null safety mechanisms.
-	Kotlin is 100% interoperable with Java, so you will be able to use any new library written in Kotlin but also libraries written in Java. If you are going to build a SDK, it will go also in that direction, your Kotlin SDK will work perfect with apps written in Java.
-	Structured concurrency -> Kotlin has coroutines that will help you to write better and safer concurrent code.
-	There are tons of Kotlin well written docs and codelabs for you ad your team to learn (and know what? Kotlin is suuuuuper easy to pick up!).
-	Android Studio is optimized for Kotlin, providing first-class support for the language.
-	Google and the Android team is fully committed to Kotlin. A proof of that is that they declared it as the preferred language for writing apps but also new libraries that they write in Kotlin, all the new learning material and samples they write are in Kotlin, etc.
-	In terms of Kotlin at **Microsoft**, we also embrace Kotlin. New apps and sdks are mostly written in Kotlin (e.g. Family Safety app, Surface Duo SDK, Github for Android), and apps that have been out there for long, developers write new code in Kotlin (e.g. Yammer, Msft To-do, OneNote, Teams, FluentUI, etc.)
-	And a very important one: Kotlin is fun!! You will enjoy while writing Kotlin code will you will be able to ship also safer, more concise and better code :)

#### Cons

- Kotlin stdlib adds an extra 750KB. It is mitigated if application is already using Kotlin.
- Devs need to learn Kotlin. Get a crash course on language (a few hours) is good enough to read code and write code with some cheat sheet. Will take a bit longer to master.

#### Notes

Code style check enforce: ktlint - enforces the official Jetbrains style guide and the Google Android style guide. Topic is discussed [here](https://teams.microsoft.com/l/message/19:8b8a303496dc4b509ee2a476775b26ed@thread.skype/1593014661883?tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47&groupId=405885d7-7566-4fd8-ab74-09b2e641d007&parentMessageId=1593014661883&teamName=Android%20%40Microsoft&channelName=Kotlin&createdTime=1593014661883)

<!-- markdownlint-disable-file MD013 -->
