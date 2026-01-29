Algorithm\
**Step 1: Initialization**

- Create a list of files
- Give each file:
  - Risk value
  - Virus status
  - Initial pheromone level
- Create ants for scanning
-----
**Step 2: Ant Movement**

- Each ant chooses an **unscanned file**
- Files with **higher pheromone** have more chance to be selected
- Ant moves to the selected file
-----
**Step 3: Scanning Files**

- Mark the file as scanned
- If virus is found:
  - Increase virus count
  - Mark file as infected
-----
**Step 4: Pheromone Update**

- Increase pheromone on scanned files
- Increase pheromone more if virus is detected
-----
**Step 5: Pheromone Evaporation**

- Reduce pheromone levels slowly
- This avoids focusing on only one file
-----
**Step 6: Best Path Selection**

- Calculate distance of paths taken by ants
- Find the **shortest and best path**
-----
**Step 7: Stop Condition**

- Stop when all files are scanned
- Display:
  - Files scanned
  - Viruses found
  - Best ant path


