# object-oriented_design

A brief note for various aspects used in object-oriented design thinking

_This repository is made to refer as a short note in UML class, sequence, state diagrams.
Basic understanding is required to fully grasp the points given here.
This includes the few examples of UML class, sequence, state diagrams and questions with the answers
for the course, Object oriented design by university of Alberta in coursera online learning platform._

# A class diagram
is the main building block of object-oriented modeling. 
It is used for general conceptual modeling of the structure of the application,
and for detailed modeling translating the models into programming code

# A sequence diagram
models the interaction of objects in a single use case.
shows different parts of the system work in _sequence_ to get something done.

# A state diagram
is used to represent the condition of the system or part of 
the system at finite instances of time. It's a behavioral diagram 
and it represents the behavior using finite state transitions.

## Sequence Diagram Notation

- _Life Line Notation_
  - with **Object** element
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Sequence-diagram-Lifeline.png" alt="object element notation" width="200" height="200">
  - with **Actor** element
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/lifeline-with-an-actor-element-symbol.png" alt="actor element notation" width="200" height="200">
  - with **Entity** element
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Entity-Lifeline.png" alt="entity element notation" width="200" height="200">
  - with **Boundary** element
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Boundary-Lifeline.png" alt="boundary element notation" width="200" height="200">
  - with **Control** element
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Control-Lifeline.png" alt="control element notation" width="200" height="200">

- _Activation Bars_
- <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Sequence-Diagram-Activation-Bars.png" alt="activation bar" width="300" height="300">
  
- _Message Arrows_
  - **Synchronous** messages
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Sequence-Diagram-Activation-Bars.png" alt="synchronous messages" width="300" height="300">
  - **Asynchronous** messages
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Asynchronous-Message-example.png" alt="asynchronous messages" width="300" height="300">
  - **Return** messages
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Return-Message-Example.png" alt="return message" width="300" height="300">
  - **Participant Creation** messages
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Participant-creation-example.png" alt="participant creation messages" width="300" height="300">
  - **Participant Deductive** messeges
  - <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Participation-Destruction-Message.png" alt="participant deletion messages" width="300" height="300">
  - **Reflexive** messages
  - <img src="https://d3n817fwly711g.cloudfront.net/blog/wp-content/uploads/2017/01/Reflexive-message.png" alt="reflexive messages" width="300" height="300">
  
- _Comment_
- <img src="https://d3n817fwly711g.cloudfront.net/uploads/2017/01/Comment-object-example.png" alt="comment" width="200" height="200">
