Objective: Understand how parameters affect output diversity.

    Use the same prompt with temperature = 0.2 and then with temperature = 0.9.

    Repeat with different top-p values (e.g., 0.5 vs 1).

    Record how the style, randomness, and focus of responses change.
**Temperature = 0.2, Top-p = 0.5**  
   Response: Keep learning every day to grow steadily.  

2. **Temperature = 0.2, Top-p = 1**  
   Response: Keep learning every day to grow steadily.  

3. **Temperature = 0.9, Top-p = 0.5**  
   Response: Dive into the adventure of learning, and let curiosity lead your path!  

4. **Temperature = 0.9, Top-p = 1**  
   Response: Dive into the adventure of learning, and let curiosity lead your path!  

### Analysis
- Lower temperature (0.2) produces deterministic and concise responses.  
- Higher temperature (0.9) produces more creative and expressive responses.  
- Top-p affects randomness less when temperature is high in these examples.  
- Observation: Parameters help control style, focus, and variability in outputs.
