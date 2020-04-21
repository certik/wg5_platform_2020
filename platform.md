# Platform

The goal of Fortran is to provide a programming language for high performance
and technical computing which enables domain experts to program the latest
computers and HPC systems with maximum simplicity, portability, and performance,
while retaining compatibility with previous versions of the standard. The
original mission of Fortran should still be the mission today: enable
scientists, engineers, and other domain experts to write programs that naturally
express the mathematics and algorithms employed, are portable across HPC
systems, remain viable over decades of use, and extract a high percentage of
performance from the underlying hardware.

The role of the Fortran Standards Committee is to steward the language and
standardize new features that help move towards the language goal, while keeping
them backwards compatible so that older codes continue working.

The role of the WG5 Convenor is described in the INCITS Organization, Policies
and Procedures [document](http://www.incits.org/standards-information/policies),
in general the Convenor is "responsible for presiding at meetings and ensuring
that the program of work for that body is carried out in a prompt, efficient,
and effective manner".

## Summary

To summarize my platform at a high level, it breaks down into the following
bullet points:

* Release on a faster fixed schedule.
* Adopt rules and procedures.
* Prior compiler implementation of new features.
* Be community driven.
* Use meeting time efficiently.
* Improve meeting logistics.
* Enforce the ISO Code of Conduct.

Let me explain why each point is needed and my plan how to get it done as a WG5
convenor.

## Release on a faster fixed schedule

This is one of the most upvoted proposals at
our J3 proposals GitHub repository
(https://github.com/j3-fortran/fortran_proposals/issues/36). It
fixes two issues: significantly speeds up getting new features into the language
and at the same time prevents not well developed features from getting into the
language by allowing as much time as needed to discuss and refine each proposal
and only accept it when it is ready, without delaying a given standard release.
The WG5 convenor can change to this mode of operation and direct the J3
Committee to consider proposals submitted by the community at all times and to
help get proposals ready and ship a standard at a given date.

## Adopt rules and procedures

The J3 Committee currently does not have a written down set of rules how a new
proposal will get reviewed and eventually accepted or rejected. I submitted a
draft that many people upvoted of an example of such
rules (https://github.com/j3-fortran/fortran_proposals/issues/98),
which we can use as a starting point to discuss and agree on a set of
operating rules and procedures. The WG5 convenor can help facilitate this
process.

## Prior compiler implementation of new features

Traditionally the Fortran Committee standardizes many features that do not have
a prior compiler implementations and uses the Standard as a driving mechanism to
force compiler vendors to implement such features. I propose to reverse the
process and rather have a compiler implementation first. The common objection at
the Committee is that compiler vendors do not have the time and money to do so.
The long term solution is to have community compilers such as Flang and LFortran
which would allow such new features prototyping. The WG5 convenor should
encourage such efforts. We might not be able to achieve for every single feature
to be implemented first, but that is what we should strive for and we should
encourage and try to do that.

## Be community driven

The Committee should consider and discuss
proposals from
the Fortran community and focus on community priorities, as outlined by which
proposals the community wants to see
implemented (https://github.com/j3-fortran/fortran_proposals/issues?q=is\%3Aissue+is\%3Aopen+sort\%3Areactions-\%2B1-desc).
In addition each proposal that the Committee considers should have high support
at the J3 Github repository. The Committee should not consider proposals that
have not been discussed at GitHub ahead of time, or do not have wide support.
Furthermore the Committee should work more closely with the wider Fortran
community. This fixes a long standing issue that the wider Fortran community
sometimes feels (as evidenced by online posts and personal interaction) that the
Committee does not listen. I have already started fixing this issue by creating
the J3 GitHub repository and encouraging public participation in it, but as a
WG5 convenor I could help fix this faster by facilitating the dialog between the
Committee and the wider Fortran community. By coming from the outside community,
I have first hand understanding of the feelings and frustrations that Fortran
practitioners often feel, and at the same time by being on the Committee I
understand the background and history why the Committee sometimes operates the
way it does and I think I can help bring the two sides together to work as one
community on improving Fortran together and to improve the trust in each other.

## Use meeting time efficiently

Currently almost no work is being done between meetings, and then valuable
meeting time is used to develop new proposals from scratch and to have design
discussions. That is very inefficient. I propose to develop proposals between
meetings online at our J3 GitHub repository, discuss all the pros and cons
remotely and try to agree on a path forward and polish the proposals as much as
possible and also do initial review ahead of time. And use our in person meeting
time to focus on review and decision making. I have already been very successful
with getting the community to do a lot of work at our new J3 repository, and as
a WG5 convenor I would encourage even wider participation of both the community
and the Committee.

## Improve meeting logistics

Currently we meet in a small room that sometimes does not have enough chairs or
table space for all participants, does not have a projector and subcommittees
must meet in hotel rooms. Rather, our goal should be to have enough rooms for
both plenary and subcommittee meetings, have a projector and telecon equipment
available. As a WG5 convenor I would use my contacts in Industry, Academia and
National Labs to try to find an affordable facility that would meet our goals.

## Enforce the ISO Code of Conduct (CoC)

The CoC is a tool to ensure that discussions are healthy and open to everyone. I
have a lot of experience with running large open source communities and ensuring
that discussions always stay healthy, that there is no abusive behavior, and
that new participants feel safe to discuss ideas. As a WG5 convenor I would
enforce the CoC and ensure that unprofessional behavior is not tolerated at any
meeting.

## Note

Some of the above issues are specific to J3 Committee. However, sometimes the J3
and WG5 meetings are held together and furthermore, as a WG5 convenor, I would
work with the J3 leadership to help implement the above goals, as I outlined
above.
