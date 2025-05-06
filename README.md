# cse224-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE224 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cse224-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95954&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE224 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
For assignment 1, you need to write a shell script named 􏰁stick􏰂 which plays a matchstick-picking game. Given an initial number of sticks, players take turns picking either 1, 2 or 3 sticks from a pile. Whoever picks the last stick wins.

Usage

You run stick without any command line arguments, i.e.

stick

The game should greet the user, and then ask how many sticks to play with (must be an integer ≥ 10), and who should go 􏰄rst (c for computer, u for user). An invalid answer should cause the program to re-ask the question (as many times as necessary).

On the user’s turn, ask the user how many sticks to remove, and remove those from the pile. On the computer’s turn, calculate the correct number of sticks to remove in order to ensure you will (hopefully) win the game.

Play continues until there are no sticks left, at which point your program announces who won. You must show the set of sticks after each player’s move. Show this as a set of pipes (􏰁|􏰂) side by side, followed by the number of sticks in (parenthesis), for example:

||||||| (7)

Illegal Moves

When the user is asked how many sticks to take, they must enter 1, 2 or 3. If their entry is illegal (anything other than 1 2 or 3), remind them of their options, and ask once more. If they enter another illegal number, announce that they have forfeited the game, and terminate the program. If the user entered a valid number the second try, gameplay continues (in this case, if later the user again enters an illegal number, you should again given them a second chance).

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Algorithm

Your algorithm for picking sticks is simple: given n remaining sticks, pick (n mod 4) sticks, unless (n mod 4)=0; in that case, pick 1 stick.

Other Requirements

<ul>
<li>your program must be written as a bash script</li>
<li>make frequent backups! It’s easy to lose your work; it’s your responsibility to make sure you can recover from this.</li>
<li>you must comment your script thoroughly, including a block of comments in the beginning describing:
􏰆 your name, the course, the date, and the assignment number 􏰆 a synopsis in your own words of what the script does

If you don’t include this block of comments, your program will receive a grade of 0.
</li>
</ul>
</div>
</div>
</div>
