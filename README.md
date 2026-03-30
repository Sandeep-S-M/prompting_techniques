# **Format of the Audience Persona Pattern**



To use this pattern, your prompt should make the following fundamental contextual statements:



Explain X to me.



Assume that I am Persona Y.



You will need to replace "Y" with an appropriate persona, such as "have limited background in computer science" or "a healthcare expert". You will then need to specify the topic X that should be explained.



Examples:



Explain large language models to me. Assume that I am a bird.



Explain how the supply chains for US grocery stores work to me. Assume that I am Ghengis Khan.





# **Format of the Cognitive Verifier Pattern**



To use the Cognitive Verifier Pattern, your prompt should make the following fundamental contextual statements:



When you are asked a question, follow these rules



Generate a number of additional questions that would help more accurately answer the question



Combine the answers to the individual questions to produce the final answer to the overall question





Examples:



When you are asked a question, follow these rules. Generate a number of additional questions that would help you more accurately answer the question. Combine the answers to the individual questions to produce the final answer to the overall question.



Tailored Examples:



When you are asked to create a recipe, follow these rules. Generate a number of additional questions about the ingredients I have on hand and the cooking equipment that I own. Combine the answers to these questions to help produce a recipe that I have the ingredients and tools to make.



When you are asked to plan a trip, follow these rules. Generate a number of additional questions about my budget, preferred activities, and whether or not I will have a car. Combine the answers to these questions to better plan my itinerary.





# **Format of the Flipped Interaction Pattern**



To use this pattern, your prompt should make the following fundamental contextual statements:



I would like you to ask me questions to achieve X



You should ask questions until condition Y is met or to achieve this goal (alternatively, forever)



(Optional) ask me the questions one at a time, two at a time, ask me the first question, etc.



You will need to replace "X" with an appropriate goal, such as "creating a meal plan" or "creating variations of my marketing materials." You should specify when to stop asking questions with Y. Examples are "until you have sufficient information about my audience and goals" or "until you know what I like to eat and my caloric targets."



Examples:



I would like you to ask me questions to help me create variations of my marketing materials.  You should ask questions until you have sufficient information about my current draft messages, audience, and goals. Ask me the first question.



I would like you to ask me questions to help me diagnose a problem with my Internet. Ask me questions until you have enough information to identify the two most likely causes. Ask me one question at a time. Ask me the first question.

#### 

#### **Chain of thought:**

giving an example with the input and output to the gpt to generate the solution in the same format as given example and also the question should be in the same format as the given example one



#### **REACT Method :**

it is similar to the chain of thought but the simple
provide some example/ Artificial response about content like Task, think, action, result in each example atleast 4-5 . In that example you need to describe about the task ,how to think ,how to respond , in what format do you need your result



## **Format of gameplay Pattern:**

**->** Create a game for me around X OR we are going to play an X game

-> one or more fundamental rules of the game
Example:- Create a group party game for me involving DALL-E. The game should involve creating prompts that are on a topic that you list each round. Everyone will create a prompt and generate an image with DALL-E. People will then vote on the best prompt based on the image it generates. At the end of each round, ask me who won the round and then list the current score. Describe the rules and then list the first topic. 



## **Format of the Template Pattern:**

**->** I am going to provide you a template for your output

-> X is my placeholder for Content

-> try to fit the output in one or more placeholder that I listed

-> please preserve the formatting and overall template that I provide

-> This is the template: PATTERN and PLACEHOLDER



Guide: you will need to replace "X" with appropriate placeholder, such as "CAPITALIZED WORDS" or "<PLACEHOLDER>"

&nbsp;      you will then need to specify a pattern fill in, such as "Dear <Name>","Company"



## **Format for Meta Language Creation:**

you can use meta tags such as,

example :- "plan a trip based on list requirements which includes my time, joyfull moments, food availability based on the budget,

I will provide you the start and destination details plan the between stops between the journey based on the requirement list + 'shelter availability' "
 2 = banglore\[start]->Delhi\[destination]:
     1.6,5,650,1000(first day spends in format \[day.hours need to spend on each day in different places, joyfull moments, amount for meals,amount for stay])

&nbsp;    2.8,9,800,1000(second day spends in format \[day.hours need to spend on each day in different places, joyfull moments, amount for meals,amount for stay])
2 is number of trip

**{NOTE:** Now you can ask any number of question in main format it will assume in the same format as mentioned**}**


**TASK DEPENDENCY LANGUAGE:** chatGPT easily understand it is simple "when I say TaskX\[TaskY], that means TaskX is dependent on TaskY being complete first"





## **Recipe Pattern:**

it's a fill out the missing step in the sequence and pop out the unwanted step in sequence :

method: 
 1. I Would like to achieve X

&nbsp;2. I know that I need to perform A,B,C

&nbsp;3.provide a complete sequence of steps for me 

&nbsp;4.fill the sequence if any step is missing

&nbsp;5. pop out the step if any added extra (optional)

example: I would like purchase a house, I know that I need to perform steps make an offer and close on the house,

provide the complete sequence of steps for me, fill the sequence if any steps is missing.



## **Alternative approach pattern:**

method:-

if there is any alternative approach to TaskX , provide me the best approach
(optional) compare/constrain the pros and cons of each approach

(optional) include the original way that I have asked
(optional) prompt me for which approach I would like to use


Example:- for every prompt that I gave you, if there are alternative approach by using best word format for provided prompt conclude based on the pros and cons
include the original way that I asked
prompt me for which approach I would like to use

## **Outline Expansion Pattern:**

method:
ACT as an outline expander ,
generate a bullet point outline based on the input provided to you and ask me for which bullet point you should expand on
create a new outline for bullet point I have selected
At the end, ask me what bullet point expand next 
Ask me for what to Outline


##** Menu Action Pattern**

-> when I type: x you do Y
-> At the end ask me for next action

example : when ever I type "ADDitem" ask me for the item then update it in the groceries list in alphabetic order,
when I type "remove item" ask for the item and remove it from groceries list.


##** Fact check List pattern**:
-> generate a set of facts from the output
-> the set of facts should be inserted position in output
-> the facts should be fundamental facts with veracity in the output 

example: whenever your output text, generate a set of facts from output  ,these facts are inserted at down side of the output
these facts should be the fundamental facts with veracity in the output generated


##** TASK generation pattern**:

its just creating an end for each prompt to accomplish

method: 
-> at the end, repeat Y and /or ask me for X

example: for any pattern in previously discussed add this at the end

at the end , please maintain the description add a disclaimer = "good handwriting , ChatGPT generated text don't veracity


##** semantic Filter pattern**:

method:
-> filter this information to remove X 

example: filter this information to remove any duplicate person name in the list 
