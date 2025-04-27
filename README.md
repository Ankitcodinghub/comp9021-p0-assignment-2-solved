# comp9021-p0-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COMP9021 P0 Assignment 2 Solved](https://www.ankitcodinghub.com/product/comp9021-principles-of-programming-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124403&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9021 P0 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

1. General Matters

1.1 Aim

The purpose of this assignment is to:

• Develop your problem-solving skills.

• Design and implement the solution to a problem in the form of a medium sized Python program.

• Analyse the various features of a labyrinth, represented by a particular coding of its basic elements

into numbers, from the set Assignment Project Exam Help{0, 1, 2, 3} only, stored in a text file.

• Check that the input text file is correct and represents a labyrinth.

• Use object-oriented programming.

1.2 Marking

Your program will be tested against several inputs. For each test, the auto-marking script will let your program run for 30 seconds. The outputs of your program should be exactly as indicated.

Please make sure not to change the filename labyrinth.py while submitting by clicking on [Mark] button in Ed. It is your responsibility to check that your submission did go through properly using Submissions link in Ed otherwise your mark will be zero for Assignment 2.

2. Description

The representation of the labyrinth is based on a coding with only the four digits 0, 1, 2 and 3 such that:

• 0 codes points that are connected to neither their right nor their below neighbours:

• 1 codes points that are connected to their right neighbours but not to their below ones:

• 2 codes points that are connected to their below neighbours but not to their right ones:

• 3 codes points that are connected to both their right and below neighbours:

A point that is connected to none of their left, right, above, and below neighbours represents a pillar:

Analysing the labyrinth will also allow to represent:

• cul-de-sac:

• entry-exit path:

3. Examples

3.1 First Example

The file named labyrinth_1.txt contains the following:

1 0 2 2 1 2 3 0

3 2 2 1 2 0 2 2

3 0 1 1 3 1 0 0

2 0 3 0 0 1 2 0

3 2 2 0 1 2 3 2

1 0 0 1 1 0 0 0

As per the coding above, Assignment Project Exam Helplabyrinth_1.txt will look like the following:

Here is a possible interaction:

3.2 Second Example

The file named labyrinth_2.txt

022302120222

222223111032

301322130302

312322232330

001000100000

As per the coding above, labyrinth_2.txt will look like the following:

Assignment Project Exam Help

3.3 Third Example

The file named labyrinth_3.txt

31111111132

21122131202

33023022112

20310213122

31011120202

21230230112

30223031302

03122121212

22203110322

22110311002

11111101110

As per the coding above, labyrinth_3.txt will look like the following:

Assignment Project Exam Help

Here is a possible interaction:

3.4 Fourth Example

The file named labyrinth_4.txt

111120

112020

002020

002010

001110

As per the coding above, labyrinth_4.txt will look like the following:

Assignment Project Exam Help

Here is a possible interaction:

3.5 Fifth Example

The file named labyrinth_5.txt contains the following:

1 1 2 1 12

1 1 0

As per the coding above, labyrinth_5.txt will look like the following:

Assignment Project Exam Help

3.6 Sixth Example

The file named labyrinth_6.txt contains the following:

0111221210021212201201323330200

1131011210301210323130331302310

3300200323203011010332232320332

2330312230220302032203223112310

1211020213223110101302032332212

1112222331300131013312312223130

1110120222130303102210113130100

0020320223200020113011131202302

3213100301021111202122030110112

1200320130030313001031302312110

0310130300203000312021011212020

3131210323320222322212332031120

2021033213003230103112331130222

1013300313133312220131222100010

1231322020123133221023110302002Assignment Project Exam Help

3322231133223020311032001102310

2323101332332011010132023031132

2200112102133112231003320012120

2311003320123302322223032120112

0201320233130133202333323012120

2032100103021312110202200332310

3211202310233321202022122021022

1200330103010322222131033003000

1121200200313110310030131100332

0012021023310003332301123031222

0120302110232113312232012023020

2303222021330232031311210131312

0101112200130031003120203121102

2012100113233120321011002012220

0010322001332202013202312122110

0213000131303132112301110130112

1222303101032032301032210302110

1220131300113200003021222120012

1333010013001231321110022323022

3021223221133030131221100102210

2013320130211320203021000311312

0303003010033021320232203222020

2030233001202311110121110133220

1001011011001101100000010100100

As per the coding above, labyrinth_6.txt will look like the following:

Here is a possible interaction:

4. Detailed Description

4.1 Input

The input is expected to consist of ydim lines of xdim members of {0, 1, 2, 3}, where x dim and ydim are at least equal to 2 and at most equal to 31 and 41, respectively, with possibly lines consisting of spaces only that will be ignored and with possibly spaces anywhere on the lines with digits.

The xth digit n of the yth line, with 0 ≤ x &lt; xdim and 0 ≤ y &lt; ydim, is to be:

• associated with a point situated x * 0.5 cm to the right and y * 0.5 cm below an origin,

• connected to the point 0.5 cm to its right if n = 1 or n = 3, and

• connected to the point 0.5 cm below itself if n = 2 or n = 3.

The last digit on every line with digits (that is, not on blank lines) cannot be equal to 1 or 3, and the digits on the last line with digits cannot be equal to 2 or 3, which ensures that the input encodes a labyrinth, that is, a grid of width (xdim – 1) * 0.5 cm and of height (ydim – 1) * 0.5 cm (hence of maximum width 15 cm and of maximum height 20 cm), with possibly gaps on the sides and inside.

A point not connected to any of its neighbours is thought of as a Assignment Project Exam Helppillar and a point connected to at least one of its neighbours is thought of as part of a wall.

4.2 Output

Consider executing from the Python prompt the statement from labyrinth import * followed by the statement lab = Labyrinth(filename). In case filename does not exist in the working directory, then Python will raise a FileNotFoundError exception, that does not need to be caught. Assume that filename does exist (in the working directory). If the input is incorrect in that it does not contain only digits in {0, 1, 2, 3} besides spaces, or in that it contains either too few or too many nonblank lines, or in that some nonblank lines contain too many or too few digits, or in that two of its nonblank lines do not contain the same number of digits, then the effect of executing lab = Labyrinth(filename) should be to generate a LabyrinthError exception that reads:

If the previous conditions hold but the further conditions spelled out above for the input to qualify as a labyrinth (that is, the condition on the last digit on every line with digits and the condition on the digits on the last line) do not hold, then the effect of executing lab = Labyrinth(filename) should be to generate a LabyrinthError exception that reads:

If the input is correct and represents a labyrinth, then lab = Labyrinth(filename) followed by lab.display_features() should have the effect of outputting the following:

1. the number of gates, that is, the number of consecutive points on one of the four sides of the labyrinth that are not connected,

2. the number of sets of connected walls, 3. the number of inner points that cannot be accessed from any gate, starting from the point in the

middle of a gate and going from inner points to neighbouring inner points, Assignment Project Exam Help

4. the number of maximal areas that can be accessed from at least one gate (the number of accessible inner points is at most equal to the number of gates),

6. the number of entry-exit paths with no intersections not to cul-de-sacs consisting of a maximal set S of connected inner points that go from a gate to another (necessarily different) gate and such that for all points p in S, there is only one way to move on from p without getting back and without entering a cul-de-sac, in other words, the resulting path is choice-free, that is, such that leaving the path, at any inner point where that is possible, immediately leads into a cul-de-sac.

The above should be displayed exactly as described below.

A first line that reads one of:

The labyrinth has no gate.

The labyrinth has a single gate.

The labyrinth has N gates.

with N an appropriate integer at least equal to 2.

A second line that reads one of:

The labyrinth has no wall.

The labyrinth has walls that are all connected.

The labyrinth has N sets of walls that are all connected.

with N an appropriate integer at least equal to 2.

A third line that reads one of:

The labyrinth has no inaccessible inner point.

The labyrinth has a unique inaccessible inner point. The labyrinth has N inaccessible inner points.

with N an appropriate integer at least equal to 2.

A fourth line that reads one of:

The labyrinth has no accessible area.

The labyrinth has a unique accessible area. Assignment Project Exam Help The labyrinth has N accessible areas.

A fifth line that reads one of:

The labyrinth has accessible cul-de-sacs that are all connected.

The labyrinth has N sets of accessible cul-de-sacs that are all connected.

with N an appropriate integer at least equal to 2.

A sixth line that reads one of:

The labyrinth has no entry-exit path with no intersection not to cul-de-sacs.

The labyrinth has a unique entry-exit path with no intersection not to cul-de-sacs. The labyrinth has N entry-exit paths with no intersections not to cul-de-sacs.

with N an appropriate integer at least equal to 2.
