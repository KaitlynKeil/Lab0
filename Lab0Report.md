# Lab 0 Report

### Kaitlyn Keil and Serena Chen

![](waveform.png)

This is our waveform of all 16 test cases.

![](waveform_1change.png)

This is our waveform for one test case, as marked by the markers. No matter the inputs, it will always take 
350 time units to propogate (given a constant 50 time units per gate).

![](truth_table_l1.png)

This is the output for our test cases. We tried to test as many edge cases as possible, such as large negatives, large positives, adding negatives and positives, adding 0s and 1s, and various overflow scenarios. We started with the four cases in the in-class slides as a sanity check.

In terms of test cases failure, throughout the process of building the four bit adder, we had one failure, and that was due to the test case being incorrect (we checked on paper!).