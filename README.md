# csci111-lab-10-vector-class-solved
**TO GET THIS SOLUTION VISIT:** [CSCI111 Lab 10-Vector Class Solved](https://www.ankitcodinghub.com/product/csci-111-lab-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116914&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI111 Lab 10-Vector Class Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Vector Class

File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

A 3d vector type: Write a module called vector.py such that the following interaction is possible:

&gt;&gt;&gt; from vector import V

&gt;&gt;&gt; v1 = V(1, 2, 3)

&gt;&gt;&gt; v1

&lt;vector.V object at 0x00000189527E4808&gt;

&gt;&gt;&gt; print(v1)

V(1, 2, 3)

&gt;&gt;&gt; print(10 * v1)

V(10, 20, 30)

&gt;&gt;&gt; print(v1 / 5)

V(0.2, 0.4, 0.6)

&gt;&gt;&gt; v2 = V(10,20,30)

&gt;&gt;&gt; print(v2) V(10, 20, 30)

&gt;&gt;&gt; print(v1 + v2) V(11, 22, 33)

&gt;&gt;&gt; print(v2 – v1)

V(9, 18, 27)

&gt;&gt;&gt; v1 * v1

14

&gt;&gt;&gt; v1 * v2

140

&gt;&gt;&gt; v2 * v2

1400

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

16

17

18

19

20

21

22

23

And so on. Clearly you will be defining a new class and overloading the operators. Make sure you overload all of the following:

+

–

*

/

==

!= __add__(self, other)

__sub__(self, other)

__mul__(self, other)

__truediv__(self, other)

__eq__(self, other)

__ne__(self, other) -=

+=

*=

/=

–

+ __isub__(self, other)

__iadd__(self, other)

__imul__(self, other)

__itruediv__(self, other)

__neg__(self)

__pos__(self)

Adding and subtracting is done with two vectors. They are computed componentwise.

Multiplying and dividing is done with a vector and a number (float or int).

Two vectors are equal if all their components are equal, and not equal otherwise. Because we will have lots of floats in our vectors, use math.isclose to compare components instead of ==. You can also use your own function to determine if two floats are almost equal.

There is also vector multiplication to be supported. This is the inner product or dot product of two vectors:

(ax,ay,az) · (bx,by,bz) = axbx + ayby + azbz

Clearly the dot product of two vectors is a scalar (int or float). Since there is no “·” available in python, you will override the multiplication symbol, “+”. This means we have three kinds of multiplication, where v is a vector and x is a scalar:

x * v v * x v * v

1

One of these can be handled with __rmul__. To handle all three you will need to use type-based dispatch, where you examine the type of one or more of the arguments and take action accordingly.

__imul__ obviously does not apply to vector multiplication. Why not?

The last two operators in the list above are the unary operators, so we can write, for example, v + (-w) as well as v – w or v – -w instead of v+w.

None of the above operators should be destructive, except for the ”i” operators, iadd, imul, etc. The others should all be pure functions that return new objects and not modify their arguments.

Testing: Write a unittest module called test_vector.py to accompany your vector module. Make sure your unit tests test every operator!

Normalize: Write a destructive method normalize(self) that will normalize a vector, i.e.

stretch or shrink the vector so that its length is 1. If v is a vector, length of the vector,

|v|, can be computed by √

|v| = v · v

A vector can be made unit length by dividing by its length. If the length of the vector is zero, you should raise a RunTimeError with the message ’cannot normalize zero vector’ rather than the normal divide by zero error.

This method should be destructive, the vector itself should be modified. No new vector is returned.

Testing: Add tests to your test_vector unittest module to test normalization. Make sure all tests are passed before you continue!

Project: Write a nondesctructive method project(self, other) that will find the projection of a vector onto another. Mathematically the projection of v onto w is

proj

This method is nondestructive, returns a new vector and does not modify either of the input vectors.

Testing: Add tests to your test_vector module to test projection. Make sure all tests are passed before you continue!

Gram-Schmidt process: The Gram-Schmidt process starts with any three linearly independent vectors and ends up with three orthonormal vectors. Orthonormal means they are all of unit length and all perpendicular to each other.

You can test whether two vectors v and w are perpendicular by testing whether v·w = 0. Since we’re using floating point numbers a lot with vectors, don’t use equality, == to compare to zero, use math.isclose, or your own function to compare two floats to see if they are almost the same.

If v1,v2,v3 are the original vectors, the Gram-Schmidt process works as follows:

u1 = v1 u2 = v2 − proju1(v2) u3 = v3 − proju1(v3) − proju2(v3)

If any one of these vectors u1,u2,u3 is (close to) zero, the original vectors are not (really) linearly indepedent.

After this, the three vectors u1,u2,u3 are normalized to unit length.

Write a method gram_schmidt(self, v2, v3) that will desctructively perform the above algorithm on the three input vectors, ending up with all of them orthonormal.

If you find that the original vectors are not linearly independent, raise the RuntimeError with the message ’cannot orthonormalize linearly dependent vectors’

Testing: Add tests to your test_vector module to test the Gram-Schmidt process. Make sure you test orthonomrality and linear independence for several sets of vectors. Make sure all tests are passed before you turn in the assignment!

Here’s some data you can turn into a test:

v1 = V(1,1,1)*3 v2 = V(1,-2,3)*4 v3 = V(1,3,-2)*5 v1.gram_schmidt(v2,v3) for v in (v1, v2, v3):

print(v) print(v*v)

1

2

3

4

5

6

7

V(0.57735, 0.57735, 0.57735)

1.0

V(0.0936586, -0.749269, 0.65561)

1.0

V(0.811107, -0.324443, -0.486664)

1.0000000000000002

1

2

3

4

5

6
