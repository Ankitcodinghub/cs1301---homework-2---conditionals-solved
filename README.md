# cs1301---homework-2---conditionals-solved
**TO GET THIS SOLUTION VISIT:** [CS1301 – Homework 2 – Conditionals Solved](https://www.ankitcodinghub.com/product/cs1301-homework-2-conditionals-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123753&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1301 - Homework 2 - Conditionals Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
How to Think Like a Computer Scientist

CS 1301 YouTube Channel

Comment out or delete all function calls. Only import statements, global variables, and comments are okay to be outside of your functions.

Read the entire document before starting this assignment.

The goal of this homework is for you to practice and understand how to write functions that implement conditionals. The homework will consist of 5 functions for you to implement. You have been given HW02.py skeleton file to fill out. However, below you will find more detailed information to complete your assignment. Read it thoroughly before you begin.

Hidden Test Cases: In an effort to encourage debugging and writing robust code, we will be including hidden test cases on Gradescope for some functions. You will not be able to see the input or output to these cases. Below is an example output from a failed hidden test case:

Written by Arushi Gupta (arushigupta@gatech.edu), Colin Tam (ctam31@gatech.edu), and Yara Seif (yaraseif@gatech.edu)

Helpful Information To Know

Print vs Return

For example, letʼs say we have the following two functions below in a file called file.py:

This is what would happen if we ran the file and typed the following into the Python shell:

When we call returnFunc() and assign it to a variable, nothing is printed to the screen because there are no print statements inside the function. However the variable, b, now holds the value 2 ( int ).

Skill Level

Function Name: skillLevel()

Parameters: passRate ( int )

Returns: “Beginner” or “Moderate” or “Advanced” ( str )

Shopping Fun

Function Name: bookStore()

Parameters: item ( str ), walletAmount ( float ), quantity ( int )

Returns: moneyLeftOver ( float )

Dinner Plans

Function Name: dinnerPlans()

Parameters: distance ( int ), hungerLevel ( str )

Returns: transportMode ( str )

Description: After some shopping fun, you and a couple friends want to go out for dinner and are deciding whether you should walk or take an Uber. Write a function that takes in the distance from the restaurant and the hunger level of the group and returns whether you choose to Uber or Walk. There are four hunger levels: “Not Hungry”, “Slightly Hungry”, “Hungry”, “Very Hungry”. Use the table below to make your decision.

distance hungerLevel decision

&lt;= 7 Not Hungry Walk

&lt;= 5 Slightly Hungry Walk

&lt;= 3 Hungry Walk

&lt;= 1 Very Hungry Walk

&gt; 7 Not Hungry Uber

&gt; 5 Slightly Hungry Uber

&gt; 3 Hungry Uber

&gt; 1 Very Hungry Uber

Weekend Trip

Function Name: weekendTrip()

Parameters: distance ( float ), speed ( float ), freeTime ( float )

Returns: transportMode ( str )

Description: Over the weekend, you decide to explore the city and visit Atlantaʼs various attractions. However, you first want to determine the best way to get there based on how much free time (hours) you have. If your travel time is 20% or less of your free time, return the mode of transportation based on the speed (miles per hour) using the table below. If the travel time takes more than 20% of your free time, return “Going to this destination would take too much time.” Distance will be given in miles and the speed will always be 2.5 mph or greater.

speed transportMode

2.5 &lt;= speed &lt;= 15 walking

15 &lt; speed &lt;= 20 biking

20 &lt; speed driving

Friends

Function Name: textFriends()

Parameters: distance ( float ), speed ( float ), freeTime ( float ), numSnacks ( int ), numFriends ( int ) Returns: textMsg ( str )

Description: After you have determined whether you can go to the attraction, you decide to text your friends and tell them how many snacks you should get for the trip and how it should be split amongst you all. If the trip will take 20% or less of your free time, return a text message of this format:

If the trip takes up too much of your free time, return “Going to this destination would take too much time.” Hint: You must call weekendTrip() in this function.

Grading Rubric

Function Points

skillLevel() 15

bookStore() 20

dinnerPlans() 20

weekendTrip() 20

textFriends() 25

Total 100

Provided

The HW02.py skeleton file has been provided to you. This is the file you will edit and implement. All instructions for what the functions should do are in this skeleton and this document.

Submission Process
