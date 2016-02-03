# An openscienceprize entry

These are the beginnings of an entry for
[openscienceprize.org](//openscienceprize.org). Join in if you are
interested!

Build the infrastructure required to create and publish scientific
output that is more than a simple, static document.

A toolbox that makes reusable science a first class citizen in the
academic workflow by being useful from day one of a research
project. Reusability as a side effect.


# Tech-y summary and principles

Combining ideas from mybinder, everware, thebe, github, docker,
travis, and zenodo. Useful for researchers from day one. Runs locally
on your laptop or lab's cluster. Provide a way to automate every
step. Opinionated. Helps setup structure of a research project. A
toolbox, not a framework. Most individual steps already have fantastic
solutions out there, people should use them! Final step: interactive,
re-mixable papers.

Read [the full proposal](proposal.md).


# Contributing

Everyone is welcome to contribute. Discussion happens in
[issues](https://github.com/betatim/openscienceprize/issues), and
changes are handled via [pull
requests](https://github.com/betatim/openscienceprize/pulls).

You can contribute by filing an issue on something you find unclear,
needs improving, is missing, is incorrect, or add an idea of your
own. Or directly create a pull request with your suggested edits.

As this is about creating a entry for the open science prize, creating
the entry should happen in the open as well. Licensing details and a
list of contributors can be found in [LICENSE](LICENSE).

Watch the repository - this way, you will get email notifications of
new conversations. You can do this by clicking on 'Watch' at the top
of the repository:

![Watching a repository](https://help.github.com/assets/images/help/notifications/watcher_picker.gif)


# Brain dump points

This is an unordered collection of thoughts. Feel free to add to it.

Build a tool that universities/labs/publishers can use to encourage
re-use of software and provide a completely new kind of research
article, one that is interactive!

* preserving and open access of data is becoming mainstream
* to make sense of data we need lots of documentation and experience
* one source of documentation and experience is the code used to
  analyse the data in the first place
* sharing code is not enough, code only makes sense in the environment
  it runs in
* so far very little effort on sharing code and its environment
* adding re-usability/re-producibility as an after thought does not
  work (misaligned incentives)
* make re-usability a waste product, provide tools that are useful to
  researchers while developing their analysis pipeline that produce
  re-usability as a side effect
* bit rot is everywhere, undetected bit rot is a disaster
* periodically and automatically run a subset of analyses to detect
  bit rot
* researchers use very diverse set of tools, not interested in
  changing them
* need a flexible system that allows composing
* machine readable environment and entry point allow for completely
  new kinds of scholarly communication (-> interactive articles)
* simple syste that can be setup at universities or labs or publishers
* lots of problems already solved (sharing -> git(hub), workflow ->
  make, snakemake, etc), do not reinvent them, instead allow composing
  of these tools
* do not build a platform that people have to adopt to, or at least
  reduce the adoption as much as possible and provide benefits to
  researchers from day one.
* support a model of "bring your own computing", allows users to
  provide their own computing resources instead of beign tied to host.
* BYOC is inherently flexible in terms of how compute power is
  provided