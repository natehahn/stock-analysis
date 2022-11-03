# Stock Analysis 

The purpose of this anlaysis was to help George build a script to analyze stock so he could make recommendations to his parents.  Initially, we used a script that was very easy to read and provided the answers that George wanted.  However, he was concerned that the code would break if he were to run it against more than 12 stocks.

Here are the results of the two different types of code:

#### Non-Refactored

This image shows the output of the original code before it was refactored

<img src="/Resources/AllStockAnalysis%20Module.png" height="250" width="250"/>


Followed by the amount of time it took to run

<img src="/Resources/AllStockAnalysis_Time.png" height="250" width="250"/>

#### Refactored

This image shows the output after we refactored the code to only loop through all rows without a nested for loop
<img src="/Resources/VBA%20Challenge.png" height="250" width="250"/>


Followed by the amount of time it took to run

<img src="/Resources/VBA%20Challenge_Time.png" height="250" width="250"/>


**Summary**

There are advantages of refactoring code.  It can make the program run more smoothly, especially if you have thousands of lines to go through.  However, what I found with this example was that the original code ran faster.  Even after I ran it multiple times with the script loaded into memory.  What this means is the original scripting was actually faster and could be with even more stock tickers.  *Note: I have a ridiculously fast computer.
