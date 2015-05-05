Data Cleanup
============

In this data file (sample_data.txt), there are three records.

In your favorite scripting language (we use Python at MindMixer), write a few functions/methods that will:

• Convert all strings to Title Case (e.g. ``SUGAR LN`` becomes ``Sugar Ln``).
• Remove stray spaces inside a string.
For e.g.
```python
PALESTINE                                         TX
```
should become 
```
PALESTINE TX
```
• The last field in each record is the Date of Birth (represented as yyyymmdd). Calculate the individual's age today.

Now, combine all those functions to process the entire file, and dump the output line-by-line into the console.
