Data Cleanup
============

In this data file (sample_data.txt), there are three records.

In your favorite scripting language (we use Python at MindMixer), write a few functions/methods that will:

1. Convert all strings to Title Case (e.g. ``SUGAR LN`` becomes ``Sugar Ln``).
2. Remove stray spaces inside a string (e.g.
        ```PALESTINE                                         TX```
should become
       ``PALESTINE TX``)
3. The last field in each record is the Date of Birth (represented as yyyymmdd). Calculate the individual's age today.

Now, combine all those functions to process the entire file, and dump the output line-by-line into the console.
