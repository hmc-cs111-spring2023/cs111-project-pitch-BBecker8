# Contract

## Goals

_At a high level, what do you most want to get out of this project, and why?_

Goal 1: Brainstorm and generatge ideas for your dsl language
The first goal of mine will be to come up with an idea for my dsl language and to really define the specifics of the language and how that might map out to a stats sheet. The most imortant part of this will be finding a langage that is simple enough for non coders to use and that can easily map to a data structure. Along with this will be fining the host language as of right now I think my top three options are python, java, and scala.

Goal 2: Build data structures that represent a teams stat sheet
The second goal of mine will be to use classes to implament a data structure that can be representative of a stats sheet. For instance do I use a dictionary for each individual player or a linked list or a map of some kind. The overall data structure will look like an excell sheet where each row is a player and each colomn is a different stat. On top of this another data structure for team stats should be built using the avergaes of the player stats this will show the affectivness of the team and will look similar in structure.  

Goal 3: Build methods that add player/team data into the data structures
The third goal will be to build methods that add data to the data structures. This way I can easily map out how the methods and data structures work together and so that later I can use the methodology to help build the language. It is important that I have methods that deal with adding data to the structures as well as using the data from the strutures and editing it. For instance lets say Tom passes for 33 yards on first down and 10 yards on the next play to would be nice to have the passing total of tom be 43 and not a list of 33,10.... Aditionally lets say that the user makes a mistake and puts int the wrong stat there should be some type of method that allows for a correction.

Goal 4: Connect the dsl language to the methods for data addition to the stat sheet and work on error handling
The fourth goal is to put it all together. I will take my brianstromed DSL language and map it to the existing methodology. This way the user can use simple natural languge to build a stat sheet. The last part will be error handling with the language and making sure that the user knows when thier data is nit being prcoessed correctly. Error handling should also be implamented in all the previos steps as well but these will be deeper level errors that a user may not understand.

Goal 5: Use the google sheets API or excell api to implament live stat handling
My final goal will be to reserch and utalize an API for live stat keeping so that when a user uses the DLS it adds that data directly to a veiwable spreadsheet in excell or google sheets. This will take some research and some time but it should be fairly easy to map the data structures directly to the API. This goal is importnat because I belive that it shows proof of concept that such a tool such as a DSL can build easy live stat sharing. Although live stat sharing is possible at the profession levels there is usually still someone at the game responsible for the input of the data. This is not alaways the case for highschool and lower colleigate levels. I hope this aspect of my dls can make it easy to build live stats and can show prof of concept at all levels.

## Concepts / skills

_What concepts and / or skills from class would you like to work on, as part of your
project? Are there any concepts / skills that we haven't covered in class that you would
like to work on, as part of your project (for example, other things related to DSLs that
you have come across, or topics from other classes)? Why are you interested in working on
these things?_

The concepts from class that I will be using are natural-language syntax, pattern matching, language mapping, and the idea of building a bridge between the dsl and the host language. Some things that we have not covered in class that I will be taking from previos expirences will be things such as data structure creatation/implamentation depending on libraries avaliable and API usage such as sending data to a live excell sheet. I think all of these skills will build a very good project. Im excited to dive deeper into the natural-language syntax/semi-natural-language syntax. I think this will be the easiest way for all users to utalize the dsl. Also it will be important that my language maps out to the data structure that represents a stat sheet. 

## Time management plan

_How do you plan to set aside time outside of class, to work on the project? Are there
intermediate milestones that you can create, to help you make consistent progress?_

I plan to work on the project on Mondays, Wensdays, Fridays and Sundays. On Monday I will use the time in class to finish the critique for people in my group. Additionally if that is not finished in class then I will finish it later that night. Monday night I will plan to either finsh the critique or start working on the next section of my project. On Wensdays I will use the time in class to work on the project and ask questions on things that I may be having trouble with/ need help with. Wensday night I will plan to continue the section of my project that I have been working on that week for and hour or two. On Fridays I will work on the project in the later afternoon for a few hours before dinner. On Sunday I plan to work on my project for a few hours and then complete the Project notebook for the week. I plan to split the project into ... sections of worked based off of my goals. This way I can devide the five weeks into an even set of work for the project and each goal will have ... time to complete.

## Teamwork plan

_If you plan to work with someone else on the project, what is your plan for
collaborating? What part(s) do you think you might do together? What part(s) are you
considering doing separately? How will you hold one another accountable to make regular
progress?_

N/A I will be working by myself

## Critique plan

_What will you do to make sure that you can give consistent and actionable feedback to
other people in the class?_

In order to make sure that I can give consistent and actionable feedback to other people in the class I will attend class on mondays and plan to talk with the people in class in which I am critiqueing. My plan will be to look over peoples journals before class starts in oder to see what they have accomplished with thier project so far/ since I last looked at it. Additionally in class I would like to have a quick meeting to discuss what they are planing to do for the following week and I will plan to also look over their code on github and leave feedback on it. I will plan to do this all on monday and if I become overwhelemed with work on a monday I will finish the critique sepcifically code reviews on tuesday. I belive that if I stay ontop of a schedual like this every week, I should be able to provide good, consistent and actionable feedback to people in the class. 


## Success

_At the end of the semester, what would you be proud to show or tell someone about your
project?_

At the end of the semester I would be proud to show/tell someone that I built A DSL for live stat keeping that is simple and does not require pen and paper or an extensive excell sheet. I would esspecially be proud to tell my dad that he no longer needs to bring a notepad for stat keeping to my brothers football games. If this project goes really well I think it could have potential aplications within the highschool and collegiate football realm. What I mean by this is that currently coaches at the highschool and lower colligiate levels have to manually input stats for their players into their systems. So what if instead they had a DSL that allowed them to keep live stat keeping that could hook into thier systems and manually update in live time. Although I do not think It would be possible to expand to the that level over the last few weeks of the semester, I think it would be really cool to show proof of concept such as having the dsl update a spreadsheet in excell live. Overall I would be most proud to show off the language weather it is more natural langauge esc or a combination of natural language and method based, also I would be very proud to show that a simple dsl can build a stat sheet for an entire team and the potential to activly update an excell sheet.

## Assessment

_Looking over your responses to the previous questions, what would you consider to be an
"A-" for your project? What would you consider to be an "A"?_

I think that creating a dsl that builds data structures that represent a teams stat sheet would be good enough for an B+ to A- range. The data structures accumitivly would be the representation of all dsl input and be the aquivalent of a teems stat sheet that you may see in excell. However, I think I will be able to get to a point where I can take the data structures and use the excell api to make a live stat sheet for the dsl. I belive this would be the equivalent of an A. 
