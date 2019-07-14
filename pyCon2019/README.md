#Python is NOT easy - Lessons from SymPy's codebase

### Slides are currently in their draft version
### Please see the ipynb for examples, explanations and walkthroughs

Python is generally considered an easy to use language and generally speaking, does not surprise the user and is known for being predictable. Even when one uses libraries in Python, one can generally predict how the library functions would behave or even be named with some experience. 

This does not hold true when one actually tries to contribute to said libraries. A new contributor to open source projects often has to decode the codebase that has been written in Python but does not behave in ways that they have learned Python does.

This talk introduces a few such features (listed below), reasons about why these features are in-fact good, fantastic even, and tries to enable the new contributor to not be surprised by them and help them not come to a point where they would say, "Python is NOT easy".

Topics in the talk:

- Inheritance in Python

  Python allows multiple inheritance and has a *kinda* complex system for figuring out where a function's parent is. 

  - Metaclasses

    Classes that modify other classes without really telling you

  - Decorators
    @i_will_change_your_class.before_its_attached_to_a_name
  - Mixin Classes (A Convention)
    Classes that allow different classes to behave the same in specific cases

- Slots - Classes are not classes anymore
- Other "tiny" features
  - Functions are objects and *Vice-Versa*

