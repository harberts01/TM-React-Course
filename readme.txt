do the "Suggested Readings"?

What is React? is a library for building user interfaces

-unidirectional Dataflow
-compositions
-Explicit Mutations
-Jsut JavaScript

Compositions:

<Slider /> ; <Navbar /> ; <Date />
<Router /> ; <Map /> ; <Datepicker />
<Header /> ; <Calendar /> ; <Avatar />
<Carousel /> ; <Chart /> ; <Icon />

You build a large app with a bunch of small components.


Unidirectional Data Flow:

Instead of Event Handlers updating the DOM in react the event Handlers are all part of the state. Then React, Renders UI based off
of the state.

this.setState ({
    handle: 'xxxxxx',
    authed: true
});

React is Just JavaScript. A lot of the same methods can be used inside React. 


CODE>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>