ezPyChart
=======

ezPyChart scratches a specific itch: generating a pie chart from a tab-delimited set of named lines. The actual chart generation uses [matplotlib](http://matplotlib.org/). If you need a simple way to create a pie chart from a text file of names and values, ezPyChart is your answer.

Installation
============

Use [pip](https://pip.pypa.io/en/stable/) install.

```
pip install ezPyChart
```

Usage
=====

Pipe a list of named values and ezPyChart will create a pie chart with those names and values.

```
ezpychart < customer-breakdown.txt
```
