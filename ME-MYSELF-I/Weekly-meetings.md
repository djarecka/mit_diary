# Weekly Meetings

* [15th September 2017](#date-15th-september-2017)
* [24th September 2017](#date-24th-september-2017)
* [29th September 2017](#date-29th-september-2017)


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
