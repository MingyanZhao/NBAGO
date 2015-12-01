# PressBook of NBAGO

## Week Zero

[Project Proposal] (https://github.com/MingyanZhao/DataVisFinal/blob/master/proposal.md)

Objective: Proposal

## Week One

Objective: Set up environment and redesign project base on proposal feedback.

The first week and before the feedback of the proposal, we share the work and try to build some infrastructure code:
Mingyan design the front page and Game Tab and Team Tab.
Adam choose to start with the Player Tab.
Congyuan try to set up the Django server.

After the USA map with team Logo was done, we receive the feedback of the proposal. The main idea is our project proposal is acceptable and  we are encouraged to build something new.

We accept the advices and decide to focus on a specific task and create innovative visualizations. Mingyan redesign the project proposal and redefine our objective. The new main idea of the project is to show "what was happening in those games".

The changes of the project are:
* The main dataset now is only using play by play data of 2009-2010 season, that are in directory /2009-2010.regular_season, about 1230 games.
* User can specify a team.
* We show all the results of the team in the season using bar chart
* User can brush on the bar chart to choose a certain time interval.
* We show several visualizations to display what was happening in those selected games. The vis could be:
  -	Shooting chart
  -	Accuracy
  -	Point got and loss percentage
  -	Information about players
  -	Other vis

## Week Two

Objective: prototype design.

Mingyan continue to develop the code of project entrance, which is the USA map with team Logo. The develop the game result bar chart which used to choose games. Then the information of the selected games are dispatched, so the other visualizations can updated correspondingly.

Mingyan implement the shooting chart which display all of the shooting happened in the selected games.

Adam implement the treemap chart which display the points got by each player in those games.

Congyuan was trying to get data from stats.nba by sending request.

Week two meeting is on Nov, 29, 2015, 1:00 pm, at Library. We discucssed the new design and share the work left.

## Week Three

Objective: continue to working on game detail visualizations.

## Week Four
Fix bugs and create report.
