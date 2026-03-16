# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started? 
Answer:
Bugs In the Code:

The number seems to be going out of bounds max is 100 but I was allowed to guess 105
Also the game tells me to go higher when the number is lower
The history of my guesses seem to be missing some 
When the game ends seems to not let me start a new one
Hint button not working 


- What did the game look like the first time you ran it?

The game was running efficiently and I was able to type in the text box no problem. Howver I ran into some difficulties when I was submitting an answer then I saw the it was telling me to go higher when the number was lower. I also wasn't able to start a new game 

- List at least two concrete bugs you noticed at the start  :
 I wasn't really able to identify any bugs right off the bat however I noticed that my history of guesses was missing some numbers. Also that when I was guessing the hint saying to go higher or lower was bugged and didn't help at all. 
  (for example: "the secret number kept changing" or "the hints were backwards").

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I used claude code as my ai copilot and github co pilot
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result). I told the github copilot to implement a code that would fix the range bug and it implemented a function pretty quikcly that worked 
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
Some of the function it was implemeneting seemed a little off with the rangers but overall it would actually pretty accurate I was suprised only thing it had a hard time doing was testing 

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
I decided to run the program in streamlit then try of if the bug was really fixed on my end then us co pilot to implement it himself too when they used the test option
- Describe at least one test you ran (manual or using pytest)
One test I ran is when they fixed the range soemtiems in the program if you guessed 1000 it would allow you to guess it when the range should be 1-100 so I ran pytest using co pilot then manually ran stream lit to test it  
  
- Did AI help you design or understand any tests? How?
Yes actually alot it mainly implemented itself it asked me to give it permissions to run some pytest in the terminal and I allowed it too it designed its own pytest im pretty sure it ran it through streamlit module
---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
I think the number wasn't really changing it was dependent on the difficultiy the app was in and I made copilot run the tests and it went thorugh just fine reported no bugs on changing the secret number
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
I would explain it like re opening a video game like fortnite after you game is glitched and you restart to fix the bugs
- What change did you make that finally gave the game a stable secret number?
I didn't make any changes because for my app the secret number never changed and I ran multiple tests manually and it never changed for me.
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?

  - This could be a testing habit, a prompting strategy, or a way you used Git.
  Definetly the pytest because it actaully helps pointing out bugs and fixing them right away rather then manually going in and testing everything yourself. Well it's good if you manually test it but pytest is actaully really good for debugging

- What is one thing you would do differently next time you work with AI on a coding task?
Honeslty I would use it to explain code more and point out bugs rather than just do it and not explain anything so I can learn not to write those bugs next time and also get better at prompting the AI
- In one or two sentences, describe how this project changed the way you think about AI generated code.
This project made me think diffretnly about AI because when I think about AI in my field I think about it doing my job for me but the way I see it now its more of a partner assisting you with what you need. I feel like its a very nice tool alot of develpoers use that would assist them on their projects which is really helpful because it can write,implement and explain code for you.
