
Let's take RIT (https://github.com/ogrnv/random-intelligence-tests) sample tasks of different complexity and compare human results with results of AAC - anticipating algorithm code (https://github.com/ogrnv/Anticipating-algorithm-for-solving-tasks-of-random-intelligence-tests) and Monte Carlo (MC) algorithm (https://github.com/ogrnv/Creating-sample-means-for-measurement-standards-of-intelligence).

For example, these are mean values of moves per step in at least 130 tests:

the board 8x8, 42 chips of 7 types, 5 rounds x 12 steps in a round:
 
HM  2.8112  
AAC 3.19098  
MC  4810.561

2.8112/3.19098=0.881
 
the board 8x8, 59 chips of 7 types, 5 rounds x 12 steps in a round:
 
HM  4.1397  
AAC 4.4658  
MC  1587.414

4.1397/4.4658=0.927

Considering that LLMs use human algorithms to generate AACode, the following improvement in results (without human assistance) will show the capabilities of AGI.

When LLM tried to pass Random Intelligence Test (https://github.com/ogrnv/random-intelligence-tests) without coding they got much worse results:<br>for 8x8 board, **2** chip types, 54 chips (in case of unallowable changes made by an AI, it received an error message and went back one move, so such errors were not taken into account):  

Precision 1*2:  

10 Aug 2025 Grog4: "Grok was unable to reply"  
08 Aug 2025 GPT-5(Smart) 1000=1000x2/2  
01 Apr 2025 Gemini 2.5 PRO (Experimental) 1000=1000x2/2 (without any unallowable changes)  
28 Jan 2025 DeepSeek-R1 667=1000x2/3  
06 Oct 2024 mistral-large-2-instruct 400=1000x2/5  
13 Sept 2024 OpenAI-O1-Preview 250=1000x2/8 (without any unallowable changes)  
06 Sept 2024 mistral-large-2-instruct 500=1000x2/4  
07 Sept 2024 ChatGPT-4o mini 400=1000x2/5  

Precision 1*1 (too many moves in 2th step):  

18 Aug 2025 Qwen3-235B-A22B Thinking is off 1000=1000x1/1  
23 Nov 2024 Llama-3.2-90B-Vision-Instruct 250=1000/4  
06 Oct 2024 ChatGPT-4o mini 1000=1000x1/1  
22 Sept 2024 Jamba-1_5-large-instruct 1000=1000x1/1  
27 Sept 2024 Nemotron-4-340b-instruct 333=1000x1/3  
05 Sept 2024 llama-3.1-405b-instruct 167=1000/6
