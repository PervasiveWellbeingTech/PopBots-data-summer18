# PopBots-data-summer18

During the summer of 2018, the Pervasive Wellbeing Technology Lab used Amazon Mechanical Turk (using Qualtrics surveys) to gather linguistic and demographic data on people and what commonly stresses them out. 

In our first "comprehensive" stress survey, we asked questions questions about how stressed people feel in general, the nature of their stressors, how much social support they receive from their community, and how likely they are to chat with therapeutic chatbots. On a scale from 1 (not stressed at all) to 10 (extremely stressed), the average stress level was 7. People tended to report that they were stressed about ongoing circumstances (rather than singular events). We hypothesized that the more social support a person had from their family, the less likely they would be to use therapeutic chatbots. Through our mturk surveys, we did not find a relationship between the two. We did find that most people were somewhat likely or likely to chat with the bots if they were readily available. You can view the data [here](comprehensive_stress.tsv) and the original survey [here](qualtrics-surveys/comprehensive_stress_survey.pdf).

The main focus of the following series of surveys is the pairing of stressors (i.e. an individual's written statement about something that stresses them out) and their responses (i.e. a text response, like what one would receive via text message from a friend, to the stressor). The goal is to understand what kind of responses, or affirmations, are appropriate for different situations. The study consists of 3 separate surveys, whose main purposes are detailed below:

  Phase 1 [(phase 1 data)](stress_1.tsv). Collect stressors and “ideal” responses to them. (i.e. What’s something that has been stressing you out recently? What would an ideal response from a bot/friend look like?)
  
  Phase 2 [(phase 2 data)](stress_2.tsv). Collect alternate responses to selected stressors from part 1. (i.e. Imagine your friend texts you: “I’m stressed because I don’t have enough money for next month’s rent.” How do you respond?)
  
  Phase 3 [(phase 3 data)](stress_3.tsv). Have people rank and categorize (good, bad, neutral) multiple responses (selected responses from part 2. + “ideal” response from part 1.), given a stressor. To make sure people are putting thought into their responses, require them to provide justifications for how they determined if statements were good/bad/neutral, and maybe have them “fix” the responses they categorized as bad. The results from this survey are a bit difficult to understand in tabular form; you can view data visualizations [here](stress_3_viz.pdf).
  
  
We also have data from user conversations via Facebook Messenger, when we were still using the Messenger platform. This data is stored on the Stanford Department of Computer Science's commuter server. We were able to perform some analyses on this data, but for privacy purposes, we cannot share user conversation data on github.
