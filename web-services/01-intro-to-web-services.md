# A Whirl-Wind Tour of Web Services

### Projected Time
4 hours

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
- Some purveyors of web services.

### Specific Things To Teach
- White boarding architecture.
- The problems that web services solve.
- The types of solutions available.

### Materials

- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Google Cloud Platform](https://cloud.google.com)
- [Amazon Web Services](https://aws.amazon.com/)

### Mini Lesson: White Board Architecture Together

Consider the following problem:
__Marketing wants to track all new registratants and connect their information
to 1. a marketing database, and 2. a sales system. Product wants to be sure
that the performance of the registration is not impacted. Engineering is
concerned about these third party systems being unavailable. Marketing wants to
be sure that they do not loose any data.__

Given the requirements:
- how might go about describing this problem in technical terms?
- how would you draw this request?

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

- Thinking that everything should happen inside one app!
- Thinking that "web services" are for "dev-opsy" people.

### Guided Practice

Let's go through Google Cloud's Platform and identify the _problem_ each of
their services attempts do solve.

### Independent Practice

Go through Amazon's AWS on your own. See if you can identify the _problem_ each
service attempts to solve.

### Challenge

Consider another problem:
__


### Check for Understanding

Each group should go up to the whiteboard, summarize the problem of the
challenge, and draw out their solution using any or all of GCP or AWS.
