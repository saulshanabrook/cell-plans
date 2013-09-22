
# Background
having a cell phone plan is expensive. not only is it expensive, but
it is hard to find what plan offers the best deal considering your
needs. So why not make a web app to compare phone plans?

# Design
We need to be able to specify what we need and then see a comparison
of the different plans, so we can effectively look at the cost vs.
the quality of each option.

## Specifying our needs
There are a number of requirements we might have when looking for a cell
plan. We should support the most common first.

1. multiple devices. Each device should have:
   1. Domestic usage
      1. number of minutes
      2. number of texts
      3. amount of data
   2. type of phone
      1. basic vs smartphone
      2. type of smartphone
2. carrier


## Listing the competition
Once a user has specified what they want, we should list the possible
options, sorted by price.


# Implementation
since this is useful to the general public it should be a website.

it does need to by the end user, and really could be a single page
web app, completely static. that means that representation and data
storage must all be done with javascript.

I want to use [polymer](http://www.polymer-project.org/) as the
javascript framework, because it seems like it will be the future. From
their [FAQ](http://www.polymer-project.org/faq.html#why)

> Unlike some other frameworks before it, Polymer attempts to embrace
  HTML as much as possible by encouraging the use of custom element
  wherever possible. It includes a handful of independent polyfills
  for these emerging web standards (Custom Elements, Shadow DOM, etc.)
  that over time, diminish and ultimately disappear as browser vendors
  implement the native APIs.
