### Summary

The data visualization is based on a dataset that includes information of 891 passengers on Titanic. The visualization aims to provide some intuitions about how to travel safely through exploring the relationship between the presence of travel companions and the survival rate.

## Design

### Chart Types
As I want to show the proportions of groups, I only have two alternatives——pie chart and bar chart. But as pie charts are less effective than bar charts (in that pie charts use more visual encodings to convey the same information than bar charts), I chose bar charts in this visualization.

### Visual encodings
x position: groups(Alone, With siblings or spouses, With parents or children)
y position: the proportions

### Story
At first, I wanted to show an animation of the story. But setting a suitable time interval between different parts of the story is too difficult (because different people read at different speed). So later I created buttons so that readers can control the flow of the story by themselves.
The story is followed by an interaction which allows the readers to explore by themselves.
  
### Libraries
As the bar charts are not complicated, I used dimple.js to create them.
Additionally, I also used d3.js.

## Design Change

## Feedback
### Questions:
What do you notice in the visualization?
What questions do you have about the data?
What relationships do you notice?
What do you think is the main takeaway from this visualization?
Is there something you don’t understand in the graphic?

### Feedbacks are given by my friends:
Feedback from Max:
1.I noticed that the proportions of the survivors in titanic are different in different groups.
2.I don’t have any question about the data.
3.Travelling with families has more chance to survive, while travelling alone is more easy to die.
4.The data are demonstrated in a clear and neat way. And instead of just simply showing the data, the visualization presents the data with a guidance.
5.No

Suggestions:
1. The font of the button can change into boldface. 
2. Also swap the order of the ‘next’ and ‘back’ button will be better.

Feedback from Claire:
1. I notice that the visualization makes a comparison between the number of people going with families and that of those who went alone. Also it shows the numbers of survivors and victims in different groups.
2. I don't think the conclusion that we should always travel with our families can be drawn so easily without considerable data.
3. Maybe if a person travel alone, he will be more likely to face danger than those who travel with others.
4. The part where I can go back to the previously shown graghs.
5. No.

## Resources
https://grafana.com/blog/2015/12/04/friends-dont-let-friends-abuse-pie-charts/
