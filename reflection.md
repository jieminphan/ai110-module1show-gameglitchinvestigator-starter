# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?
The purpose of the game is to guess the number provided and hidden by the system.
When I first ran the game, I noticed the following glitches:
- There were no hints, even when the "Show hint" box was checked
- Guesses are not submitted even after hitting "Enter"
- Attempts are always recorded at 0
- "New game" button does not work
- When I entered 100, it tells me to go higher
- When I entered 140, there's no warning of going over the limit
- When I entered -2, it tells me to go lower
- I have negative scores
- Changing the levels does not change the level of the game
- The range of "Hard" level is smaller than "Normal", and has lesser attempts
- The game mentioned "Out of attempts" when I had a few more to go

---

## 2. How did you use AI as a teammate?

I used Claude Code for this project. One AI example that was correct was the reason why it was telling users to go lower when he number was too low and higher when the number was too high. An example that could be misleading was regarding the number of tries for each difficulty level.
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

I decided a bug was fixed if I tested it and the results were as expected (eg the pressing the "Enter" button submits the guesses). The tests were designed on my own.

---

## 4. What did you learn about Streamlit and state?

Streamlit "reruns" are like running the programmes from the beginning and states are something that tells the programme to remember, so the programme can start from a specific case.

---

## 5. Looking ahead: your developer habits

One habit from this project I want to reuse in the future is using as many test cases as possible. Something I would do differently would be to go more in-depth in my code. This project helped me undersstand that while AI is a tool, it is not perfect.
