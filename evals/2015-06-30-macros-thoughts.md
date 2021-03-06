Thoughts on the (title) workshop --- Data
=========================================

**Luke**:

I thought it went well.  There weren't many questions/help needed by
the attendees, so that could a good thing.

I felt that the beginning with going over GitHub and explaining
everything on the slides took a bit too much time.  I would prefer we
get into coding quicker, and do explanations while doing the coding.
That way they get more application practice.

I would have liked more integration with git, but oh well.  :(

There were parts that I felt could have been sped up more, but at the
same time explained more.  I liked that you went through some of the
initial SAS code in detail and explained what it meant, but maybe what
we need to do is also include more detail about the basic structure of
SAS code (especially for those with *no* experience with SAS).  Later
on though, I noticed you repeated some things maybe a bit too much,
which (for better or worse) slowed things down and maybe made things a
bit confusing.

We might need to re-structure the macros lesson to include at least an
`%if ... %then ...` statement to show the usefulness of macros outside
of just making coding cleaner and easier.

You mentioned a few times about looping, but we never actually went
over loops.  Not sure how the learners felt, but that may have been
confusing.  I think next time we don't even mention the looping
feature of the multiple `y` variables when using `proc reg` or `proc
glm`... For beginners/novices, I think that feature may be a bit
confusing as to why SAS does that for the `y` variables for
(potentially) some `proc`s but not others (It doesn't work on `proc`s
that make use of multivariate analyses like partial least squares
regression, reduced rank regression, or factor analysis, nor will it
work on repeated measures ANOVA).

I realized that we both don't make much use of the stickies.  I think
that whenever we have a task they need to finish, to tell them to put
the stickies up when they are finished.

One thing I think we should incorporate more into is a 'learning
objective' or something at the very beginning.  As part of this
objective (doesn't need to be part of it), there should be something
concretely explaining a specific task this will accomplish or
something that will explain what we can do with this lesson.
Something to bring it back to reality and their analysis workflow,
rather than just a chance to teach.

**Daiva**:

I think this workshop went well. The pace felt quite slow for me, but I actually think that was good for the learners. They seemed to be able to follow along with the coding and did not seem to think things went slowly.

I think the overview of GitHub at the beginning was useful. There seemed to be a few roadblocks that learners faced when trying to do the GitHub assignment and we were able to clarify them. Even though this took some time, I think it was valuable. But, since we plan to teach Git + GitHub together in the future we will probably modify the lesson based on our experience with this run of the workshop. If we devote 2 weeks to Git + GitHub and learners are comfortable with that material then we can stay focused on macros in the macros lesson. 

I think creating a few different types of macro examples would be valuable for the next round. I basically just stuck with proc means and proc glm, but I will try to create examples for other tests as well (maybe proc logistic, proc freq, proc ttest).

**General**:

I agree with your comments about the sticky notes and learning objectives. Let's definitely incorporate those  ideas into the next round.
