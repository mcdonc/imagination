.. include:: <s5defs.txt>

A Failure of Imagination
========================

:Authors: Chris McDonough, Agendaless Consulting
:Date: 3/2014 PyCon

..  footer:: Chris McDonough, Agendaless Consulting

Who Am I
--------

- Bad Perl hacker until Python.  Came to Python via Zope in 1999.  Worked at
  Digital Creations (aka Zope Corporation) until 2003.  Now a consultant with
  Agendaless Consulting.

- Primary author of: Pyramid web framework, Supervisor UNIX process control
  system, Deform form system, Repoze collection of middleware, and other
  unmentionables.  Contributor to Zope, WebOb, and other OSS projects.

Premise
-------

- Most programming problems are a failure of the imagination of the developer.

Direction
---------

- I don't mean this in some sunshiney way either.  "All a developer needs
  to do is be more positive" is unfortunately bullshit.

- Instead, a developer often needs to be more pessimistic.

Testing
-------

- A developer often skimps on tests for a variety of reasons.

- "Takes too long".

- "I'll do it later."

- "My manager doesn't believe in testing."

You know these are excuses.  The real issue is a failure of imagination.

Testing (Cont'd)
----------------

- Imagine a world in which when someone reports a bug to you, your first
  reaction is skepticism.

- Imagine a world where you're not living in fear of a phone call from your
  operations guy, and instead he buys you beers every week.

- Imagine a world where bugs are caught before they make it into production or
  even staging.

Testing (Cont'd)
----------------

- Now, imagine a world where, on top of the code that executes when your system
  is in production, you have to write 2 or 3 times that amount of code to test
  the runtime code.

- That's right.  I am not joking.  You have to write your code.  Then you have
  to write that same amount of code again.  And then again.  And then maybe
  again.  You might find shortcuts and get the same level of confidence, but in
  my experience it's very rare.

Testing (Cont'd)
----------------

- You look pretty skeptical.  That's your lack of imagination, because writing
  2-3 times the amount of runtime code you have in order to test it is just
  what it takes to feel very confident in your code.

- Feeling confident in your code means understanding your code.  You don't
  understand it when you write it.  You only understand it when you read it,
  and testing all of it makes you read and comprehend all of it.  It also
  usually ends up with refactorings and API changes, because you realize just
  how terrible it was the first time you wrote it.

- Suck it up.

Hard Problems
-------------

- Imagine a world where you aren't powerless in the face of Hard Problems.

- Imagine a world where your value to your company and co-workers is many
  times what it is now.

- Imagine a world where you are tasked with more interesting problems.

Hard Problems (Cont'd)
----------------------

- Now, imagine a world where you are required to become intimate with the layer
  underneath the bottom-most layer you're comfortable with right now.

- Imagine a world where, upon encountering a bug in a library at that layer
  upon which your system depends, your first reaction is to attempt to
  reproduce it in isolation, and then fix it yourself.  Imagine that this is
  going to take approximately forever, as you learn new systems, and new
  concepts.

- Imagine that you will fail at this over and over and over again, and feel
  incredibly foolish and irritated for days, possibly weeks, maybe even months.

Hard Problems (Cont'd)
----------------------

- You look pretty skeptical.  That's your lack of imagination, because nobody
  is born an expert in anything nor does it necessarily "come easier" to
  certain people than others.  The knowledge that the developers you admire
  have didn't spring forth from the head of Zeus.  They worked at it hard.

- Some folks have more time on their hands than others, and you're busy.  But
  you also have *some* time on your hands.  Don't piss it away; instead, have
  some faith in yourself and try.  You'll be surprised at how much you actually
  know.  After a bit, you'll be even more surprised at how little other people
  know.

- Suck it up.

Repeatable Builds
-----------------

- Imagine a world where a new developer to a complex project can be spun up
  with a development environment in fewer than 20 minutes.

- Imagine a world where you don't have to keep doing the same things over and
  over again like a tolltaker, and instead you have more time to do interesting
  things.

- Imagine a world where releasing a new version of your code to production takes
  10 minutes rather than 2 days.

Repeatable Builds (Cont'd)
--------------------------

- Now imagine a world where you have to build everything.  Everything.  From
  scratch.  I don't just mean Python things.  I mean, like, even, sometimes,
  Postgres and Apache and other things that are traditionally "system"
  libraries.

- Imagine the pain of needing to do this for multiple platforms because you
  don't want to proscribe the systems that your developers use (Linux vs. Mac
  OS X vs. Windows or whatever), because it's a recipe for developer
  dissatisfaction.

Repeatable Builds (Cont'd)
--------------------------

- Imagine the pain of needing to replicate a build across many production
  systems that are entirely different than development systems.

- Imagine the pain of needing to *maintain* all of this forever and ever
  without allowing it to bitrot.

- Now, suck it up. It's what you need to do.  To think otherwise is a failure
  of imagination.  Repeatable builds pay for themselves over and over and over
  again.  You lose lots of time and money not creating them.

Design
------

- Imagine a world where you weren't ashamed to have someone else look at your
  codebase.

- Imagine a world where you could remember why you did that thing there.

- Imagine a world where you might be able to reuse something you wrote on that
  other project without cutting and pasting it in.

Design (Cont'd)
---------------

- Now imagine a world where, instead of asking yourself the question "what's
  the fastest way for me to get that data over *there* in front of this person
  over *here*", you instead need to ask yourself the question "what am I
  actually trying to do, and how can I make it durable".

- Imagine a world where, when you can't answer the question "what am I actually
  trying to do" sufficiently without self-deception, you don't write any code
  at all.

- Imagine that the answer to "how can I make it durable" is "spend an extra two
  days here" and you do it.

Relationships
-------------

- Imagine a world where people you needed information from were literally happy
  to answer your questions instead of expressionlessly staring at you and
  offering the least amount of information to you that will cause your
  departure.

- Imagine a world where your knowledge could be of value to more people, and
  those people offer you respect and gratitude.

Relationships (Cont'd)
----------------------

- Now imagine a world where your *last resort* is asking someone else a
  question that you can answer yourself with a little bit of research and
  trial-and-error.

- Imagine a world where you're blessed to be able to provide more answers than
  questions on a daily basis.

Relationships (Cont'd)
----------------------

- Ignorance is bliss.  It *sucks* to know things, because other people will
  generally lean on you to provide answers.  This will take a lot of time.

- It's also very good, because you become professionally more valuable.

- But it's a balancing act.  It's easy to become consumed and jaded.  You need
  to draw boundaries.

- Imagine a world where you're continually shocked by the behavior of others.

- Suck it up.  Be generous with the time you give to others, and parsimonious
  with the time you require from others.

