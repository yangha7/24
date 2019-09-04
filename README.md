# 24
Explore the game 24

24 is the game I played when I was a kid. By randomly drawing 4 cards from a deck, one can apply +, -, *, / among these numbers to make them 24. Each card (number) must be used and only used once.

Under the current rule of game 24, only two possible computing patterns can be found. (a,b),(c,d) and ((a,b),c),d.

I wrote two seperate functions TwoAndTwo and ThreeAndOne to consider each case. A function Is24(a, b, c, d) is written. If the 4 numbers a, b, c, and d can make 24 based on the rules above, a hint is going to given. If they cannot make 24, it will simply print impossible.

Later, a Function IsGoal(a,b,c,d,goal) is written based on Is24. Here, the goal can be any number other than 24. I wish to use this to explore more about his game, and find why people chose 24, not other numbers.

Also, by setting a, b, c, d to loop among differnt ranges, we can consider only combinations (no order), car plate probability and deck probability. In particular, a trick is used to evaluate the deck probability, such that int(51/4)+1 and int(50/4)+1 can represent two differnt cards with the same number in a deck.

After a detailed exploration setting goal from 0 all the way to 100, I found that 24 is not a magic number. People may have chosen that based on their intuition. 
