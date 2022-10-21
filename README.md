# Algorithms Exploration: Cubing Workflow  
  
  
As a child, I absolutely hated puzzles. In fact, I hated the rubik's cube the most; the thought of simply touching it made me shudder. I believed that if I touched it, the cube's perfectly coloured faces would become distorted and I would never be able to put them back together again. As if solving the cube required casting an impossible magic.  

It took me a long time to gather the courage to solve the rubik's cube. In the hot summer of 2020, I decided that I will attempt to solve the cube by watching a YouTube tutorial. I'm not ashamed to admit that I took three whole days to complete my first solve. I was so happy that day. I knew that if my child self had witnessed this moment, she would be proud of me.   
  I have continued to cube ever since.

Today I can solve the 3×3 rubik's cube in under a minute. Now, I'd like to branch out and tackle a different puzzle, and this assignment is the perfect opportunity for me to develop my cubing abilities. Through this assignment I learned that such thing as a pyraminx exists. I decided to tackle 3 new puzzles: A regular pyraminx, pyraminx duo and lastly pyraminx boomerang. This file's purpose is to display the progression of my cubing skills, the algorithms used to solve the puzzles are mentioned later in the file.
Enjoy :)

**Data retrieved as of 11-10-2022, 11:20 AM**

| Type of puzzle  | Can I solve it? | What is my goal? | 
| ------------- | ------------- | ------------- | 
| Cube (3x3) | Yes  | to solve the cube in under 1 minute  | 
| Pyraminx duo  | Not yet  | to solve the pyraminx duo under 10 seconds  | 
| Pyraminx boomerang  | Not yet  | to solve the pyraminx boomerang under 30 seconds  | 
| Pyraminx | Not yet  | to solve the pyraminx under 30 seconds |  
  
  **Data retrieved as of 20-10-2022, 4:30 PM**
 
 | Type of cube  |Can I solve it? | Did I reach my goal? | What is my next goal? | AO5 (sec) | AO12 (sec) | AO25 (sec) | Best Time  | 
 | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
 | Cube 3x3  | Yes | I successfully reached my goal of solving the cube under a minute during August 2021, one thing I learned is that the type of cube you use really matters, some cubes are more stiff and difficult to play around with. | My next goal is to solve the 3x3 rubik's cube in under 45 seconds. | 1:01.23 | 1:04.77 | 1:05.89 | 53.11 | 
 | Pyraminx duo  | Yes  | I successfully reached my goal of solving the pyraminx duo in under 10 seconds during the first week of starting this assignment. | My next goal is to solve the pyraminx duo within 5 seconds. | 2.92  | 4.78  | 5.43  | 3.34  | 
| Pyraminx boomerang   | Yes | I successfully reached my goal of solving the pyraminx boomerang within 30 seconds yesterday on 19-10-2022. | My next goal is to try and solve the pyraminx boomerang within 15 seconds. | 14.90 | 15.45  | 17.70  | 7.29  |
| Pyraminx  | Yes | I successfully reached my goal of solving the pyraminx at under 30 seconds at the start of the week on 17-10-2022. | My next goal is to solve the pyraminx within 20 seconds. | 18.34  | 20.34  | 19.77  | 18.01  |  

  
  **Algorithm used to solve the 3x3 rubik's cube: Advanced CFOP / Fridrich Method**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. Start by creating a daisy on the top face of the cube, a daisy consists of one yellow piece in the center, and 4 white top-edge pieces on the cube. This can easily be done by performing basic algorithms such as turn, pull towrds, and pull away.  
2. Secondly, move the edge pieces until they match their colour with the center pieces on the side faces of the cube.  
3. Now turn each of the matching top-edge pieces twice in the clockwise direction. After completing this step 4 times you should have a white cross on the bottom face of your cube.  
4. Now look at the top yellow face of your cube and examine it, search for edge pieces that are not yellow. Once you find one, match the top-edge piece's side with its corresponding colour, this action should make an upside down "T" on the respective side of the cube.  
5. Now look at the other two side-faces of the cube and match the it with the colour on the top side of the edge piece.  
6. If the top-edge piece's colour matched with the right side-face then perform the following algorithm: U, R, U, R', U', turn to the side to fix the displaced white piece L', U', L.  
7. If the top-edge piece's colour matched with the left side-face then perform the following algorithm: U', L', U', L, U, turn to the side to fix the displaced white piece R, U, R'.  
8. Perform step 6-7 until the whole first and second layer is solved.
9. Turn the top yellow face until, you either see a straight yellow vertical line. Perform the algorithm: F U R U’ R’ F’.  
10. Now if you see a shape like the head of an arrow, made up of yellow pieces, turn them so they are at the 9 and 12 position on the clock and perform the algorithm: F U R U’ R’ F’.  
11. Now if you see a fish like shape, turn the top face until the fish's mouth is pointing to the bottom left and perform the algorithm: R U R’ U R U2 R’
’.    
12. Perform steps 9-11 until the whole yellow face is solved.  
13. Lastly, lets finish the third layer. By now you should have two corner pieces that match their colour with one of the cube sides; position them together and perform the algorithm: L’ U R U’ L U R’ R U R’ U R U2 R’.  
14. Perform step 13 until all the corner pieces match their corresponding colour.  
15. One face of the cube should be solved, keep that faced straight away from you, and examine the rest of the three face's top layer's middle pieces.  
16. If the top layer's middle pieces are matching in a clockwise manner, perform the algorithm: F2 U R’ L F2 L’ R U F2.  
17. If the top layer's middle pieces are matching in a clockwise manner, perform the algorithm: F2 U’ R’ L F2 L’ R U’ F2.  
18. Now your cube is completed!  
19. > If in any case one face of the cube is not solved in step 15, then perform: F2 U’ R’ L F2 L’ R U’ F2 and continue with the rest of the steps until the cube is solved.  

**Summary of this specific method:** This method is known best for beginners. The first two layers are solved by constructing the foundations for the first two layers, pairing up the pieces, and then placing them around the foundations. Learning the algorithms to solve the cube in two additional phases allows for the final layer to be addressed. Once algorithms have been drilled and the solver has had enough practise, all steps of this method become exceedingly simple and quick to perform.  
For more information and references: https://www.youtube.com/watch?v=R-R0KrXvWbc
  
**Algorithm used to solve the Pyraminx duo:**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. For starters, pick a side on the pyraminx duo and match all the outer edge pieces with one colour, for example, all the edge pieces could be green while the center is yellow.  
2. Now, put this side on the bottom face away from you and fix the top or tip of the triangle pyraminx duo until every side is all matching edge pieces with different center pieces.  
3. Look for the matching side that has the same colour as the side we earlier placed on the bottom. Make sure the sides with pieces that need to switch are at the front.  
4. Now perform the algorithm R', L, R, L'. With this the whole pyraminx duo should be solved!  
For more information and references: https://www.youtube.com/watch?v=xB9OFNyi-Uk


