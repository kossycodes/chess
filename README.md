# chess game
My goal is to create a multi-player chess game. Built with javascript🤗

# How to play the game
follow the rule, of the game of chess and play yea its that simple☺️🤗

# Challenges
The challenge i faced the most is writing the function to display the available paths for all pieces to move according to the ruleof the chess game.
I used <code>if else statement</code> and <code>For Loop</code> to calculate the space and the possible number of moves for each piece according to the rule of the game
```js
if (item.innerText == `${toggle}bishop`) {


                for (let i = 1; i < 9; i++) {
                    if (i < (900 - aup) / 100 && i < 9 - aside && document.getElementById(`b${a + i * 100 + i}`).innerText.length == 0) {
                        document.getElementById(`b${a + i * 100 + i}`).style.backgroundColor = 'green'
                    }
                    else if (i < (900 - aup) / 100 && i < 9 - aside && document.getElementById(`b${a + i * 100 + i}`).innerText.length !== 0) {
                        document.getElementById(`b${a + i * 100 + i}`).style.backgroundColor = 'green'
                        break
                    }
                }

```

# What i would like to change in future 
- Refactor this app to work with <code>React.js</code>
- Use font-awesome icon to display chess characters instead of the uploaded pictures

# Link
-   Livesite: [Chess Game](https://kossycodes.github.io/chess/)
