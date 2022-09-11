**Author:** [[Denes Ferenc]] 
**Tags:** #Extracurricular 
**Uniform Resource Locator:**  [https://ruwix.com/]https://ruwix.com/)

---
### Beginner Notation
Algorithms are denoted in Rubik's cube notation.

| Rotation | Letter | Color  |
|:--------:|:------:|:------:|
|  Front   |   F    | White  |
|   Back   |   B    | Yellow |
|   Left   |   L    |  Red   |
|  Right   |   R    | Orange |
|    Up    |   U    | Green  |
|   Down   |   D    |  Blue  | 
- As an example the letter F denotes a clockwise rotation on the the white face.
- Short hand for repetitions of a movement are denoted by appending a number after the letter, such as B2.
- Counterclockwise rotations are denoted by appending an apostrophe to the appropriate letter. An example, F', is a counterclockwise rotation and pronounced "F prime".

### Beginner Method
1. Create a cross on the blue face.
	- This step is easy as there are no any solved pieces to worry about.

2. Solve the blue corners.
3. Solving the second layer is the first step to require the use of algorithms. Firstly, line up an edge piece such that it matches the face closest to you and the other color is one of the faces on the left or right. From there employ one of the following two symmetric algorithms:
	>**Left:** U' L' U L U F U' F'
	>**Right:** U R U' R' U' F' U F

4. Next make another cross, this time on the green face, ignoring for now aligning them with the correct center pieces.
	- There are four permutations which can be proceeded through using this algorithm: **Center Dot -> Backwards "L" Shape -> Horizontal Line -> Cross**
	>F R U R' U' F'

5. Now align the green edges. The following algorithm will swap the edge piece facing you and the one to its left.
	- Keep in mind that this may need to be executed multiple times.
	> R U R' U R U2 R' U
6. Finally, it is time to place the corners in their proper positions.
	- This algorithm cycles the corners with the exception of the Front-Top-Right corner, thus you want to execute it with a correctly positioned corner in Front-Top-Right.
	> U R U' L' U R' U' L
	- If no corners are correctly positioned, execute the algorithm once.
7. Orienting the yellow corners in the most involved step.
	- Place an incorrectly oriented corner in the Front-Top-Right then execute the following algorithm until it is properly oriented (**NOTE:** this will mess up the cube at first.) 
	> R' D' R D 
	
	- Down, away, up, back.
	- Once the corner is correctly oriented, move the top layer and put the next incorrect oriented corner in place. Execute the algorithm, and repeat until all corners are solved.

### More Advanced Notation