## 1. Use the same prompt with temperature = 0.2 and then with temperature = 0.9.
**prompt:** 
For these questions, answer with temperatures 0.2 and 0.9
1. The girl is skipping with a ______
2. The pot is in the ________

**AI's response:**
Prompt 1: “The girl is skipping with a ______”
Temperature = 0.2 → low randomness, AI favors most likely words
Answer: “The girl is skipping with a rope.” 

Temperature = 0.9 → higher randomness, AI can pick more creative options
Answer: “The girl is skipping with a balloon.” 



## 2. Repeat with different top-p values (e.g., 0.5 vs 1).
**prompt:**
Now using temperatures 0.5 and 1.0, complete these sentences
1. John is a student, he is _____________
2. The palm wine tapper is ___________
3. The software engineer at Google is searching for ? _________________

**AI's Response:**
1. John is a student, he is _____________

Temperature = 0.5**:
"John is a student, he is diligent."
Explanation: The AI chooses a safe, expected word like "diligent," which fits well with the context of being a student. It's a reasonable, balanced completion.

Temperature = 1.0:
  "John is a student, he is always cramming the night before exams."
Explanation: Higher temperature leads to more creativity, with a more unique, humorous addition to the sentence that still makes sense.


2. The palm wine tapper is ___________

Temperature = 0.5**:
  "The palm wine tapper is skilled.
Explanation: A safe, direct answer. "Skilled" is a common adjective you'd associate with someone who taps palm wine. It's a predictable, normal word.

Temperature = 1.0:
  "The palm wine tapper is climbing the tallest tree at dawn.
Explanation: With higher temperature, the response is more imaginative and vivid, describing the tapper’s unique behavior in a more colorful way.

3. The software engineer at Google is searching for ___________

Temperature = 0.5:
  "The software engineer at Google is searching for bugs.
Explanation: This is a very common and safe response. "Bugs" is something every software engineer would typically search for, so it’s predictable and straightforward.

Temperature = 1.0:
  "The software engineer at Google is searching for the next big breakthrough in AI while eating pizza.
Explanation: The higher temperature introduces more creativity, mixing in humor and a more casual tone while still staying relevant to the engineer's work.


## 3. Record how the style, randomness, and focus of responses change.
I noticed that with each change in the style and randomness, the responses changed, for p values less than 0.5, the outputs were predictable, focused and slightly creative, and for p values = 0.5, the outputs were balanced, while for p values above 0.5, the outputs were creative and wild. 
