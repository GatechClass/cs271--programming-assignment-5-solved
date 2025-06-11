# cs271--programming-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CS271- Programming Assignment 5 Solved](https://mantutor.com/product/cs271-programming-assignment-5-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;74586&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS271- Programming Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<strong>Objectives</strong>:

<ol>
<li>using indirect addressing</li>
<li>passing parameters</li>
<li>generating “random” numbers</li>
<li>working with arrays</li>
</ol>
<strong>&nbsp;</strong>

<strong>Description</strong>:

Write and test a <em>MASM</em> program to perform the following tasks:

<ol>
<li>Introduce the program.</li>
<li>Get a user <em>request</em> in the range [<em>min </em>= 10 .. <em>max </em>= 200].</li>
<li>Generate <em>request</em> random integers in the range [<em>lo </em>= 100 .. <em>hi </em>= 999], storing them in consecutive elements of an <em>array</em>.</li>
<li>Display the list of integers before sorting, 10 numbers per line.</li>
<li>Sort the list in descending order (i.e., largest first).</li>
<li>Calculate and display the median value, rounded to the nearest integer.</li>
<li>Display the sorted list, 10 numbers per line.</li>
</ol>
<strong>&nbsp;</strong>

<strong>Requirements</strong>:

<ol>
<li>The title, programmer’s name, and brief instructions must be displayed on the screen.</li>
<li>The program must validate the user’s request.</li>
<li><em>min</em>, <em>max</em>, <em>lo</em>, and <em>hi</em> must be declared and used as global <u>constants</u>. Strings may be declared as global variables or constants.</li>
<li>The program must be constructed using procedures. At least the following procedures are required: A. main
<ol>
<li>introduction</li>
<li>get data {parameters: <em>request</em> (reference)}</li>
<li>fill array {parameters: <em>request</em> (value), <em>array</em> (reference)}</li>
<li>sort list {parameters: <em>array</em> (reference), <em>request</em> (value)}</li>
<li>exchange elements (for most sorting algorithms): {parameters: <em>array</em>[i] (reference), <em>array</em>[j] (reference), where <em>i</em> and <em>j</em> are the indexes of elements to be exchanged} F. display median {parameters: <em>array</em> (reference), <em>request</em> (value)}</li>
<li>display list {parameters: <em>array</em> (reference), <em>request</em> (value), <em>title</em> (reference)}</li>
</ol>
</li>
<li>Parameters must be passed by value or by reference <u>on the system stack</u> as noted above.</li>
<li>There must be just one procedure to display the list. This procedure must be called twice: once to display the unsorted list, and once to display the sorted list.</li>
<li>Procedures (except main) should not reference .data segment variables by name. <em>request</em>, <em>array</em>, and titles for the sorted/unsorted lists should be declared in the .data segment, but procedures must use them as parameters.&nbsp; Procedures may use local variables when appropriate.&nbsp; Global <u>constants</u> are OK.</li>
<li>The program must use appropriate addressing modes for array elements.</li>
<li>The two lists must be identified when they are displayed (use the <em>title</em> parameter for the <em>display</em> procedure).</li>
<li>The program must be fully documented. This includes a complete header block for the program and for each procedure, and a comment outline to explain each section of code.</li>
<li>The code and the output must be well-formatted.</li>
<li>Submit your text code file (.asm) to Canvas by the due date.</li>
</ol>
<strong>Extra Credit </strong>(Be sure to describe your extras in the program header block)<strong>:</strong>

<ol>
<li>Display the numbers ordered by column instead of by row.</li>
<li>Use a recursive sorting algorithm (e.g., <em>Merge Sort</em>, <em>Quick Sort</em>, <em>Heap Sort</em>, etc.).</li>
<li>Implement the program using floating-point numbers and the floating-point processor.</li>
<li>Generate the numbers into a file; then read the file into the array.</li>
<li>Others?</li>
</ol>
To ensure you receive credit for any extra credit options you did, you must add one print statement to your program output PER EXTRA CREDIT which describes the extra credit you chose to work on. You will not receive extra credit points unless you do this. The statement must be formatted as follows…

–Program Intro–

<h2>**EC: DESCRIPTION –Program prompts, etc—</h2>
<strong>&nbsp;</strong>

<strong>Notes</strong>:

<ol>
<li>The <u>Irvine library</u> provides procedures for generating random numbers. Call <em>Randomize</em> <u>once</u> at the beginning of the program (to set up so you don’t get the same sequence every time), and call <em>RandomRange</em> to get a pseudo-random number.&nbsp; (See the documentation in Lecture slides.)</li>
<li>The <em>Selection Sort</em> is probably the easiest sorting algorithm to implement. Here is a version of the descending order algorithm, where <em>request</em> is the number of <em>array</em> elements being sorted, and <em>exchange</em> is the code to exchange two elements of <em>array</em>:</li>
</ol>
<strong>for(k=0; k&lt;request-1; k++) { </strong>

<strong>&nbsp;i = k; </strong>

<strong>&nbsp;for(j=k+1; j&lt;request; j++) { </strong>

<strong>&nbsp; if(array[j] &gt; array[i]) </strong>

<strong>&nbsp;&nbsp; i = j; </strong>

<strong>&nbsp;} </strong>

<strong>&nbsp;exchange(array[k], array[i]); </strong>

<strong>} </strong>

<ol start="3">
<li>The median is calculated after the array is sorted. It is the “middle” element of the sorted list.&nbsp; If the number of elements is even, the median is the average of the middle two elements (may be rounded).</li>
</ol>
<strong>Example</strong> (user input is in <strong><em>italics</em></strong>)<strong>:</strong><strong>&nbsp;</strong>

<strong>Sorting Random Integers&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Programmed by Road Runner This program generates random numbers in the range [100 .. 999], displays the original list, sorts the list, and calculates the median value.&nbsp; Finally, it displays the list sorted in descending order. </strong>

<strong>How many numbers should be generated?</strong>

<strong>Invalid input&nbsp; </strong>

<strong>How many numbers should be generated?&nbsp;</strong>

<strong>The unsorted random numbers: </strong>

<strong>680 329 279 846 123 101 427 913 255 736 </strong>

<strong>431 545 984 391 626 803 </strong>

<strong>The median is&nbsp;</strong>

<strong>&nbsp;</strong>
