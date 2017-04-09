---
layout: team
page-head: Development
---
## Meetings

#### Nilay, Raghu, Mai-Khanh
Team Meetings (15 hours)


## Coordination

#### Nilay, Raghu, Mai-Khanh
The whole team met twice a week, about two-three hours each time, to discuss
progress, what each team managed to do since the last meeting, and future tasks.
On another hand, the programming team constantly talked with
each other in order to divide the work between us so as to not overlap, and check
each other’s work when a task was done to validate everything. We used github and
trello for project management.


### Features that were not kept:

**Nilay**
- Old sankey (colors and nodes names)
- Color-pairing sankey and pc (old colors)
- Clickable links (instead of nodes)


### Lessons learned


#### Nilay, Raghu, Mai-Khanh
The major aspect of this project was most definitely working in a team that is a melting pot of skills and nationalities, which was quite interesting and new.
Since in the past I only worked in teams with programmers only, I realised that working with designers takes a big load off coders’ shoulders and helps making a more polished looking final application.
All in all, the biggest lesson learned during the project is the process of working with different types of people and compromising, as well as adapting the workflow so that everybody can be satisfied.


### Contributions

#### Iteration 1: Hello World demo

**Nilay**
- Implementation of sankey with dummy data
- First design of the sankey. (colors, size and transition when clicked on the links of sankey)


**Raghu**
- setting things up.
- parsing variables to variable.json

**Maiky**
- displaying parallel coordinates when clicking on one part of the sankey (2.5h)
- small sample of data (25 lines) for testing (0.5h)



#### Iteration 2 : KTH Final demo

**Nilay**

*Sankey*
- Tooltips
- Sankey redesign (new colors and new nodes)
- Making nodes clickable instead of links

*Parallel coordinates*
- Filter datas to display depending on sankey part

*Treating data*
- Calculating real data for sankey
- Merging all the data for the parallel coordinates in one file
- Deciding which columns to keep (as a team),
- Creating/calculating new columns, modifying/merging some of the existing ones

*others*
- Transitions between the two layouts (just sankey and sankey+pc+summary+cohorts )
- Bugs fix (all)


**Raghu**

*parallel coordinates*
- axes tooltips

*summary*
- brushes summary (creation and updates)
- creating/removing cohorts summary

*list of variables*
- searchable text field
- list of checkboxes
- checkboxes tooltips
- default variables for each sankey part

*treating data*
- list of variables to use (variables.json)
- VariableModel.js

*others*
- bugs fix (all)
- overall design

**Maiky** (80h)

*parallel coordinates*
- adding/removing axes
- displaying/taking off cohorts when checked

*list of variables*
- min of 2 variables checked

*cohorts*
- simple design (textfield, colorbox, list of created cohorts)
- saving/deleting

*others*
- QA list → executed by other members
- bugs fix (all)


### Iteration 3 : KI demo (April 4th) + C-Awards Submission

**Nilay**

*sankey*
- changes in tooltip (% patients)

*cohorts*
- colors for cohorts (from random to ordered)

*others*
- bugs fix (all)


**Raghu**
- website

**Maiky (10h)**
- parallel coordinates
- rescaling axes
- bundling
- multibrushing colors
- ordering axes’ ticks
