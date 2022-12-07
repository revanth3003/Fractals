All fractals arengenerated using turtle pakage

Sierpinski’s Triangle

The technique of subdividing a shape into smaller copies of itself, removing one or more copies, and continuing recursively can be extended to other shapes. 

The Sierpiński triangle is a fractal attractive fixed set with the overall shape of an equilateral triangle, subdivided recursively into smaller equilateral triangles. Start with an equilateral triangle. Subdivide it into four smaller congruent equilateral triangles and remove the central triangle. Repeat step 2 with each of the remaining smaller triangles infinitely. The below figure is the Sierpinski Triangle’s output generated for stage 4
source: https://en.wikipedia.org/wiki/Sierpiński_triangle 

Sierpinski’s Triangle

<img width="172" alt="image" src="https://user-images.githubusercontent.com/114034184/206063929-9ac00f50-974d-4eb7-8572-5de4e8d86a5e.png">

Input  - s - Number of stages or interaction (Example: s = 4) (Should be a positive integer)

[3.9] Sierpinski’s Carpet

The technique of constructing Sierpinski’s carpet is like that of Sierpinski’s Triangle. The construction of the Sierpiński carpet begins with a square. The square is cut into 9 congruent sub squares in a 3-by-3 grid, and the central sub square is removed. The same procedure is then applied recursively to the remaining 8 sub squares and goes infinitely. The below figure is the Sierpinski Carpet’s output generated for stage 2. 
Source: https://en.wikipedia.org/wiki/Sierpiński_carpet

Sierpinski’s Carpet

<img width="192" alt="image" src="https://user-images.githubusercontent.com/114034184/206064072-176a2130-73a9-410b-b00f-c9e61f6d1837.png">

Input  - s - Number of stages or interaction (Example: s = 2) (Should be a positive integer)


 [3.10] Koch Curve/Snowflake

The Koch snowflake can be built up iteratively, in a sequence of stages. The first stage is an equilateral triangle, and each successive stage is formed by adding outward bends to each side of the previous stage, making smaller equilateral triangles. The areas enclosed by the successive stages in the construction of the snowflake converge to 8/5 times the area of the original triangle, while the perimeters of the successive stages increase without bound. Consequently, the snowflake encloses a finite area, but has an infinite perimeter. The below figure is Koch's snowflake generated for stage 3. 
Source: https://en.wikipedia.org/wiki/Koch_snowflake

Koch Curve/Snowflake
<img width="161" alt="image" src="https://user-images.githubusercontent.com/114034184/206064093-57a44f87-bffe-4848-babf-4ee64f6144fd.png">

Input  - s - Number of stages or interaction (Example: s = 2) (Should be a positive integer)

[3.11] Fern Leaf

The fern is a mathematically generated pattern that can be reproducible at any magnification or reduction. Like the Sierpinski triangle, the Barnsley fern shows how graphically beautiful structures can be built from repetitive uses of mathematical formulas with computers.The below matrix figure is Barnsley's matrix of constants whereas f1 (x , y) forms stem, f2 (x , y) forms  successively smaller leaflets, f3 (x , y) forms largest left-hand leaflets and f4 (x , y) form largest right-hand leaflets. (x, y) is randomly generated points.The figure below is the Barnsley’s fern generated for 100,000 random points.
Source: https://en.wikipedia.org/wiki/Barnsley_fern

<img width="258" alt="image" src="https://user-images.githubusercontent.com/114034184/206064132-4ed7575b-a113-49f0-899f-288d53835575.png">

Fern Leaf
<img width="159" alt="image" src="https://user-images.githubusercontent.com/114034184/206064119-09e273fe-2eb0-47db-8964-927680da0de7.png">
Input  - n - Number of stages (Example: n = 100000) (Should be a positive integer) (For better results the points should be more than 100,000)
	 p - probability factor (Generated as Uniform random points (0,1)

[3.12] Fibonacci Series
	
The Fibonacci numbers, commonly denoted Fn , form a sequence, the Fibonacci sequence, in which each number is the sum of the two preceding ones. The sequence commonly starts from 0 and 1. Starting from 0 and 1, the first few values in the sequence are 0, 1, 1, 2, 3, 5, 8, 13, 21, 34,55,89, 144.The figure below is the fibonacci spiral generated for stage 4.
Source: https://en.wikipedia.org/wiki/Fibonacci_number

Fibonacci Spiral
<img width="270" alt="image" src="https://user-images.githubusercontent.com/114034184/206064151-b5f1de9b-11de-4bb1-a65a-584d4131898d.png">
Input  - s - Number of stages or interaction (Example: s = 4) (Should be a positive integer)

[3.13] Pentaflake

A pentaflake, or sierpinski pentagon, is formed by successive flakes of six regular pentagons Each flake is formed by placing a pentagon in each corner and one in the center. Its Hausdorff dimension is equal to log (6) \ log (1+ φ) ≈ 1.8617, where φ= (1+sqrt (5)) / 2 (golden ratio).
The log (6) \ log (1+ φ) is obtained because each iteration has 6 pentagons that are scaled by (1+ φ). The boundary of a pentaflake is the Koch curve of 72 degrees.

There is also a variation of the pentaflake that has no central pentagon. Its Hausdorff dimension equals log (5) \ log (1+ φ) ≈ 1.6723. This variation still contains infinitely many Koch curves, but they are somewhat more visible. The figure below is the pentaflake generated for stage 4.
Source: https://en.wikipedia.org/wiki/N-flake

Pentaflake
<img width="281" alt="image" src="https://user-images.githubusercontent.com/114034184/206064227-2f70b9d6-e084-49a5-a731-f00c0fb19ec4.png">

Input  - s - Number of stages or interaction (Example: s = 4) (Should be a positive integer)
 
