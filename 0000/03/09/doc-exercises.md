<h1 style="font-size: 3em">Documentation Exercises</h1>

<br/>

<span style="font-size: 2em">
Simple exercises or problem sets demonstrating a problem that can be solved by your project...
<br/>
<br/>

<span style="font-size: 2em" class="fragment">...to be completed <em>only using your documentation</em>.</span>
</span>

--

<img src="images/dateutil-exercises-text.png"
     alt="Exercises: It is often useful to work through some examples in order to understand how a module works; on this page, there are several exercises of varying difficulty that you can use to learn how to use dateutil. If you are interested in helping improve the documentation of dateutil, it is recommended that you attempt to complete these exercises with no resources other than dateutil’s documentation. If you find that the documentation is not clear enough to allow you to complete these exercises, open an issue on the dateutil issue tracker to let the developers know what part of the documentation needs improvement."/>

--

# Next Monday meeting

<blockquote>
A team has a meeting at 10 AM every Monday and wants a function that tells them, given a `datetime.datetime` object, what is the date and time of the next Monday meeting? This is probably best accomplished using a [relativedelta](https://dateutil.readthedocs.io/en/stable/relativedelta.html).
</blockquote>

<br/>

```python
# --------- YOUR CODE -------------- #
from dateutil import relativedelta

def next_monday(dt):
    <<YOUR CODE HERE>>

# ---------------------------------- #

from datetime import datetime
from dateutil import tz

NEXT_MONDAY_CASES = [
    ...     # Skipped test cases for space reasons
]

def test_next_monday_1():
    for dt_in, dt_out in NEXT_MONDAY_CASES:
        assert next_monday(dt_in) == dt_out

if __name__ == "__main__":
    test_next_monday_1()
    print('Success!')
```

<fragment/>
