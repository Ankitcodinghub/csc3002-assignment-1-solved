# csc3002-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSC3002 Assignment 1 Solved](https://www.ankitcodinghub.com/product/csc3002-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115797&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3002 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Problem 1

Exercise 2.9 and 2.10:

The combinations function C(n,k) described in this chapter determines the number of ways you can choose k values from a set of n elements, ignoring the order of the elements. If the order of the value matters-so that, in the case of the coin example, choosing a quarter first and then a dime is seen as distinct from choosing a dime and then a quarter-you need to use a different function, which computes the number of permutations. This function is denoted as P(n,k), and has the following mathematical formulation:

Although this definition is mathematically correct, it is not well suited to implementation in practice because the factorials involved can get much too large to store in an integer variable, even when the answer is small. For example, if you tried to use this formula to calculate the number of ways to select two cards from a standard 52 -card deck, you would end up trying to evaluate the following fraction:

even though the answer is the much more manageable 2652(52 × 51).

The C(n,k) function from the text and the P(n,k) function come up often in computational mathematics, particularly in an area called combinatorics, which is concerned with counting the ways objects can be combined.

Write a function permutations (n, k) that computes the P(n,k) function without calling the fact function, and write the files combinatorics.h and combinatorics.cpp for a library that exports the functions permutations and combinations. When you write the implementation, make sure to rewrite the code for the combinations function so that it uses the efficiency enhancements suggested for permutations.

Requirements: Please finish the file combinatorics.cpp according to file combinatorics.h.

Problem 2

Exercise 3.20:

There is no gene for the human spirit. – Tagline for the 1997 film GATTACA

The genetic code for all living organisms is carried in its DNA-a molecule with the remarkable capacity to replicate its own structure. The DNA molecule itself consists of a long strand of chemical bases wound together with a similar strand in a double helix. DNA’s ability to replicate comes from the fact that its four constituent bases-adenosine, cytosine, guanine, and thymine-combine with each other only in the following ways:

• Cytosine on one strand links only with guanine on the other, and vice versa

• Adenosine links only with thymine, and vice versa.

Biologists abbreviate the names of the bases by writing only the initial letter: A,C,G, or T.

Inside the cell, a DNA strand acts as a template to which other DNA strands can attach themselves. As an example, suppose that you have the following DNA strand, in which the position of each base has been numbered as it would be in a C + + string:

Your mission in this exercise is to determine where a shorter DNA strand can attach itself to the longer one. If, for example, you were trying to find a match for the strand

the rules for DNA dictate that this strand can bind to the longer one only at position 1:

By contrast, the strand

matches at either position 2 or position 7.

Write a function

int findDNAMatch (string s1, string s2, int start = 0 ) ;

that returns the first position at which the DNA strand s1 can attach to the strand s2. As in the find method for the string class, the optional start parameter indicates the index position at which the search should start. If there is no match, findDNAMatch should return -1.

Requirements:

Please finish the file FindDNAMatch.cpp according to file FindDNAMatch.h.

Problem 3

Exercise 4.8:

Even though comments are essential for human readers, the compiler simply ignores them. If you are writing a compiler, you therefore need to be able to recognize and eliminate comments that occur in a source file. Write a function

void removeComments (istream &amp; is, ostream &amp; os)

that copies characters from the input stream is to the output stream os, except for characters that appear inside C + + comments. Your implementation should recognize both comment conventions:

• Any text beginning with /? and ending with ?/, possibly many lines later.

• Any text beginning with // and extending through the end of the line.

The real C + + compiler needs to check to make sure that these characters are not contained inside quoted strings, but you should feel free to ignore that detail. The problem is tricky enough as it stands.

Requirements:

Please finish the file RemoveComments.cpp according to RemoveComments.h. You can use the file hello.cpp file(under the res folder in Stanford Library) for testing. The generated results should print in the Stanford console.

Problem 4

Exercise 4.9:

Books were bks and Robin Hood was Rbinhd. Little Goody Two Shoes lost her Os and so did Goldilocks, and the former became a whisper, and the latter sounded like a key jiggled in a lck. It was impossible to read ”cockadoodledoo” aloud, and parents gave up reading to their children, and some gave up reading altogether…. – James Thurber, The Wonderful O,1957

In James Thurber’s children’s story The Wonderful O, the island of Ooroo is invaded by pirates who set out to banish the letter O from the alphabet. Such censorship would be much easier with modern technology. Write a program that asks the user for an input file, an output file, and a string of letters to be eliminated. The program should then copy the input file to the output file, deleting any of the letters that appear in the string of censored letters, no matter whether they appear in uppercase or lowercase form.

As an example, suppose that you have a file containing the first few lines of Thurber’s novel, as follows:

If you run your program with the input

it should write the following file:

If you try to get greedy and banish all the vowels by entering aeiou in response to the prompt, the contents of the output file would be

Requirements:

Please finish the file BanishLetters.cpp according to BanishLetters.h. The test file TheWonderfulO.txt has been provided under the res folder in Stanford Library for testing. The generated new file will existed in the build content named as build-Assignment1-….

Requirements for Assignment

Please submit your finished files together with the project file Assignment1.pro. You should finish each .cpp file according to the problem requirements. The resources and test files are provided under res folder such as hello.cpp and TheWonderfulO.txt. You can use them with relative path directly after you compile the whole project. Finally, please pack your whole project files into a single .zip file, name it using your student ID (e.g. if your student ID is 123456, hereby the file should be named as 123456. zip ), and then submit the .zip file via BB system.

Reminder: For windows users, please switch you input language to English before interacting in Stanford console. Or you will get no response.
