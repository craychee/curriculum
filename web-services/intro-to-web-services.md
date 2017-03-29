# A Whirl-Wind Tour of Web Services

### Projected Time
3 hours

### Motivation
Humans are often not the target of an application. Software engineering is
much more than curating content to be displayed in browsers. The exchange of
data across systems requires management of services, meaning its orchastration,
monitoring, event queuing, persistence, security, all things that are invisible
to the average consumer of the Internet.


### Objective
**Students will be able to**:
- Explain what is meant by "web services"
- Name some components of web services and the problems they solve

### Specific Things To Teach
- Things about the things
- More things about the things
	- This is a sub-thing about the things
- Even more things about the things
- Even more things about the things

### Materials

- [Pub/Sub](https://cloud.google.com/pubsub/docs/overview)
- [Understanding JSON-Schema](https://spacetelescope.github.io/understanding-json-schema/)

### Mini Lesson: White Board Architecture Together

Consider the following problem:
__Marketing wants to track all new registratants and connect their information
to 1. a marketing database, and 2. a sales system. Product wants to be sure
that the performance of the registration is not impacted. Engineering is
concerned about these third party systems being unavailable. Marketing wants to
be sure that they do not loose any data.__

Given the requirements, how might go about describing this problem in technical
terms?
How would you draw this request?

[There should be time for discussion and iteration on the whiteboard.]

We may eventually conclude:
- We need to send information about registrants outside of our app
- We need to persist the information in a queue somewhere
- We need to pull from that queue and send the information off to the marketing
  database and sales system.

Now that we have an architecture, what problems do we now need to solve?
[This should be done as a class.]

We may eventually get a list that looks like:
- A format to sent messages outside of our app
- A solution that can read out message and queue them
- A system that can read messages out the the queue and send them into another
  system

### Common Mistakes / Misconceptions

This is something that students might not realize or might assume at first.

Make sure they avoid this: thing


### Guided Practice

Have the students work with you as you do something.


### Independent Practice

Class does this thing themselves with specific additional items.


### Challenge

Students can try to do this other thing.


### Check for Understanding

Have students summarize to each other, make a cheat sheet, take a quiz, do an assignment, or something else that helps assess their understanding. 
