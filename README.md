ezPyChart
=======

ezPyChart scratches a specific itch: generating a pie chart from a tab-delimited set of named lines. The actual chart generation uses [matplotlib](http://matplotlib.org/). If you need a simple way to create a pie chart from a text file of names and values, ezPyChart is your answer.

Installation
============

Matplotlib needs to be installed for ezPyChart to function.

Install matplotlib via OS package manager
-----------------------------------------

On Debian/Ubuntu:
```
sudo apt-get install python-matplotlib
```

Then you can install ezPyChart with dependencies.
```
pip install --no-deps ezPyChart
```

Install matplotlib via pip
--------------------------

Use [pip](https://pip.pypa.io/en/stable/) install, but pip will need to build matplotlib and NumPy. Some dev libraries need to be installed for the build step to succeed.

On Debian/Ubuntu:
```
sudo apt-get install python-dev libfreetype6-dev
```

After those development libraries are installed, you can run
```
pip install ezPyChart
```

Usage
=====

Pipe a list of named values and ezPyChart will create a pie chart with those names and values.

```
ezpychart < customer-breakdown.txt
```
