# Your project is already legacy, you just don't know it yet

## Intro

* Ju Liu **@arkham**
* Matteo Giaccone **@Mat_Jack1**

* weLaika **dev.welaika.com**
* Cantiere Creativo **cantierecreativo.net**

## Definition of legacy

* Legacy, noun, *something left or handed down by a predecessor*
* Legacy, Heritage, Eredità: something good!

## Legacy software

* A software which is no longer mantained or supported
* Legacy system, legacy architecture, legacy code: not so good!

## Developers hate legacy

Working with legacy software is always:

* Getting your hands dirty with unclear, obfuscated mess, aka **A Big Ball of Mud**
* Everytime you touch something, the whole application breaks down, so you can't make changes confidently.

## The Developers Motto

** The old code is a huge mess, we need to rewrite it **

## Why does this happen?

Developers love to write code.

Developers hate to read code.

## The Fundamental Law of Software

** It’s harder to read code than to write it **

## Legacy is Good

Legacy code has been used.

Legacy code has been tested.

A lot of bugs have been found, and they were fixed.

## Code does not Rust

Code doesn't get worse because it gets older.

## The value of Software

Software is valuable because it solves problems. Most of these problems are
hard.

Every project which is valuable and lasts will eventually become legacy.

And your project too.

## Scenario

You are managing a healthy project, along with a seasoned developer.

You fully embraced the Agile Way™ with standup sessions, sprint plannings, TDD, continuos integration, etc.

The developer is pushing features like crazy, the client is happy, you are happy.

## Developer Runaway

Google decides to hire your developer.

He's leaving next week.

## What do you do?

1. You panic
2. You search for a new developer

## The Bad News, Pt I

You find a new developer: he is a junior developer, he seems moderately skilled and he is very excited to join your project.

After a week of work, he complains that:

* The code is too complex to understand
* Features can't be added that easily
* Tests keep breaking all the time for misterious reasons

## The Bad News, Pt II

You find a new developer: he is a senior developer, he seems very skilled and he is very excited to join your project.

After a week of work, he complains that:

* The code quality is too low
* Features can't be added that easily
* The test architecture is horrible and need to be re-written.


## Why does this happen?

If you focus on "working software", you only care if the software works:

* if it works, it's good
* if it doesn't, it's bad

The risk is that you lose the vision on the quality of your product.

## From working software to better software

Software has intrinsic, measurable defects:

* Complexity
* Duplication
* File Churn
* Test Coverage

These metrics aren't 100% accurate, but they introduce measurable data that we can analyze

## Code metrics

* SonarQube (aka Sonar), C/C++/Java/Python
* Code Climate, Ruby/Javascript
* Scrutinizer CI, PHP

Aggiungere un po' di screenshot

## Why are these useful?

They give you a easy to read, hard to miss indication of the health of your
project. After each commit you get a notice:

* *A -> B* Paperclip::Storage::Filesystem has gotten worse
* *B -> A* Paperclip::ClassMethods has improved.

## Judging quality

These tools help judging two different projects.

Let's say we are looking for a file uploader in rails.

* thoughtbot/paperclip has a GPA of 3.07
* jnicklas/carrierwave has a GPA of 3.57
* markevans/dragonfly  has a GPA of 3.7
* bbenezech/papermill  has a GPA of 0.21

## Roundup

Every software which brings value lasts in time.

If your projects succeed, they will become legacy too.

Don't worry, just keep them in good health.

