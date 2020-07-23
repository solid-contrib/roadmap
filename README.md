# Roadmap

The Solid roadmap explains the upcoming plans and needs of the various parties involved in implementing Solid. Read more about how to contribute to the roadmap [here](https://github.com/solid/process/issues/218). 

The [Solid specification project board](https://github.com/solid/specification/projects/1) is the best place to keep up to date on how Solid development is evolving and what is in the pipeline. The Solid roadmap is not the place to read about Solid development however, the roadmap is a place to read about implementation of Solid. 

# Dogfooding 

Solid properties cover tools, systems, and services used for advancing the Solid. The Solid properties are currently maintained using third party software that is not per say Solid compatible. 

The Dogfooding milestone is aimed at transforming the Solid properties to use Solid compatible software where possible as well as advance solidproject.org content for developers. 

Items that need to transformed into Solid compatible software include: 
* [Host solidproject.org on a Solid server](https://github.com/solid/solidproject.org/projects/1#card-41337384)
* [Solid listings on solidproject.org should be in RDF](https://github.com/solid/solidproject.org/projects/1#card-41337497)
* [Represent elements related to solid/process in RDF](https://github.com/solid/process/projects/1#card-41210779) 
* Many more items of column of [solidproject.org kanban board](https://github.com/solid/solidproject.org/projects/1) called “to do once there are technical resources”   

Here is a [description of the scope of work and profile of the individual needed to build the dogfood Solid on Solid properties](https://github.com/solid/roadmap/blob/master/dogfooding.med). 

There are several apps that need to be build as Solid compatible apps that would be used by the Solid Team, each of which will need a scope of work and profile of indiviual who could execute the task: 
* Make a Solid Chat app including calling that is good enough to carry out the Solid specification development work 
* Make a Solid app for Solid World invites that allows users to RSVP, get a calendar invite, and an email reminder a few hours before the webinar 
* Make a Solid app for This Month in Solid newsletter 
* Solid GitHub

## Testing Solid 

The aim is to test if the Solid specification delivers interoperable Pod servers that are interoperable. The first phase of the test will be for technical interoperability the second phase of the test will be for usable interoperability. 

You can find the latest version of the [test suite here](https://github.com/solid/test-suite). Here is an [example of a finalised test suite](https://docs.google.com/document/d/1NYGBQoL5VYDTqpy_8LRADCqLyZtGnHSIl7OWueC_Wqw/edit#). 

### Methodology 

**Phase 1: Technical Interoperability**

*1A.  finalise a stable specification*
First, the Editors will need to deliver a stable version of the Solid specification. The important element of this stage is to get one document that is a complete version of the Solid specification. If there are known problems these should be recorded but it should not block the delivery of a Solid specification to be tested because the problems can be discussed in practice later on during this test. 

*1B.  Build a Solid test suite*
Secondly a Solid test suite will need to be written based on the final version of the specification. The specification will need to remain static while the test suite is being written. Here is a [description of the scope of work and profile of the individual needed to build the test suite](https://github.com/solid/roadmap/blob/master/test-suite.md). 

*1C. Interoperability PlugFest*
Third, there will be a three day interoperability plugfest workshop with the aim to test the Solid specification using the test suite against various Solid servers built by different teams. The aim of the PlugFest is to run the test suite on  various Solid servers to highlight any areas where these servers are not complying. Each area where there is non compliance will be an item on the agenda to find out if the non-compliance is due to the server, test suite, or specification. Resolutions for each will need to be agreed upon between the parties involved. 

*1D. Incorporate the Decisions During the PlugFest*
The Editors will be responsible for incorporating the decisions into the Solid Specification. The author of the Solid test suite will be responsible for incorporating the decisions into the test suite. The developers behind each Solid server implementation will be responsible for incorporating the decisions into the Solid servers they are building. 

**Phase 2: Usable Interoperability** 

*2A. Testing usability of Pods*
Find a group of fifty users, who will be referred to as testers, who are not familiar with Solid and use smartphones on a daily basis.

Record a profile of the tester including:
* Do you work online? If yes, what tasks in your work do you need to carry out online? 
* Do you use technology socially? If yes, describe which common activities and apps you use.  
* Do you bank online? 
* Do you regularly shop online? If yes, what kinds of shopping, for example, food, clothes, other? 
* Have you ever coded? If yes, what did you code and in what language? 
* Have you ever changed the data sharing or privacy settings of an app that you use? If yes, which app and what did you try and change?
* Have you ever built a website? If yes, how did you build the website? 

Each tester needs to complete the following task with one person guiding them through the instructions and the other recording how the test individual reacts. 

The task is as follows. 

* Register for an identity (A)
* Register for another identity (B) with another identity provider

* Register for an Pod (A) 
* Register for another Pod (B) with another Pod provider

* Use Pod (A) using Identity (A)
* Use Pod (A) using Identity (B)
* Use Pod (B) using Identity (A)
* Use Pod (B) using Identity (B)

If it is not possible for the tester to complete any of the steps, make a record describing why the task was not possible to complete including screenshots of any erroneous steps. 

### Results 

**Phase 1: Technical Interoperability**

* Tester 1 - pass/fail (if fail why?) 
* Tester 2 - pass/fail (if fail why?) 

**Phase 2: Usable Interoperability** 
Profiles of the Tester:
* Tester 1 - 
* Tester 2 - 

The testers have been categorised into groups: 
* Online user: uses technology socially 
* Regular online user:  works online, uses technology socially, banks or shops online
* Actively engaged online user: has coded, altered privacy settings or built a website

Task Completion by Testers: 

### Analysis

### Conclusion





