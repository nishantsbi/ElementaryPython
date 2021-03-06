Computer Programming (with Python)
==================================

.. class:: crop

  .. image:: img/snake.JPG

.. class:: center huge white
  
  Computer Programming (with ``Python``) Week 3
  
.. class:: right big white

  | *Matt Harrison*

.. class:: small white

   ©2010, licensed under a `Creative Commons
   Attribution/Share-Alike (BY-SA) license
   <http://creativecommons.org/licenses/by-sa/3.0/>`__.

------------

.. class:: center huge

  Solution to Problem

School
-------

.. class:: small

  .. code-block:: python

    question = "What is your school?"
    school = raw_input(question)
    print "You go to " + school

Lessons
-------

  * I need to be more descriptive

-----------------

.. class:: center huge

  *Functions*

-----------------

*Functions* take input, apply an operation and return output




---------------

.. class:: crop

  .. image:: img/func1.png 


---------------

.. class:: center huge

  What does ``?`` do?


---------------

.. class:: fit

  .. image:: img/func2.png 

---------------

.. class:: center huge

  What does ``?`` do?

---------------

.. class:: fit

  .. image:: img/func3.png 


-----------------

.. class:: center huge

  Three important parts

Parts
-----

* Function
* Input
* Output

---------------

.. class:: fit

  .. image:: img/func4.png 

---------------

.. class:: fit

  .. image:: img/func5.png 

---------------

.. class:: fit

  .. image:: img/func6.png 


Python version
--------------

.. code-block:: python

  def add_4(input):
      answer = input + 4
      return answer

or

.. code-block:: python

  def add_4(num):
      return num + 4





Calling functions
-----------------

.. code-block:: python

  def add_4(num):
      answer = num + 4
      return answer

  seven = add_4(3)
  print seven


Quiz
-----

Name function, input and output

.. code-block:: python

  def add_4(num):
      answer = num + 4
      return answer

--------

.. class:: center huge

  Colons!



---------------

Christopher Columbus is Colon

.. class:: crop

  .. image:: img/4049688808_3791a0d001_b.jpg

--------------------

.. class:: center huge

  colons (``:``) go with *indentation* in Python


Python version
--------------

Find colon and indentation

.. code-block:: python

  def add_4(num):
      answer = num + 4
      return answer

Functions
----------

.. class:: incremental

  * Start with ``def``
  * then function name
  * then ``(``
  * then *input variables*
  * then ``)``
  * then ``:`` (and return)

    * then indent logic
    * then ``return`` answer

``def``
--------

``def`` means *define* a function

function names
---------------

similar to variable names:

  * lower case
  * ``_`` (underscore multiply words)
  * can't start with numbers
  * should be verbs (ie ``add_two``, ``load_data``)

Input
-----

If you have more than one input, separate with commas (``,``)

.. code-block:: python

  def add(x, y, z):
      return x + y + z

Input (2)
---------

Sometimes you don't have input

.. code-block:: python

  def get_name():
      return "Matt"

Whitespace
----------

All of function *logic* is indented (4 spaces).

.. code-block:: python

  def process(x, y):
      a = x + y
      b = x - y
      c = x * y
      return a + b + c


``return``
------------

``return`` tells the program what the *output* is

``return`` (2)
---------------

Don't have to have a ``return``

.. code-block:: python

  def print_name():
      print "Matt"


Calling Functions
------------------

.. class:: normal

  .. code-block:: python
   
    output = function_name(input)

-------------------

.. class:: center huge

  Have we seen any *functions*?

---------------------

.. class:: center huge

  YES!

  * ``int``
  * ``str``
  * ``raw_input``


Assignment
----------

Write a function that:

* takes a number
* subtracts 5 from that number
* returns the result

Extra Assignment
-----------------

Write a function that:

* takes degrees Celsius (Metric)
* returns degrees Fahrenheit (US)
(C to F multiply by 9 divide by 5 add 32)

----------------------

.. class:: center huge

  Conditions

New data *type*
-----------------

.. class:: incremental

  * int
  * float
  * string
  * boolean

*Boolean*
-----------

.. code-block:: python

  a = True
  b = False



----------------------

.. class:: center huge

  ``if`` statement


  
---------------------

.. code-block:: python

  age = 10
  if age > 18:
      print "OLD!"

``if`` statement
-----------------

.. class:: incremental

  * Start with ``if`` 
  * then *condition*
  * then ``:`` (and return)

    * then indent logic

Conditionals
-------------


=============== =============
Syntax          Meaning
=============== =============
``>``           Greater than
``<``           Less than
``>=``          Greater than
                or equal
``<=``          Less than
                or equal
``==``          Equal to
``!=``          Not equal to
=============== =============


Conditionals evaluate to Booleans
---------------------------------

.. code-block:: python

  >>> print 1 != 3
  True
  >>> print "matt" == "Fred"
  False




Examples
---------

.. code-block:: python

  name = "matt"
  if name == 'matt':
      print "Cool!"

  cash = 0.3
  if cash < 1.0:
      print "too bad"


``elif``
---------

.. code-block:: python

  grade = 80
  letter = "F"
  if grade > 90:
      letter = "A"
  elif grade > 80:
      letter = "B"
  elif grade > 70:
      letter = "C"

``elif``
---------

.. code-block:: python

  grade = 80
  letter = "F"
  if grade > 90:
      letter = "A"
  elif grade > 80:
      letter = "B"
  elif grade > 70:
      letter = "C"
grade = ? (note the indentation)


``else``
---------

.. code-block:: python

  name = 'matt'
  if name == "matt":
      print "same"
  else:
      print "different"

function with ``if``
---------------------

.. class:: normal

  .. code-block:: python

    def is_matt(name):
        result = False
        if name == "matt":
            result = True
        elif name == "Matt":
            result = True
        else:
            result = False
        return result



Assignment
-----------

Write a function that:

* takes a number
* returns:

  * ``"G"`` if greater than 1000000000
  * ``"M"`` if greater than 1000000
  * ``"K"`` if greater than 1000















credits
-------

* http://www.flickr.com/photos/marcp_dmoz/4049688808/sizes/l/
