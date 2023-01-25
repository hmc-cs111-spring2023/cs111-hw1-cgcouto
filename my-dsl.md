# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

The language is called MDL. It's really niche; the only thing I could find on it is [an IEEE conference paper from 2007](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4127225).

# Domain

_Describe the language's domain in five words._

Development of molecular dynamics approaches!

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

When a program in the DSL runs, it parses all of the details given through the core four functions (physical, approximations, output, and excecute) and runs a molecular dynamics simulation governed by all of those parameters!

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

I would say that this language definitely sits closer to the "purely" domain-specific side of the spectrum, because of how narrow its function is, and that users are significantly limited as to what structures they can use in their programs (no loops, conditionals, etc).

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

The language is an internal DSL because it heavily relies on Python syntax and would be recognized as valid Python code by a Python interpreter.

# Host language

_What language(s) was (were) used to implement the DSL?_

They used Python as well as some specialized C++ libraries.

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

It is made easier with this language because it automatically contains several common molecular dynamics libraries. This means that to test out a different simulation type, you might not need to hunt down a different package and get that working.

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

If a new type of molecular dynamics approach comes out in the literature, you're pretty much dependent on the developers of this DSL to implement that instead of pulling their code and implementing it yourself.
