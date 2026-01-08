
# m1a
- Start with index.html
- Has a maxAge query param that default to 9.
- Display "Press Space" in the canvas
- When the user press space
    - Randomly choose N between 3 and maxAge (inclusive) and use speech api to ask
    - "What grade are you in if you are ${N} years old?"
    - Render on a canvas the expression $N - 5.
- When the user type a number, display it in the canvas to the right of the expression, along with =, <, or >.
  - If it's =, then tell the user that that's correct.
    - Go back to "Press Space"
  - Otherwise, tell the user that that's too small or too big and to try again.
    - Reset back to just the expression.