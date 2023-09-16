# HungerGames
MC bots on the hunger games

## Prompt Reasoning for Actions with LLMs
Made with Palm 2
Example
```
Instruction: You pick between options [a] and [b] {{RETURN ONLY THE LETTER, NO OTHER WORDS}} [a] or [b].
Situation: you are in minecraft hunger games, and you need to survive, pick from [a] diamond sword [b] wood sword
Output: b
```

Others
```
Instruction: You are in the minecraft hunger games, choose the answers that you think will make you win the game. When pick In MCQs {{RETURN ONLY THE LETTER, NO OTHER WORDS}}.
Situation: you are in minecraft hunger games, and you are close to starvation, pick from [a] diamond sword [b] a stack of bread
Output: b

Instruction: You are in the minecraft hunger games, choose the answers that you think will make you win the game. When picking In MCQs {{RETURN ONLY THE LETTER, NO OTHER WORDS}} otherwise {{ANSWER NORMALLY}}.
Situation: you are in minecraft hunger games, and you have just begun, make a list of steps to win.
Output: 
1. **Find a weapon**. You need a weapon to protect yourself from other players. You can find weapons in chests, villages, or by killing mobs. 
2. **Build a shelter**. You need a place to hide from other players and to sleep at night. You can build a shelter out of wood, stone, or dirt. 
3. **Find food**. You need to eat to survive. You can find food in chests, villages, or by killing mobs. 
4. **Stay hydrated**. You need to drink water to stay hydrated. You can find water in rivers, lakes, or by digging wells. 
5. **Avoid other players**. The other players are your enemies. You need to avoid them or kill them if you want to win. 
6. **Win the game**. The last player standing wins the game.
```

## Next Challenges
 - converting Natural Language insturctions to MCQ format for all answers
 - use feedback loop to develop plans and reasoning with context awareness
 - Describe minecraft visual world in text-format
 - implement in minecraft environment
