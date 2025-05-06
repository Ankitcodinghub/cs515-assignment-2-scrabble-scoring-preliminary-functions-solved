# cs515-assignment-2-scrabble-scoring-preliminary-functions-solved
**TO GET THIS SOLUTION VISIT:** [CS515 Assignment 2-Scrabble scoring — Preliminary Functions Solved](https://www.ankitcodinghub.com/product/cs515-assignment-2-scrabble-scoring-preliminary-functions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96649&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS515 Assignment 2-Scrabble scoring -- Preliminary Functions Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Scrabble scoring — Preliminary Functions

Write the following functions:

<ul>
<li>letterScore(letter, scorelist) takes as input a single letter string called letter and a list where each element in that list is itself a list of the form [character,

value] where character is a single letter and value is a number associated with that letter (e.g. it’s scrabble score). The letterScore function then returns a single number, namely the value associated with the given letter. For example, you can cut and paste the following scrabble score list into your hw2.py program file. This function is allowed to crash if the letter is not in the scorelist.

scrabbleScores = [ [“a”, 1], [“b”, 3], [“c”, 3], [“d”, 2], [“e”, 1], [“f”, 4], [“g”, 2], [“h”, 4], [“i”, 1], [“j”, 8], [“k”, 5], [“l”, 1], [“m”, 3], [“n”, 1], [“o”, 1], [“p”, 3], [“q”, 10], [“r”, 1], [“s”, 1], [“t”, 1], [“u”, 1], [“v”, 4], [“w”, 4], [“x”, 8], [“y”, 4], [“z”, 10] ]

If you include this in your file (outside of any function you define – for example right after the header comments in your file), then scrabbleScores is a “global variable”; it can be referred to by any function defined in that file and, more importantly for this example, it can be used once we load in that file.

&gt;&gt;&gt; letterScore(“c”, scrabbleScores) 3

&gt;&gt;&gt; letterScore(“a”, scrabbleScores) 1
</li>
<li>wordScore(S, scorelist) should take as input a string S and a scorelist in the format described above, which will have only lowercase letters, and should return as output the scrabble score of that string.

Here are some examples:

&gt;&gt;&gt; wordScore(‘spam’, scrabbleScores)

8

&gt;&gt;&gt; wordScore(“wow”, [[‘o’, 10], [‘w’, 42]]) 94
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
CS 115 – Hw 2

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Scrabble Scoring

Your ultimate task here is to write a function that takes as input a “rack” – a list of letters – and returns the highest scoring word that can be made with those letters. This is the key ingredient in a computerized Scrabble game! Note about Scrabble: in this game, each letter in the rack can only be used once. For example, if the rack is [‘w’, ‘y’, ‘l’, ‘e’, ‘l’, ‘o’] then you cannot make the word ‘wow’ because the rack only has one ‘w’.

In this problem, you may use recursion as well as the built-in higher-order functions map, filter, and reduce. In fact, if you write a function that needs to process a long list (e.g. a dictionary) with more than a few hundred items in it, you are much better off letting map, filter, or reduce cruise through those lists since they have been optimized to work very fast.

There will be a few places where using anonymous functions (lambda) will be convenient.

One of the objectives of this problem is to have you think about designing a more complicated program that involves several functions. You have complete autonomy in deciding what functions to write in order to reach the ultimate goal (see more on the two required functions below). Try to think carefully about which functions you will need and try to implement those functions so that they are as simple and clean as possible. Don’t settle for the first thing you think of. Strive to make your program simple and well organized.

Our sample solution has fewer than 9 functions, two of which we copied from our solution to the Recursion Muscles lab. The remaining 7 (or so) functions range from one to four lines of code per function. You are not required to have the same number of functions and you may have a few slightly longer function; the point is that it’s possible to complete this assignment without writing a lot of code.

Be sure to have a comment at the top of the file with your name(s), the filename, the date, and the pledge. Every function should have a docstring saying what it does. If the function is even a little complicated, write a short comment explaining to the reader how this function works.

A bit later in this problem, we’ll give you a fairly large dictionary of English words to use. For now, we recommend that you use the following tiny dictionary during the course of testing and development. Include this line near the top of your file. Now, it’s a global variable that can be used by any of your functions in that file. Similarly, you should include the scrabble letter score list from Recursion Muscles.

Don’t try to change the values of these global variables! As we’ll see soon, that can make Python angry. However, there’s no need to change the contents of the Dictionary or the scrabble

letter scores during execution of the program.

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 115 – Hw 2

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Dictionary = [“a”, “am”, “at”, “apple”, “bat”, “bar”, “babble”, “can”, “foo”,

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“spam”, “spammy”, “zzyzva”]

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
The details…

Ultimately, there are two functions that we will be testing.

• scoreList(Rack) takes as input a Rack which is a list of lower-case letters and returns a list of all of the words in the global Dictionary that can be made from those letters and the score for each one. Specifically, this function returns a list of lists, each of which contains a string that can be made from the Rack and its Scrabble score. Here are some examples using the tiny Dictionary above:

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 115 – Hw 2

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; scoreList([“a”, “s”, “m”, “t”, “p”]) [[‘a’, 1], [‘am’, 4], [‘at’, 2], [‘spam’, 8]] &gt;&gt;&gt; scoreList([“a”, “s”, “m”, “o”, “f”, “o”]) [[‘a’, 1], [‘am’, 4], [‘foo’, 6]]

The order in which the words are presented is not important.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
• bestWord(Rack) takes as input a Rack as above and returns a list with two elements: the highest possible scoring word from that Rack followed by its score. If there are ties, they can be broken arbitrarily. Here is an example, again using the tiny Dictionary above:

Aside from these two functions, all of the other helper functions are up to you! Some of those helper functions may be functions that you wrote in Recursion Muscles, or slight variants of those functions. However, you might find it useful to use a strategy in which you write a function that determines whether or not a given string can be made from the given Rack list. Then, another function can use that function to determine the list of all strings in the dictionary that can be made from the

given Rack. Finally, another function might score those words.

Remember to use map, reduce, or filter where appropriate – they are powerful and they are

optimized to be very fast.

Test each function carefully with small test inputs before you proceed to write the next function. This will save you a lot of time and aggravation!

A reminder about in: Imagine that you are writing a function that attempts to determine if a given string S can be made from the letters in the Rack list. You might be tempted to scramble (“permute” to use a technical term) the Rack in every possible way as part of this process, but that is more work

</div>
</div>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; bestWord([“a”, “s”, “m”, “t”, “p”]) [‘spam’, 8]

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
than necessary. Instead, you can test if the first symbol in your string, S[0], appears in the rack with the statement:

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 115 – Hw 2

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
if S[0] in Rack:

# if True you will end up here

else:

# if False you will end up here

That in feature is very handy. Now, recursion will let you do the rest of the work without much effort on your part!

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Although we don’t expect that you will end up doing huge recursive calls, you should know that Python can get snippy when there are a lot of recursive calls. By default, Python generally complains when there are 1000 or more recursive calls of the same function. To convince Python to be friendlier, you can use the following at the top of your file.

Trying it with a bigger dictionary

Finally, if you want to test out a big dictionary (it’s more fun than the little one above), you can use the file dict.py provided with the assignment. It contains a large list of words (a bit over 4000 words). The list is still called Dictionary. After you have downloaded the file and placed it in the same directory as your Python file, you should do the following at the top of your Python file:

<pre> from dict import *
</pre>
Now, you can refer to Dictionary as a global variable. This is much nicer than cutting-and-pasting that very large list into your Python file. Here are some examples using that Dictionary.

</div>
</div>
<div class="layoutArea">
<div class="column">
import sys

sys.setrecursionlimit(10000) # Allows up to 10000 recursive calls

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; scoreList([‘w’, ‘y’, ‘l’, ‘e’, ‘l’, ‘o’])

[[‘leo’, 3], [‘low’, 6], [‘lowly’, 11], [‘ow’, 5], [‘owe’, 6], [‘owl’, 6], [‘we’, 5], [‘well’, 7], [‘woe’, 6], [‘yell’, 7], [‘yo’, 5]]

Notice that “yellow” is not in this dictionary. We “cropped” off words of length 6 or more to keep the dictionary from getting too large. Finally, here is an example of bestWord in action:

&gt;&gt;&gt; bestWord([‘w’, ‘y’, ‘l’, ‘e’, ‘l’, ‘o’]) [‘lowly’, 11]

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
And an even bigger dictionary!

Want to try this with an even bigger dictionary? We’ve got one! It’s in the file called bigdict.py provided with the assignment. The bad news is that it causes IDLE to crash on some computers, but you can always re-start IDLE and go back to a smaller dictionary.

If you want to try this, download the file and use this:

<pre> from bigdict import *
</pre>
The dictionary is still called Dictionary and it is available as a global variable. Here is an example of it in use:

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 115 – Hw 2

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; bestWord([“s”, “p”, “a”, “m”, “y”]) [‘may’, 8]

&gt;&gt;&gt; bestWord([“s”, “p”, “a”, “m”, “y”, “z”]) [‘zap’, 14]

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; scoreList([‘a’, ‘b’, ‘v’, ‘x’, ‘y’, ‘y’, ‘z’, ‘z’, ‘z’])

[[‘ab’, 4], [‘aby’, 8], [‘ax’, 9], [‘ay’, 5], [‘ba’, 4], [‘bay’, 8], [‘by’, 7], [‘ya’, 5], [‘yay’, 9], [‘za’, 11], [‘zax’, 19], [‘zyzzyva’, 43], [‘zzz’, 30]]

</div>
</div>
</div>
</div>
