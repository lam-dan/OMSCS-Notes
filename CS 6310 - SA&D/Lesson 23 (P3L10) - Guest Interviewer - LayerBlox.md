# Lesson 23

This lesson is primarily interviewing a chief architect from a company called LogicBlox. LogicBlox focuses on:

> Solving business problems with applications that evolve with business needs, in a unified environment with Big Data scale, spreadsheet flexibility, and advanced analytics.

The business model behind LogicBlox is SaaS (software as a service).

## LayerBlox

One of the novel ways LogicBlox has handled redundancy and enabled reusability in their software architecture is to have _LayerBloxs_ which takes care of commonly used services for various client applications. LayerBloxs accomplishes this by generating different variants of components using assembly specs and a reusable feature library. This is possible as LayerBloxs is based on feature-based design principles.

## References

Below are references used in building out LayerBlox:

- Don Batory: [Feature-Oriented Programming and the AHEAD Tool Suite.](https://gatech.instructure.com/courses/116212/files/13031401/download)
  Proceedings of the 26th International Conference on on Software Engineering, ICSE 2004, pp. 702-703.
- Don Batory and Sean O'Malley: [The Design and Implementation of Hierarchical Software Systems with Reusable Components.](https://gatech.instructure.com/courses/116212/files/13031583/download)
  ACM Transactions on Software Engineering and Methodology (TOSEM), 1(4):355-398, October, 1992.
- David L. Parnas: [Designing Software for Ease of Extension and Contraction.](https://gatech.instructure.com/courses/116212/files/13031585/download)
  IEEE Transactions on Software Engineering, SE-5(2):128-138, March, 1979.
- David L. Parnas: [On the Design and Development of Program Families.](https://gatech.instructure.com/courses/116212/files/13031397/download)
  IEEE Transactions on Software Engineering, SE-2(1):1-9, 1976.
- Yannis Smaragdakis and Don Batory: [Implementing Layered Designs with Mixin Layers.](https://gatech.instructure.com/courses/116212/files/13031399/download)
  Object-Oriented Programming, pp. 550-570.

## Implications And Advice

Advice from Kurt:

- Get good at data modeling the structure of data in a system on a conceptual level can pay dividends in the long run
- Using an algebraic approach to think about software composition (e.g., what are their properties, when are they useful, and how to use them to inspire designs)
- Knowing a body of related work when you start a new problem as in trying to relate your problem to a problem that has already been seen that you can heavily borrow from

##Quiz

Each refinement Is a generator that will generate a different way of implementing interfaces
True

An architect’s job may cover:
All of above

________ is quickly regenerated for some particular product or some particular set of products.
A on-demand forecaster


Based on the analysis to calculate demand, to forecast demand of products in the absence of any kind of promotional activity or any other kinds of events, special events that might cause spikes or troughs in demand. And that generates something called: 
A baseline forecaster

A baseline forecaster, a set of multipliers , a variant and an incremental forecaster are sub components that are used to create a batch.
False

A variance is based on customized requirements, and may not be used as often as a batch
True

A product line is a group of products that a company creates under a single brand. The products are similar and focus on the same market sector. 
True

LayerBlox is a software generator for generating different variants of products in the same product line.
True

Based on a separate set of algorithms that calculate incremental sales, an additional uplift from the base line when certain special events are in play(ex: a promotion) actually calculates: 
An incremental forecaster

An typical Application  of LayerBlox is Forecast Manager for sales, inventory, etc.
True

A refinement for incremental forecaster is parameterized by two different kinds of arguments, one is some component that implements _____.The other is some component that implements ______. And, when I apply this refinement to components of those suitable types, then I'll actually generate a new forecaster.
forecast interface, multipliers interface



