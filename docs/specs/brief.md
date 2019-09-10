
>*The stages of planning, tracking, recording, processing and visualizing are fundamental to the technique.
In the planning phase, tasks are prioritized by recording them in a "To Do Today" list.
This enables users to estimate the effort tasks require.
As pomodoros are completed, they are recorded, adding to a sense of accomplishment and providing raw data for
subsequent self-observation and improvement.*


# Pomodoro application brief


## Story:

1. I want pomodoro application, available as desktop app for windows (as priority), mac os and linux. 
2. want it to contain planning features, so I can add features and track my activities on working on it
3. want features breakdown, to create atomic subtasks, So I can focus on them 
4. Most existing pomodoro apps only track time ranges for pomodoro, not providing another tooling for technique.

## Reading: 
	- https://en.wikipedia.org/wiki/Pomodoro_Technique
	- http://baomee.info/pdf/technique/1.pdf


## Features:
- Run/Stop pomodoro
- Create tasks
- Import tasks for next day from google calendars/outlook/trello/whatever is also most popular now
- Make large tasks breakdown
- Allow next non-canonical stuff
	- "prolong pomodoro" 5/10/15 minutes or smth - need to investigate, and make user facing tests (or make less distractive behavior, adding automatic prolongation feature). 
	- "add distraction " 5/10/15 minutes, same as previous
- Generate end day report, next day brief.
- Select rest time, proposing predefined options based on prolonging patterns
- Propose pomodoro duration adjustment, based on distraction patterns


## Probably appreciated features:
- Call distraction: add some use to it, making possible to add calling time and short meeting minutes and adding
  new emerging tasks
- Tasks export to trello/outlook/whatever
- Add cheering productivity integration (e.g commits in github, etc), trello tasks closed,
	

## Application examples:
### Gnome pomodoro 
https://gnomepomodoro.org/
- Pros:
  - Convenient enough to use
  - Available for linux
- Cons:
	- No tasks features
	- No tasks breakdown features
	- This productivity tool CRASHES time over time
	- Only for linux
### YAPA
https://github.com/YetAnotherPomodoroApp/YAPA-2:
- Pros:
	- Neat
- Cons:	
	- No tasks
	- Useless pomodoro report, hidden somewhere in configuration
    
 
# MVP attributes:
TBD

	
  
