
Is a Computer Science Degree Necessary?
***************************************

Written February 9th, 2014, published February
15th, 2016. [#what-have-you-been-doing-for-2-years]_

I get this question from time to time and I used to waffle on the
answer. That, I think, is just a symptom of not framing the question
clearly.

Let's disentangle some questions:

1. Is the learning that happens in a CS program necessary?

2. Is the diploma necessary?

3. Are there things you learn in a CS program that are difficult to learn in the field?

4. Conversely, are there things you learn in the field that are absent in the CS program?


**Is the learning that happens in a CS program necessary?**

It depends on what sort of programming you want to do. The thing about
software engineering is that the most common and visible of jobs
programmers get is web development. Web development is like
construction. The majority of things that are built are probably
residential, and usually the difficult bits are outsourced anyway. The
house builder doesn't design and build a custom boiler, for
instance. He gets something built by a specialist and plugs it into
the house via a well defined set of interfaces. Similarly, the web
developer is picking up the difficult pieces (an operating system,
database, even web framework), and assembling it using a well defined
set of interfaces. In fact, you'd probably get better at this sort of
engineering working in the field rather than sitting in a
classroom. [#MIT]_

But let's crank it up a notch and say that you're a homebuilder and
you get a job to build a 50 floor office tower. You'd probably have to
know more about physics, chemistry, mechanical engineering, not to
mention building codes, project management, inspection requirements,
and all the other meta stuff that goes into a substantial engineering
project. That's the analogy I'd like to make to having a CS degree. A
web developer moving on to building a highly available distributed
database is going to require both theory and practical knowledge not
found in that 90% of development jobs. School is a finely tuned
instrument for pushing theory to poor souls.


**Is the diploma necessary?**

That's an easier one to answer. If you're doing research, most
likely. In that situation, it's important to have a broad view of the
field, because you can't spend time inventing things other people
already invented, and you have to build on results other people have
discovered. And like I said earlier, school is a finely tuned
instrument for pushing theory.

For everything else, you probably don't need the diploma. In fact,
startup land has gotten very good at ignoring it. Why is that?

First off, for most of software development, that 90%, a few years of
experience far outweighs what you do in school. As an interview
question, I used to ask candidates to estimate the amount of time
they'd spent coding or thinking about code. What people do in their
first year or two out of school quickly outpaces all of what they did
their entire lives leading up to that point. Programming, for most
people, is essentially a side hobby up until the first full time
job. So, if you're hiring for that 90%, you probably shouldn't care
about the degree.

Though it does tell you some useful things. If a candidate went to a
top notch school, nepotism aside, you can probably infer that
candidate has the capability to focus and get good grades, ie the
ability to do what is expected. If the candidate did well in a top
notch school, then you can probably infer they know many potentially
useful CS topics, and were able to adapt to a higher level of
expectations.

But insisting on a top notch school with top notch grades precludes
some particularly large classes of valuable programmers -- those who
simply don't care to appease others, are unconventional in their
thought and beliefs, or focus so closely on computers that they fail
in other areas. You probably want some of these folk on staff.

The days of "our startup consists of all CS PhDs!" being a selling
point are long gone.


**Are there things in a CS program that are difficult to learn in the
field?**

Absolutely. You can say you know a lot about an operating system, but
unless you took an OS class in school, you probably have never
actually implemented one. The experience of writing parts of an OS are
key in truly understanding how it works and what you can expect from
it in the field. It's similar for programming languages. You don't
truly learn about your arguably most important tool without having to
implement a compiler or interpreter.

Data structures that are not already baked directly into a language
are difficult to learn about if you don't already know of their
existence. A good grasp of theory helps when looking for more esoteric
techniques others may have already discovered.

Another thing that should not be underestimated is the amount of
feedback you get while in school. The classes are designed to tell you
if you're wrong about something quickly. It's very easy to find a job
where you write code that nobody else sees. Not everybody does code
reviews, especially really small startups. So there's often times
little feedback, and without a feedback loop, it's difficult to get
better.


**Are there things you learn in the field that are absent in the CS
program?**

Absolutely. How to engineer software, for one. Classroom projects
usually don't live for more than a semester, and much of real world
engineering has to do with maintaining systems that exist past the
time at which any particular engineer stops working on it. I have
never heard of a class that directly addresses this issue.

When I was in school, I signed up for a class with the unfortunately
broad title of "Software Engineering." The professor got up at the
podium and actually said, "I'm not really sure what I'm supposed to
teach you guys this semester." I dropped the class.

This is what we should have learned:

- Coexisting peacefully with peers using a source control system.

- Communicating clearly through documentation, bug trackers, and
  wikis.

- Effective testing and automation.

- Development methodologies, project planning.

- Design patterns, techniques for structuring large systems from small
  components.

- How to work with a large code base written by people you have no
  access to.

- Using debugging tools and analyzing log files.

That last one is interesting. At a previous place I worked, we would
give candidates an nginx log file and ask basic questions such as
"what is the most common path?" or "what percentage of requests are
returning 40x errors?" Newly minted graduates, even from prestigious
CS programs, would almost always struggle with those
questions. Candidates who mustered correct answers often did so by
writing a Python or Ruby program using regex. Very few knew how to use
grep, awk, and sort.


**So, do I need a CS degree or what?**

I still can't definitely answer that question. But another way of
looking at it is, what's the downside? You learn a lot about how to
approach problems -- generally good for the brain -- at the cost of a
few years and some cash. You have a wider selection of programming
jobs to pick from, most of which will probably pay more (that
distributed systems specialist will command a higher salary than a run
of the mill backend engineer), which lets you recoup that lost tuition
money fairly quickly. It's a pretty reasonable investment of money and
time, assuming you can get a spot in a decent curriculum. But if you
can't stand boring lectures, or you don't believe the rest of the
college experience is worthwhile, by all means, skip the degree.

The harder question is, what constitutes a decent curriculum that
prepares you for that 10%? I think one common characteristic of all of
them is that they organize around a breadth of topics and don't worry
so much about the details. Berkeley, for instance, has no required
class that teaches you how to program in a particular language. At the
opposite end of the spectrum, I have yet to encounter someone with
only a General Assembly / Skillshare / Codecademy / OpenCourseWare
filled resume who is very good at programming. I'm not pessimistic
about those curriculums or online learning yet. I simply have yet to
see that pan out, so maybe that's something to look out for in 2014.

It might be possible to squish the right curriculum into a year or so
of intensive study. And this could be done, perhaps, General Assembly
style, or online like Codecademy. It's ambitious, but it doesn't seem
entirely outlandish to me, at least as I type this. I'll close with
what I think my dream curriculum would be, completed in four quarters
of full time study.

1. Core data structures, everything implemented in the Python standard
   library for example.

2. Intro level algorithms, topics drawn from Knuth volumes 1 - 3.

3. Survey treatment of assorted topics from operating systems,
   programming languages, databases, networking, randomized
   algorithms, and machine learning.

4. "Software engineering" a la the topics I listed above, requiring
   building and shipping a large real world project. I imagine this
   would be a several month project involving a multi person group.

.. [#what-have-you-been-doing-for-2-years] Yes, it took me over 2
   years to publish this because I was trying to write the best static
   site generator. Those who can build their own tools are doomed to
   build their own tools.

.. [#MIT] MIT `switched their famous 6.001 curriculum
   <https://groups.google.com/forum/#!msg/comp.lang.lisp/Tmon3cXr8xM/EJ1nIS5melEJ>`_
   for this reason, so maybe it *can* be done in academia.
