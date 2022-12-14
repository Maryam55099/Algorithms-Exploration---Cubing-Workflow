# Algorithms Exploration: Cubing Workflow  
  
  
As a child, I absolutely hated puzzles. In fact, I hated the Rubik's cube the most; the thought of simply touching it made me shudder. I believed that if I touched it, the cube's perfectly coloured faces would become distorted and I would never be able to put them back together again. As if solving the cube required casting impossible magic.  

It took me a long time to gather the courage to solve the Rubik's cube. In the hot summer of 2020, I decided that I will attempt to solve the cube by watching a YouTube tutorial. I'm not ashamed to admit that I took three whole days to complete my first solve. I was so happy that day. I knew that if my child self had witnessed this moment, she would be proud of me.  
I have continued to cube ever since.  

Today I can solve the 3×3 Rubik's cube in under a minute. Now, I'd like to branch out and tackle a different puzzle, and this assignment is the perfect opportunity for me to develop my cubing abilities. Through this assignment, I learned that such a thing as a pyraminx exists. I decided to tackle 3 new puzzles: A regular pyraminx, a pyraminx duo and lastly pyraminx boomerang. This file's purpose is to display the progression of my cubing skills, the algorithms used to solve the puzzles are mentioned later in the file.   
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
 | Cube 3x3  | Yes | I successfully reached my goal of solving the cube in under a minute in August 2021, one thing I learned is that the type of cube you use really matters, some cubes are more stiff and more difficult to play around with. | My next goal is to solve the 3x3 rubik's cube in under 45 seconds. | 1:01.23 | 1:04.77 | 1:05.89 | 53.11 | 
 | Pyraminx duo  | Yes  | I successfully reached my goal of solving the pyraminx duo in under 10 seconds during the first week of starting this assignment. | My next goal is to solve the pyraminx duo within 5 seconds. | 2.92  | 4.78  | 5.43  | 3.34  | 
| Pyraminx boomerang   | Yes | I successfully reached my goal of solving the pyraminx boomerang within 30 seconds yesterday, 19-10-2022. | My next goal is to try and solve the pyraminx boomerang within 15 seconds. | 14.90 | 15.45  | 17.70  | 7.29  |
| Pyraminx  | Yes | I successfully reached my goal of solving the pyraminx in under 30 seconds at the start of the week on 17-10-2022. | My next goal is to solve the pyraminx within 20 seconds. | 18.34  | 20.34  | 19.77  | 18.01  |  

Official Recorded Solve for the Regular Pyraminx: held by Mr. Osudar (recorded as of 18-10-2022)
|   | Time (sec) |
| ----| ---------| 
| 1 | 1:40.10 |
| 2  | 34.32 | 
| 3  | 26.47 |  
| 4  | 42.387|  
| 5  | 30.654 | 
| AO5  | 35.787 |  

**ALGORITHMS:**  
  **Algorithm used to solve the 3x3 rubik's cube: Advanced CFOP / Fridrich Method**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. Start by creating a daisy on the top face of the cube, a daisy consists of one yellow piece in the center and 4 white top-edge pieces on the cube. This can easily be done by performing basic algorithms such as turn, pull towards, and pull away.  
2. Secondly, move the edge pieces until they match their colour with the centrepieces on the side faces of the cube.  
3. Now turn each of the matching top-edge pieces twice in the clockwise direction. After completing this step 4 times you should have a white cross on the bottom face of your cube.  
4. Now look at the top yellow face of your cube and examine it, search for edge pieces that are not yellow. Once you find one, match the top-edge piece's side with its corresponding colour, this action should make an upside-down "T" on the respective side of the cube.  
5. Now look at the other two side-faces of the cube and match them with the colour on the top side of the edge piece.  
6. If the top-edge piece's colour matches with the right side-face then perform the following algorithm: U, R, U, R', U', turn to the side to fix the displaced white piece L', U', L.  
7. If the top-edge piece's colour matched with the left side-face then perform the following algorithm: U', L', U', L, U, turn to the side to fix the displaced white piece R, U, R'.
8. Perform steps 6-7 until the whole first and second layer is solved.  
9. Turn the top yellow face until you either see a straight yellow vertical line. Perform the algorithm: F U R U’ R’ F’.  
10. Now if you see a shape like the head of an arrow, made up of yellow pieces, turn them so they are at the 9 and 12 positions on the clock and perform the algorithm: F U R U’ R’ F’.  
11. Now if you see a fish-like shape, turn the top face until the fish's mouth is pointing to the bottom left and perform the algorithm: R U R’ U R U2 R’ ’.  
12. Perform steps 9-11 until the whole yellow face is solved.  
13. Lastly, let's finish the third layer. By now you should have two corner pieces that match their colour with one of the cube sides; position them together and perform the algorithm: L’ U R U’ L U R’ R U R’ U R U2 R’.   
14. Perform step 13 until all the corner pieces match their corresponding colour.  
15. One face of the cube should be solved, keep that face straight away from you, and examine the rest of the three face's top layer's middle pieces.  
16. If the top layer's middle pieces are matching in a clockwise manner, perform the algorithm: F2 U R’ L F2 L’ R U F2.  
17. If the top layer's middle pieces are matching in a clockwise manner, perform the algorithm: F2 U’ R’ L F2 L’ R U’ F2.  
18. Now your cube is completed!

19. > If in any case one face of the cube is not solved in step 15, then perform: F2 U’ R’ L F2 L’ R U’ F2 and continue with the rest of the steps until the cube is solved.  

**Summary of this Method:** This method is known best for beginners. The first two layers are solved by constructing the foundations for the first two layers, pairing up the pieces, and then placing them around the foundations. Learning algorithms to solve the cube in two additional phases allows for the final layer to be addressed. Once algorithms have been drilled and the solver has had enough practise, all steps of this method become exceedingly simple and quick to perform.  
For more information and references: https://www.youtube.com/watch?v=R-R0KrXvWbc
  
**Algorithm used to solve the Pyraminx duo:**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. For starters, pick a side on the pyraminx duo and match all the outer edge pieces with one colour, for example, all the edge pieces could be green while the center is yellow.  
2. Now, put this side on the bottom face away from you and fix the top or tip of the triangle pyraminx duo until every side is all matching edge pieces with different centrepieces.  
3. Look for the matching side that has the same colour as the side we earlier placed on the bottom. Make sure the sides with pieces that need to switch are at the front.  
4. Now perform the algorithm R', L, R, L'. With this, the whole pyraminx duo should be solved!  
For more information and references: https://www.youtube.com/watch?v=xB9OFNyi-Uk  

**Algorithm used to solve the Pyraminx boomerang:**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. Firstly perform different algorithms to solve one side of the triangle puzzle. This solved side will be placed away from you.  
2. Secondly, arrange the sides in a way that one side piece with two different colours is facing away from you respective to the solved side on the bottom.   
3. Now, perform the algorithm: R, L', R, L', R.  At this point you should two sides of the triangle solved, the one on the bottom plus the 3 sides at the top front.  
4. Now, repeat step 2 and perform the following algorithm: R, L', R, L', R.  
5. At this point, the Pyraminx boomerang should be solved completely!  

_Reference video not available as this method was taught to me by Mr. Osudar in class._ 

**Algorithm used to solve the Pyraminx (regular):**  
> prior knowledge of cubing algorithms and cube faces is required.  
1. Firstly pick a face of the triangle that you want to solve, now examine and play with it until you have 3 matching coloured centrepieces.  
2. For functional purposes turn the corners of your triangle to match the colour of the centrepieces.  
3. Now, place this face on the bottom and search the top of the triangle for the same coloured pieces to move to the bottom face.  
4. Once you find one, figure out whether it's on the right or left.  
5. If it's on the right, turn the coloured piece until its opposite coloured piece matches with its corresponding colour and then perform the algorithm: L', U, R'.  
6. If it's on the left, turn the coloured piece until its opposite coloured piece matches with its corresponding colour and then perform the algorithm: R, U', L.  
7. Perform steps 4-6 as many times as you want until all the pieces belong to their corresponding coloured faces.  
8. Lastly, sometimes you need to turn the tip and first layer of the triangle to match the last layer to complete the Pyraminx.  
For more information and references: https://www.youtube.com/watch?v=2H0FUvaaUsI&t=1s

**AN INTELLECTUAL QUESTION: HOW DOES CUBING RELATE TO MATH AND COMPUTER SCIENCE?/PROGRAMMING**  
Rubik's Cube and mathematics have a number of connections. Rubik's Cube ties to arithmetic concepts like fractions, ratios, and proportional reasoning because it can be used to grasp surface area and volume as well as show a net of a familiar, three-dimensional solid. Second, as is common knowledge, the cube is a riddle of colour combinations, and combinations are studied in number theory and algebra, perhaps also in probability theory and other fields. All these are components of Math. Thirdly, let’s discuss how cubing is related to programming.  
Although cubing and coding/programming are undoubtedly two very different tasks, they both call for the effective use of algorithms and problem-solving abilities. An algorithm is a list of instructions used in computer science to solve problems or carry out activities based on knowledge of potential solutions. Similar to this, algorithms in cubing are a set of moves used to solve a cube or create interesting patterns. Thus, cubing has applications in both mathematics and computer science.  
Thank you for reading :)  
  
  
**References:**
Denning, P. (2016, September 21). CAN A RUBIK'S CUBE TEACH YOU PROGRAMMING? BLOG@UBIQUITY. https://blog.ubiquity.acm.org/can-a-rubiks-cube-teach-you-programming/  
der Vieren, D. Van. (2019, May 28). Using Rubik's Cubes to Teach Math. Edutopia. https://www.edutopia.org/article/using-rubiks-cubes-teach-math  
Different Rubik's Cube Solving Methods. (n.d.). Ruwix. https://ruwix.com/the-rubiks-cube/different-rubiks-cube-solving-methods/  
How to Solve a Rubik's Cube | WIRED. (2019, September 5). Youtube. https://www.youtube.com/watch?v=R-R0KrXvWbc  
How to Solve the Pyraminx Duo [Beginner Method]. (2015, May 19). Youtube. https://www.youtube.com/watch?v=xB9OFNyi-Uk  
Pyraminx Layer By Layer | Easy Beginner's Tutorial. (2019, June 29). Youtube. https://www.youtube.com/watch?v=xIQtn2qazvg&t=4s  
Rubik's Cube. (n.d.). The Strong National Museum of Play. https://www.museumofplay.org/toys/rubiks-cube/#:~:text=Hungarian%20design%20teacher%20and%20serious,it%20in%20stores%20in%201980  
7 Benefits of Rubik's Cubes on Mental Health. (2022, June 23). HealthFitnessRevolution. https://www.healthfitnessrevolution.com/7-benefits-of-rubiks-cubes-on-mental-health/  
What a Rubik's Cube can teach you about Programming. (2015, March 17). Medium. https://medium.com/hootsuite-engineering/what-a-rubiks-cube-can-teach-you-about-programming-82f54a6be69c  




