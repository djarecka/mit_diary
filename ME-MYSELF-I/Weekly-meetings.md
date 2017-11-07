# Weekly Meetings

* [15th September 2017](#date-15th-september-2017)
* [24th September 2017](#date-24th-september-2017)
* [29th September 2017](#date-29th-september-2017)
* [8th October 2017](#date-8th-october-2017)
* [15th October 2017](#date-15th-october-2017)
* [22nd October 2017](#date-22nd-october-2017)
* [29th October 2017](#date-29th-october-2017)
* [5th November 2017](#date-5th-november-2017)


### Date: 5th November 2017

#### Who did you work directly with (i.e. we helped each other) this week?

#### Who did you help this week?

* some nipype users: neurostar, nipype
* helped David qith github workflow and CI

#### Who helped you this week?

* Jakub helped me with neurodocker and a new Dockerfile for nipype_tutorial
* Satra suggested changes to nipype_tutorial notebooks
* Mathias helped me with read-only system and testing my PR
* Satra helped me with my pytest PR: fixing failing DataSink test


#### What did you achieve?

* finished pytest cleaning PR
* updating nipype tutorial and testing with a new container
* creating Dockerfile for the tutorial taht works with Binder (tested)
* reviewing some issues
* updating some tests in pynidm and testing David PR


#### What did you struggle with?

* connecting nipype_tutorial to mybinder
* understanding how to use conftest.py andd pytest.ini with pytest
* figuring out ants. registration interfaces (what should be mandatory, default etc.)

#### What else did you do this week week?

#### What would you like to work on next week?

* reviewing repronim training materials
* creating examples for neurodocker
* opening a new traitlets PR
* exercises and CI to nipype_tutorial
* checking combination nipype & matlab (neurostar)

#### Where do you need help from Satra?

#### Any other topics



### Date: 29th October 2017

#### Who did you work directly with (i.e. we helped each other) this week?

#### Who did you help this week?

* some nipype users: neurostar, nipype

#### Who helped you this week?

* Satra talked to me about traitlets, and explained why I should be creating a new PR.

#### What did you achieve?

* fixing a few more tests in traitlets PR
* pytest cleaning
* reviewing some issues
* some basic tests for nidm
* creating a PR for ants issue


#### What did you struggle with?

* connecting nipype_tutorial to mybinder
* understanding how to use conftest.py andd pytest.ini with pytest
* figuring out ants. registration interfaces (what should be mandatory, default etc.)

#### What else did you do this week week?


#### What would you like to work on next week?

* opening a new traitlets PR
* finishing pytest cleaning
* PyNIDM
* connecting nipype_tutorial to mybinder
* reviewing repronim training materials
* checking combination nipype & matlab (neurostar)

#### Where do you need help from Satra?

#### Any other topics
took a day off



### Date: 22th October 2017

#### Who did you work directly with (i.e. we helped each other) this week?

#### Who did you help this week?

* some nipype users: neurostar

#### Who helped you this week?

#### What did you achieve?

* fixing a few more tests in traitlets PR
* changing TraitedSpec, so it doesn't change mutable variables used as inputs
* helping with cmtk.nbs:
  - nipype PR improving some error massages and adding tests for cmtk.nbs
  - PR to connectomviewer


#### What did you struggle with?

* having problem with testing connectomviewer with docker container based on neurodebian (at the end wasn't important for the code I wanted to test to solve an issue)

#### What else did you do this week week?


#### What would you like to work on next week?

* continue working on traitlets
* PyNIDM
* cwl
* helping Alex

#### Where do you need help from Satra?

#### Any other topics
were on vacation till Wed, may need to take one more day off this week



### Date: 15th October 2017

#### Who did you work directly with (i.e. we helped each other) this week?

#### Who did you help this week?

* helped Alex with issue regarding image resolution 

#### Who helped you this week?

#### What did you achieve?

* fixing a few more tests in traitlets PR
* creating a PR with tests to traitlets repo
* small PRs to PyNIDM


#### What did you struggle with?

* still having problem with traitlets container-type traits, waiting for possible changes

* problems with nilearn tests, global lists are modified (probably should change the nipype classes) 

* some problems with the dev version singularity (api has changed)

#### What else did you do this week week?

* attending fMRI lectures

#### What would you like to work on next week?

* continue working on traitlets
* PyNIDM


#### Where do you need help from Satra?


#### Any other topics
took some time off this week and planning to be on vacation till Wed.



### Date: 8th October 2017

#### Who did you work directly with (i.e. we helped each other) this week?

* working with Jakub on cwl examples

#### Who did you help this week?

* short conversation with Ola about statistics

#### Who helped you this week?

* Jakub helped me to solve problem with docker examples run by cwl
* Satra helped me with my traitlets PR


#### What did you achieve?

* fixing a few more tests in traitlets PR
* solving problems with running simple workflow using cwl-runner
* small fix to neurodocker
* suggesting some test to traitlets


#### What did you struggle with?

* still having problem with traitlets, one of the problem related to how traitlets treats `default_value` (see the [issue](https://github.com/ipython/traitlets/issues/455))  

* didn't know how to mount directory with data to docker container when running a script using cwl

* having problem with creating a docker image for the nipype tutorial (some should be solved by my fix)

#### What else did you do this week week?

* attending fMRI lectures

#### What would you like to work on next week?

* continue working on traitlets, have to finish all general files from interface directory
* creating a docker file and adding exercises to nipype tutorial
* running more examples with cwl

#### Where do you need help from Satra?


#### Any other topics
planning to take 3-4 days of vacation in the week 16-23 Oct.


### Date: 29th September 2017

#### Who did you work directly with (i.e. we helped each other) this week?


#### Who did you help this week?

* Checking a few thing in ClearMap for Alex
* Neurostar

#### Who helped you this week?

* Satra gave me some suggestions regarding dropbox


#### What did you achieve?

* finished a github repo with data tracked by datalad (https://github.com/djarecka/datalad_repo_test); 
   - [notes](https://github.com/djarecka/mit_diary/wiki/datalad---dropbox)
   
* fixing a few more tests in traitlets PR


#### What did you struggle with?

* I still haven't fixed the traitlets error when running multiple tests from test_io.py 
("traitlets.traitlets.TraitError: Unexpected error in TraitType: default value not set properly")
It's realated with `JSONFileSinkInputSpec` and other `*InputSpec` classes that have `__setattr__`

* My tests running simple workflow with cwl are failing, both with and without docker (but different errors), 
more in [the notes](https://github.com/djarecka/mit_diary/wiki/cwl-wip-notes) 

#### What else did you do this week week?

* attending fMRI lectures

#### What would you like to work on next week?

* continue working on traitlets, have to finish all general files from interface directory
* continue working on simple workflow with CWL examples (on my own and with Jakub)
* start adding exercises to nipype tutorial

#### Where do you need help from Satra?

* suggestion what should I do with the repo with tutorial output
* traitlets
* possibly with cwl

#### Any other topics


### Date: 24th September 2017

#### Who did you work directly with (i.e. we helped each other) this week?

* I was running CWL examples and discussing the problems with Jakub.

#### Who did you help this week?

* I had a short meeting with Alex

#### Who helped you this week?

* Yarik helped me with creating datalad repository from files saved in dropbox.
* Chris and Oscar helped me with PR
* Satra explained some issues regarding regression testing

#### What did you achieve?

* rerun all examples from nipype_tutorial and adding to datalad repo (it's very inefficient, still have to improve the workflow)
* finished PR on networkx
* run CWL tutorial 
* solved an issue

#### What did you struggle with?

* I'm still not sure hot to efficiently create datalad repository from files from dropbox. Yarik corrected my files names, but I'm not sure what is the best way of using `git annex addurl` (more in my email).
* I'm having problem with running simple workflow locally using CWL (could be related to temporary directories that CWL creates), also having problem with accessing environmental variables in a `cwl` file.

#### What else did you do this week week?

* attending fMRI lectures
* attending statistical learning lectures
* a short presentation for Gablab Datablitz

#### What would you like to work on next week?

* coming back to traitlets, have to finish all general files from interface directory
* debugging Alex workflow (and understanding how this should be done)
* finish the datalad repo
* continue running CWL examples



#### Where do you need help from Satra?

* gita annex/ datalad
* possibly with traitlets

#### Any other topics


---

### Date: 15th September 2017

#### Who did you help this week?

* Spent a few hours working on ClearMap and trying to help Alex to change the image for the registration.
* small help with Python for Qasim 
* neurostar (nipype)

#### Who helped you this week?

* Got some help from Satra and Yarik regarding datalad and dropbox.
* talking to Smruti about various certifications 

#### What did you achieve?

* some new chnages in my traitlets PR (new classes, changes in io (this still give errors))
* testing different pieces of creating datalad repository with my output data

#### What did you struggle with?

* Changing io.py for traitlets
* Creating datalad repository from data storage in dropbox

#### What else did you do this week week?

* attending fMRI lectures
* attending statistical learning lectures (not sure if will continue)

#### What would you like to work on next week?

* coming back to traitlets, have to finish all general files from interface directory
* finis what Alex wants to change with registration
* rerun all examples from nipype_tutorial and create datalad repo (still have to work on dropbox api and git annex)
* checking tox so we can use it with regression testing



#### Where do you need help from Satra?

* still might need some advices how to add the output files to the datalad repository ds000114
* possibly with traitlets

#### Any other topics




---

## Template (Copy template, add date link on top, and replace text, newest first)

### Date: [INSERT DATE OF MEETING]

#### Who did you work directly with (i.e. we helped each other) this week?

#### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.


#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

#### What did you achieve?

* Replace this text with a bullet point list of what you achieved this week.
* It's ok if your list is only one bullet point long!

#### What did you struggle with?

* Replace this text with a bullet point list of where you struggled this week.
* It's ok if your list is only one bullet point long!

#### What else did you do this week week?


#### What would you like to work on next week?

* Replace this text with a bullet point list of what you would like to work on next week.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Where do you need help from Satra?

* Replace this text with a bullet point list of what you need help from Kirstie on.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Any other topics

This space is yours to add to as needed.
