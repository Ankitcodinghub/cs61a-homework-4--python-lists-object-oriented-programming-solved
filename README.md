# cs61a-homework-4--python-lists-object-oriented-programming-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Homework 4- Python Lists, Object-Oriented Programming Solved](https://www.ankitcodinghub.com/product/cs61a-homework-4-python-lists-object-oriented-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119649&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Homework 4- Python Lists, Object-Oriented Programming Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions

Download hw04.zip. Inside the archive, you will find a file called hw04.py, along with a copy of the ok autograder.

Using Ok: If you have any questions about using Ok, please refer to this guide.

Readings: You might find the following references useful:

Section 2.3

Section 2.5

Grading: Homework is graded based on correctness. Each incorrect problem will decrease the total score by one point. There is a homework recovery policy as stated in the syllabus. This homework is out of 2 points.

Required questions

Parsons Problems

To work on these problems, open the Parsons editor:

python3 parsons

Q1: Remove Odd Indices

Complete the function remove_odd_indices, which takes in a list lst and a boolean odd, and returns a new list with elements removed at certain indices. If odd is True, then the function should remove elements at odd indices; otherwise if odd is False, then the function should remove even indexed items.

Note that lists are zero-indexed; thus, the first element is at index 0, the second element is at index 1, etc.

py def remove_odd_indices(lst, odd): “”” Remove elements of lst that have odd indices. &gt;&gt;&gt; s = [1, 2, 3, 4]

&gt;&gt;&gt; t = remove_odd_indices(s, True) &gt;&gt;&gt; s [1, 2, 3, 4] &gt;&gt;&gt; t [1, 3] &gt;&gt;&gt; l = [5, 6, 7, 8] &gt;&gt;&gt; m = remove_odd_indices(l, False) &gt;&gt;&gt; m [6, 8] “”” “*** YOUR CODE HERE ***” Q2: Smart Fridge

The SmartFridge class is used by smart refrigerators to track which items are in the fridge and let owners know when an item has run out.

The class internally uses a dictionary to store items, where each key is the item name and the value is the current quantity. The add_item method should add the given quantity of the given item and report the current quantity. You can assume that the use_item method will only be called on items that are already in the fridge, and it should use up the given quantity of the given item. If the quantity would fall to or below zero, it should only use up to the remaining quantity, and remind the owner to buy more of that item.

Finish implementing the SmartFridge class definition so that its add_item and use_item methods work as expected.

py class SmartFridge: “””” &gt;&gt;&gt; fridgey = SmartFridge() &gt;&gt;&gt; fridgey.add_item(‘Mayo’, 1) ‘I now have 1 Mayo’ &gt;&gt;&gt; fridgey.add_item(‘Mayo’, 2) ‘I now have 3 Mayo’ &gt;&gt;&gt; fridgey.use_item(‘Mayo’, 2.5) ‘I have 0.5 Mayo left’ &gt;&gt;&gt; fridgey.use_item(‘Mayo’, 0.5) ‘Uh oh, buy more Mayo!’ “”” def __init__(self): self.items = {} def

add_item(self, item, quantity): “*** YOUR CODE HERE ***” def use_item(self, item, quantity): “*** YOUR CODE

HERE ***”

Code Writing Questions

Q3: Merge

Write a function merge that takes 2 sorted lists lst1 and lst2, and returns a new list that contains all the elements in the two lists in sorted order. Note: Try to solve this question using recursion instead of iteration.

“`py def merge(lst1, lst2): “””Merges two sorted lists.

&gt;&gt;&gt; merge([1, 3, 5], [2, 4, 6])

[1, 2, 3, 4, 5, 6]

&gt;&gt;&gt; merge([], [2, 4, 6])

[2, 4, 6]

&gt;&gt;&gt; merge([1, 2, 3], [])

[1, 2, 3]

&gt;&gt;&gt; merge([5, 7], [2, 4, 6])

[2, 4, 5, 6, 7]

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q merge Q4: Mint

A mint is a place where coins are made. In this question, you’ll implement a Mint class that can output a Coin with the correct year and worth.

A Coin’s worth method returns the cents value of the coin plus one extra cent for each year of age beyond 50. A coin’s age can be determined by subtracting the coin’s year from the present_year class attribute of the Mint class.

“`py class Mint: “””A mint creates coins by stamping on years.

The update method sets the mint’s stamp to Mint.present_year.

&gt;&gt;&gt; mint = Mint()

&gt;&gt;&gt; mint.year

&gt;&gt;&gt; dime = mint.create(Dime)

&gt;&gt;&gt; dime.year

&gt;&gt;&gt; Mint.present_year = 2101 # Time passes

&gt;&gt;&gt; nickel = mint.create(Nickel)

&gt;&gt;&gt; nickel.worth() # 5 cents + (80 – 50 years)

35

&gt;&gt;&gt; mint.update() # The mint’s year is updated to 2101

&gt;&gt;&gt; Mint.present_year = 2176 # More time passes

&gt;&gt;&gt; mint.create(Dime).worth() # 10 cents + (75 – 50 years) 35

&gt;&gt;&gt; Mint().create(Dime).worth() # A new mint has the current year 10

&gt;&gt;&gt; dime.worth() # 10 cents + (155 – 50 years)

115

&gt;&gt;&gt; Dime.cents = 20 # Upgrade all dimes!

&gt;&gt;&gt; dime.worth() # 20 cents + (155 – 50 years)

def __init__(self): self.update()

def create(self, coin): “*** YOUR CODE HERE ***”

def update(self):

“*** YOUR CODE HERE ***”

class Coin: cents = None # will be provided by subclasses, but not by Coin itself

def __init__(self, year): self.year = year

def worth(self):

“*** YOUR CODE HERE ***” class Nickel(Coin): cents = 5 class Dime(Coin): cents = 10 “`

Use Ok to test your code:

python3 ok -q Mint

Q5: Vending Machine

In this question you’ll create a vending machine that only outputs a single product and provides change when needed.

Create a class called VendingMachine that represents a vending machine for some product. A VendingMachine object returns strings describing its interactions. Remember to match exactly the strings in the doctests — including punctuation and spacing!

Fill in the VendingMachine class, adding attributes and methods as appropriate, such that its behavior matches the following doctests:

“`py class VendingMachine: “””A vending machine that vends some product for some price.

&gt;&gt;&gt; v = VendingMachine(‘candy’, 10)

&gt;&gt;&gt; v.vend()

‘Nothing left to vend. Please restock.’

&gt;&gt;&gt; v.add_funds(15)

‘Nothing left to vend. Please restock. Here is your $15.’

&gt;&gt;&gt; v.restock(2)

‘Current candy stock: 2’

&gt;&gt;&gt; v.vend()

‘You must add $10 more funds.’

&gt;&gt;&gt; v.add_funds(7)

‘Current balance: $7’

&gt;&gt;&gt; v.vend()

‘You must add $3 more funds.’

&gt;&gt;&gt; v.add_funds(5)

‘Current balance: $12’

&gt;&gt;&gt; v.vend()

‘Here is your candy and $2 change.’

&gt;&gt;&gt; v.add_funds(10)

‘Current balance: $10’

&gt;&gt;&gt; v.vend()

‘Here is your candy.’

&gt;&gt;&gt; v.add_funds(15)

‘Nothing left to vend. Please restock. Here is your $15.’

&gt;&gt;&gt; w = VendingMachine(‘soda’, 2)

&gt;&gt;&gt; w.restock(3)

‘Current soda stock: 3’

&gt;&gt;&gt; w.restock(3)

‘Current soda stock: 6’

&gt;&gt;&gt; w.add_funds(2)

‘Current balance: $2’

&gt;&gt;&gt; w.vend()

‘Here is your soda.’

“””

“*** YOUR CODE HERE ***”

“`

feeling = ‘love’ course = ’61A!’ f’I {feeling} {course}’ ‘I love 61A!’ “`

Use Ok to test your code:

python3 ok -q VendingMachine

If you’re curious about alternate methods of string formatting, you can also check out an older method of Python string formatting. A quick example: “`py

ten, twenty, thirty = 10, ‘twenty’, [30] ‘{0} plus {1} is {2}’.format(ten, twenty, thirty) ’10 plus twenty is [30]’ “`

Submit

Make sure to submit this assignment by running:

python3 ok –submit
