# Weekly Meetings

* [15th September 2017](#date-15th-september-2017)
* [24th September 2017](#date-24th-september-2017)
* [29th September 2017](#date-29th-september-2017)
* [8th October 2017](#date-8th-october-2017)
* [15th October 2017](#date-15th-october-2017)
* [22nd October 2017](#date-22nd-october-2017)
* [29th October 2017](#date-29th-october-2017)
* [5th November 2017](#date-5th-november-2017)
* [15th November 2017](#date-15th-november-2017)
* [26th November 2017](#date-26th-november-2017)
* [10th December 2017](#date-10th-december-2017)


### Date: 10th December 2017 (for 2 weeks)

#### Who did you work directly with (i.e. we helped each other) this week?
* with Jakub on regression tests

#### Who did you help this week?

* nipype users

#### Who helped you this week?

* Jakub with neurodocker for regtest
* Satra helped me to understand how to use cwl with regtest

#### What did you achieve?

* solving some nipype issues
* closing doem old pr/issues
* reviewing the olf traitlets issue and collect changes that are valid for the traits version
* finishing PR exercises to nipype tutorial
* writing first simple version of regtest framework


#### What did you struggle with?

* understanding how to use cwl with regtest

#### What else did you do this week?

* applying for IAP (suggesting 2 workshops) 
* meeting with Paul and Lee
* meeting with Satra

#### What would you like to work on next week?

* new api
* regression tests: learning `scatter`, adding docker creation to cwl
* nipype: old pr, issues
* my traitlets pr base issue (create a new pr)

#### Where do you need help from Satra?

* nipype - new api
* nipype - old pr


#### Any other topics



### Date: 26th November 2017

#### Who did you work directly with (i.e. we helped each other) this week?
* with Jakub on neurodocker for regression test

#### Who did you help this week?

* nipype users
* explaining docker to my previous collaborator


#### Who helped you this week?

* Jakub created for me Dockerfile for a C++ library
* Satra explained to me problem with running fsl script in jupyter notebook
* Satra and Mathias helped me with solving the fsl nipype issue

#### What did you achieve?

* solving some nipype issues
* finishing PR for neurodocker
* adding exercises to nipype tutorial [WIP]
* updating repository&CI for regression tests
* adding interfaces to regression [WIP]



#### What did you struggle with?

* understanding fsl checks in nipype

#### What else did you do this week?
* meeting with Satra to talk about VM+Docker servers 


#### What would you like to work on next week?

* regression tests with Jakub
* finishing exercises and creating CI for nipype_tutorial
* reading more about prov and update PyNIDM
* post about docker (?)


#### Where do you need help from Satra?


#### Any other topics
* working remotely on Mon/Tue


### Date: 15th November 2017

#### Who did you work directly with (i.e. we helped each other) this week?
* with David on PyNIDM tests

#### Who did you help this week?

* brainhack participant to work preprocessing on her data
* software carpentry participants
* repronim training participants
* explaining docker to Julie
* explaining git/datalad to conference participants

#### Who helped you this week?

* Yarik helped me with datalad subdirectory
* David was explaining me prov library
* Jakub helped me to fix docker for nipype tutorial


#### What did you achieve?

* updating repronim training lessons
* adding examples for neurodocker
* updating nipype tutorial
* adding some simple tests to PyNIDM


#### What did you struggle with?

* installing docker on various platforms
* changing nipype.test do it can use option from pytest.ini
* understanding prov library and ho to access/check all attributes

#### What else did you do this week?
* sfn (brainhack, software carpentry, repronim training)


#### What would you like to work on next week?

* regression tests with Jakub
* opening a new traitlets PR (?)
* exercises and CI to nipype_tutorial
* reading about prov and adding tests to PyNIDM


#### Where do you need help from Satra?
* choosing an alternative library to traitlets
* choosing the best way for testing PyNIDM/prov

#### Any other topics
Next week will be working 3 days remotely and afk for Thanksgiving (probably Wed-Sat)




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
