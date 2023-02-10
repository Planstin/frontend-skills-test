# Names Exercise
In this exercise you'll create a simple table to display various names with a calculated score. The requirements are as follows:

### Rules of the test:
- You can reference online docs , libaries etc. as needed, ask questions to interviewer(s) for help but no live assitance.
- Use a Frontend Library / Framework of your choice: Angular, Vue, React, Ember, etc.
- For your convenience we have a base install of Angular, Vue, React, Ember pre-installed in this repo.
- We run on node.js 14
- You will have 1 hour to perform the test.
- Do your best and have fun.

### Application Requirements
- [ ] Create a text input for adding names to the table.
  - Names can be submitted through both/either a keypress (enter) or button click.
- [ ] Create a table with columns for: Row Number, Name, & Score. 
  - Names added through input display in table by alphabetical order. 
  - The third column, <b>Score</b>, should display a value calculated on the name.
    - Scoring is defined in the section [below](#scoring-calculations).  
- [ ] Create a footer at the bottom of the table with a value that is the sum of the entire score column.
- [ ] Add the ability to remove any row in the list

### Scoring Calculations:
 - <b>Score</b>: the sum of each alphabetic character of the name multiplied by it's (index + 1) 
    - For example in `names.json`, the name `COLIN` is 938th in the list after being sorted. It has an alphabetic value of `3 + 15 + 12 + 9 + 14 = 53`, thus the score would be `938 * 53 = 49714`.
 - <b>Alphabetical Character</b>: Its value is its place in the alphabet.
    - The example of `COLIN` 
      - `C` is the 3rd letter in the alphabet 
      - `O` is the 15th letter in the alphabet

### Bonus Objectives
- Extra: Create a button that bulk adds the provided list of names to the table `names.json`
- Extra: add the ability to multi sort by name and score

### Notes
- If you have any extra time feel free to add any extra features or improvements you would like.
- A JSON list of the alphabet, `alphabet.json`, has been added for your convenience. 
