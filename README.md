# MVF – a tiny Javascript framework

'MVF' stands for either 'Minimal Viable Framework' or 'Mostly Vanilla Framework'; take your pick. It consists of Javascript libraries and some tooling. It does as little as absolutely possible. If you are used to giant Javascript app frameworks, MVF is going to seem shockingly small and underpowered. This is by design.

In practice MVF is not so much a framework as it is a collection of related building blocks with a common 'design flavor' to them. In most cases you should use only those blocks you need. 

## Goals

* Simplify and automate pain points in [Vanilla.js](http://vanilla-js.com/) app developement 
	- Provide helpers and adjuncts for Vanilla.js, not wrappers

* Provide basic tooling without requiring Node.js and NPM
	- So, yeah, Python, got a problem with that?

* No external dependencies, outside of what is already available in modern browsers
	- None
	- Seriously, none at all; not even in the tooling
	
* Minimal internal dependencies
	- None, where possible

* Demonstrate the power of the [Actor Model](https://en.wikipedia.org/wiki/Actor_model) in Javascript
	- Provide a version of the [MVP Architecture](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter) using Actors for Views and Presenters

## Non-Goals

* Anything easily done with [Vanilla.js](http://vanilla-js.com/)

* Make MVF useful for anyone other than the person creating it