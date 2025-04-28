# ucsdcse8b-assignment-2--measuring-file-similarity-solved
**TO GET THIS SOLUTION VISIT:** [UCSDCSE8B Assignment 2- Measuring File Similarity Solved](https://www.ankitcodinghub.com/product/ucsdcse8b-psa-2-measuring-file-similarity-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118837&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;UCSDCSE8B Assignment 2- Measuring File Similarity Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Helpful Information:

● Setting Up the PSA

● Online Communication: Using Piazza, Opening Regrade Requests

● How to Use Vim

● Style Guidelines

● Submitting on Vocareum and Grading Guidelines

Table of Contents:

Part 1: Vim and Unix Commands [7 Points]

Introduction to Test-Driven Development Example

Exercise (optional):

Part 2: WordCountList [70 Points]

Overview

A. Read words from file into your program. (20 points)

A-1. Unit Testing

A-2. Implementation

B. Remove a given set of common words from your program (10 points)

B-1. Unit Testing

B-2. Implementation

C. Define your toString(), writing words to file (15 points)

C-1. Unit Testing

C-2. Implementation

D. Find n most frequent words (25 points)

D-1. Unit Testing

D-2. Implementation

Part 3: Summary [3 Points]

Style Guidelines (Link) [20 Points]

Part 4: Similarity Detector [+8 Points]

Submitting the Assignment (Link)

Appendix toString

Scanner

WordCount

WordCountListTester

ArrayLists

Testing Using WordCountListTester (Sample Output)

Similarity Checker (Sample Output)

Part 1: Vim and Unix Commands [7 Points]

In COMMANDS.md, answer the following short questions with short answers.

Questions about Vim:

1. What are two ways to switch from command mode to insert mode?

2. How do you move the cursor to the end of a line in vim without using the arrow keys or mouse?

3. How do you copy 8 lines of code in Vim?

Questions about Linux:

1. How do you change to the home directory, no matter what directory you are currently in?

2. How do you make a new directory from the command line?

3. How do you show the path to the directory you are currently in?

4. How do you copy a directory and all of its contents?

5. How do you copy files from your personal computer to the ieng6 server?

6. How do you copy files from the ieng6 server to your personal computer?

Introduction to Test-Driven Development

In PSA1, you learned to write testers for your code, whether it was inserting print statements, checking the print statements, testing various outputs for some input, or perhaps even using Exceptions. Regardless of technique, the important goal in testing your code is to determine whether your code has the correct behavior.

Example

/* This method returns the sum of first and second if and only if flag is true. Otherwise, return null

Note: This method is not defined yet! */ public Integer addIfTrue (int first, int second, boolean flag);

If you were testing a method addIfTrue(), create a test testAddIfTrue(). In the test, include a method call to the function you want to test, even though the function has not been implemented yet. Your tests should not focus on what’s inside of the method, but what output/result is expected given an input. As in this example, the programmer already knows what this method should do: It takes the two arguments (first and second), adds them together, and returns the sum. However, it will do so if and only if the third argument, flag, is true. Otherwise, just return null. Since the output’s expected value can be easily guessed, the programmer can write a tester method for it before writing the method itself. Notice that testAddIfTrue was fully implemented before addIfTrue was.

public boolean testAddIfTrue () { if ( addIfTrue ( 5 , 7 , true ) != 12 ) return false; if ( addIfTrue ( 3 , 2 , true ) != 5 ) return false; if ( addIfTrue ( 0 , 0 , true ) != 0 ) return false; if ( addIfTrue ( -1 , 5 , false ) != null ) return false; if ( addIfTrue ( 7 , 8 , false ) != null ) return false; if ( addIfTrue ( 999, 1 , true ) != 1000 ) return false; if ( addIfTrue ( -6 ,-9 , false ) != null ) return false; return true; // Reaching this statement means all passed.

}

After addIfTrue() is implemented, the programmer will be able to run the unit tests on addIfTrue() and then modify its implementation from there.

Exercise (optional):

Let’s practice unit testing. Neither of these files will be submitted for points. You will be writing tests and

debugging a method that finds the derivative of a math expression.

Part A: Writing unit tests

In ExampleClass.java, you will find the following method, which is not defined yet:

public String derivative(int multiplier, char variableName, int power) {}

Do not write the method body for this method yet. Do the following:

1. Read the method header of derivative() to understand what this method is supposed to do.

3. Compile and run UnitTestEx. Observe that all the tests fail, because derivative() has not been defined yet.

Part B: Using unit tests to debug buggy code

Now that we have some test methods, we can now proceed with derivative(). Instead of writing this method from fresh, we have provided you with a partially correct version of this method. Your goal is to debug this method until it works correctly. To do so:

1. Go to ExampleClass.java, comment out the first derivative() in ExampleClass.java. (If you did not modify

this file, it should be line 74)

2. Scroll down, rename derivative2() to be derivative()

3. Compile and run UnitTestEx. Observe that some tests still fail, proceed to debug derivative() until all tests pass.

4. Give yourself a pat on the back. You have just learned the essence of unit testing.

Part 2: WordCountList [70 Points]

Overview

Your task here is to define a set of methods in WordCountList.java. Write your well-documented unit tests for the WordCountList methods in the provided file called WordCountListTester.java

Your personal tests should focus on testing one method at a time with different arguments to ensure each method produces expected result. Once you have finished writing a unit test method, call it in the main method of WordCountListTester.java. For unit testing to be effective, you should test your code with your pre-written tests after each method is written. If your method fails the unit tests, you can use these failures to improve/debug your method’s functionality. Once you’ve made the correction, test the method again. Refer to A-1, B-1, C-1, D-1 below on how to write unit test for each method.

We provided the full code for WordCount.java. Do not modify WordCount. Implement the following methods in WordCountList.java. The intended use for WordCountList is:

1. Read in the words from a file.

2. Strip out any common words (i.e., the, a, an) (the file with common words is given to you).

3. Display the most occurring words in the input file to another output file or on console.

4. Be able to know which words occurred the most.

Each of the methods below corresponds to one of the steps above. We have also provided some more detailed explanations on various components in the Appendix section.

A. Read words from file into your program. (20 points)

A-1. Unit Testing

Before writing the implementation for reading from a file, write a test in WordCountListTester.java that will determine whether or not getWordsFromFile() is working correctly. Create your own small files to read words from. Your test should:

1. Create a new instance of a WordCountList object.

2. Load the words from a file that you created.

3. Verify that the correct words appear the WordCountList’s ArrayList.

4. Verify that the WordCount objects have the correct counts.

Run the tester before writing the implementation to make sure that it fails. You are free to add additional test cases as in order to ensure that your method program is correct. A-2. Implementation void getWordsFromFile( String filename ) throws IOException

This method populates the ArrayList containing WordCount objects for each word in the file. The throws IOException clause is there because you will deal with file I/O in this method. Your algorithm will be:

for every word in the file

search for the word in the arrayList if the word is present

increment its count if word is not already in the arrayList add word to the arrayList

Important:

Make sure that you do not ignore punctuations while saving your words in WordCount. For example,

● “Apple” and “Apple!” should be counted as different words in the ArrayList (with different entries)

● Similarly “state”, “state,” and “state.” should be counted as different words

Note:

● Adding a word into the ArrayList should be case insensitive and should just keep the String in the list the same as its first occurrence.

● All the input files should be put in the same location as the .java files. You should use relevant path while creating your File object.

B. Remove a given set of common words from your program (10 points)

B-1. Unit Testing

Before writing the implementation for reading from a file, write a test in WordCountListTester.java that will determine whether or not removeCommon() is working correctly.

1. Create a new instance of a WordCountList object.

2. Load the words from a file that you created.

3. Remove common words using a file that you created.

4. Verify that the correct words were removed from the WordCountList object’s ArrayList.

5. Verify that other words were not removed. B-2. Implementation void removeCommon(String omitFilename) throws IOException

This method will read each word from the specified file and remove that word from the ArrayList. Your method need not be efficient (nested for loops is fine). Also, removing a word is case insensitive like in the method before.

C. Define your toString(), writing words to file (15 points)

C-1. Unit Testing

Before writing the methods in part C, write a tester that verifies the correctness of the WordCountList’s toString() method. You do not need to write a tester for outputWords(), but you should still verify its correctness manually.

C-2. Implementation

public String toString()

This method is called to format the words in the ArrayList of WordCounts into a string. If a file contains three occurrences of “this”, two occurrence of “is” and one occurrence of “a”, then one valid output of the toString() is “this(3) a(1) is(2) ”. Ordering does not matter, but you will be graded on the correct formatting.

public void outputWords(boolean printToFile) throws IOException

This method is called to print the words in the Arraylist of WordCounts. This method takes in a boolean printToFile. If printToFile is false, it should print the result of toString on the screen. If printToFile is true, it should output to a file myOutput.out. The output file should be written into the current path, and not using an absolute path but a relative path. By default, if you don’t provide any path when creating a file for output, Java will create the file in the folder where your java files are.

Also, you will be graded for formatting of the outputted text. If your formatting is wrong, up to 5 points will be deducted. Make sure that spaces and parentheses are consistent with what is provided in the sample output. Check the “Testing Using WordCountListTester (Sample Output)” section for more details.

Note: Print a newline after printing all the words in the console or the file.

D. Find n most frequent words (25 points)

D-1. Unit Testing

Before writing the topNWords method in part D, write a test in WordCountListTester.java that checks if topNWords functions properly (i.e. verify that the method returns the correct words and their respective counts). Your tester should:

1. Create a new instance of a WordCountList object.

2. Load the words from a file you created.

3. Call the topNWords method.

4. Verify that the WordCount objects in the returned ArrayList contain the correct words.

5. Verify that those words have their correct respective counts.

D-2. Implementation public ArrayList&lt;WordCount&gt; topNWords(int n)

This method will find the top n occurring words as determined by their frequency in the arraylist and returns this list of words as well as their counts as an ArrayList. In the event of a tie, use the first occurring word with that count.

Hint:

Here is one way to get the top n words from an unsorted Arraylist (we refer to it as the original list here). You can iterate through the list looking for the word with the highest count. Once you have saved this word and its count into another ArrayList, you can make its count negative of its original in the original list so it won’t be the one with the highest rank again in the next round of search. You repeat this process until you have located the top n words. When you are done finding the top n words in the original list, you will need to iterate through the original array list again and change the negated counts back to their original values. For instance, if the original arraylist is the following (with word and its count) and the length parameter passed is 1.

dog 5 cat 222 snake 10 dophin 200

We want to locate the top 2 words in the list (n=2). In the first round of search, your code will locate cat which has the highest count, and make its count negative of its original count int the array list. It becomes

dog 5 cat -222 snake 10 dophin 200

In the second round of search, the list becomes the following.

dog 5 cat -222 snake 10 dophin -200

The last step is to go through the original array list again to make all the counts positive again. So the array list changes back to its original form.

You are required to be able to have the method topNWords execute more than once and produce the same results (ArrayList should have the same values). In the case of a tie (two words are equally frequent), you should select the word which occurred first in the original text file.

***Note 1: You are free to implement any other helper algorithm/method as well to get the topNwords.

***Note 2: topNWords method does not print/display anything.

***Note 3: If the number of words is less than n, return all those words. For example n = 10 but you have only 5 words, return those 5 words.

Things to Test: Think about what needs to be tested to ensure correctness. Be aware that this includes Note 1 above.

Part 3: Summary [3 Points]

In README.md, write about your test-driven development of your WordCountList. Tell us about how you approached this different angle of development. Provide a program description for each file you worked on. For example, WordCountList.java is a file you worked on, but not WordCount.java. However, you can mention WordCount when talking about WordCountList.

The audience of the summary is anyone who knows no programming or computer science. As a rule of thumb, write as if you were writing for an impatient 5-year old boy or a non-computer scientist grandmother. This means use absolutely no Java or CSE terms, but high-level terms are fine. The scripts will warn you if you use a word that’s too technical and the checks will be including in the grading scripts.

Style Guidelines (Link) [20 Points]

We will grade #1 through #10 in the style guidelines. Two points each.

Part 4: Similarity Detector [+8 Points]

The following methods will be defined in Similarity.java.

public static WordCountList findMax(WordCountList a, WordCountList b)

public static WordCountList findMin(WordCountList a, WordCountList b)

They should find the maximum and minimum number of occurrences of each word. For example, if the word “hello” appears 3 times and “hi” appears 1 times in file A, and “hello” appears 2 times and “hi” appears 4 times in file B, the WordCountList returned by findMax will have a WordCount for “hello” with a count of 3 and for “hi” with a count of 4. Likewise, the WordCountList returned by findMin will have a WordCount for “hello” with a count of 2 and for “hi” with a count of 1. If a word occurs in one file, but not the other, then the word occurs in the other file 0 times.

You should use the two above methods to write the following method to find the percent similarity between two documents. This can be found by dividing the sum of all minimum counts by the sum of all maximum counts and multiplying by 100. Remember to use floating point division. Continuing the example, the similarity between document A and B should be 3/7 (42.8571429%) because the sum of all the minimum counts is 3 and the sum of all the maximum counts is 7.

public static double getSimilarity(WordCountList a, WordCountList b)

See Similarity Checker (Sample Output) for other cases.

Submitting the Assignment (Link)

Early Submission:

● WordCountListTester.java

Submission Files (Make sure your submission contains all of the files and that they work on the ieng6 lab machines!)

● WordCountListTester.java (For early checkpoint and normal submission)

● WordCountList.java (With methods defined in Part 2)

● README.md (Program summary)

● COMMANDS.md (Answers to linux/vim questions)

● Similarity.java (Extra Credit program)

Maximum Score Possible: 110/100 Points

Read the submission scripts!

Appendix

toString

Every class in Java has access to a method called toString(). The purpose of the toString() method is to return a string representation of an object.

Suppose you create a class called Coordinate.java, in which each Coordinate object has an x-value and a y-value. You write two getter methods for this class: getX() and getY(). You then write the following code in your main method:

Coordinate c1 = new Coordinate(10, 20);

System.out.println(c1);

Coordinate@7852e922

However, this seemingly random/“garbage” series of letters and numbers isn’t very helpful for us. We can remedy this problem by defining a method called toString() in the Coordinate class:

public String toString() { return “The coordinates are: ” + this.getX() + “, “ + this.getY(); }

Now, when we call System.out.println() on a Coordinate object, its x and y coordinates will be printed out. For instance, System.out.println(c1) will now print:

The coordinates are: 10, 20

Scanner

Use a Scanner object to read words from the file.

The Scanner Javadocs: http://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html The basic framework to use a Scanner in this PSA is:

// Construct a Scanner that reads in words from a file Scanner input = new Scanner( new File(fileName)); while ( input.hasNext() ) // while there are more words to be read in { word = input.next(); // reads next string …

}

WordCount

This class is just a pairing of a String (a word) with an integer (the number of its occurrences) for use in your WordCountList class. Your ArrayList will store WordCount objects. Applicable methods are provided.

WordCountListTester

This file contains some default testers for you to test the validity of the methods in your WordCountList.java file. It can simply be run by compiling along with the other files on the command line and running it.

If you are intent on completing the unit testing extra credit portion of the PSA, consider using this file as a reference in thinking about how you can write unit tests for individual methods as you develop the PSA.

ArrayLists

ArrayLists are dynamically resizing arrays. In Java, standard arrays are initialized to a fixed size when first created. However, with ArrayLists, there is an initial size but when it becomes full, it automatically enlarges. When an element is removed, it automatically gets smaller.

Go to the Useful Links section on the course website for a link to Java API where you can find information about ArrayLists and the methods they have. Some suggested methods to use are : get, size, add, and remove.

Testing Using WordCountListTester (Sample Output)

To use WordCountListTester, run a line like:

java WordCountListTester nameOfInputFile.txt numberOfTopNWords {file|console}

The following is an example of using the WordCountListTester on the provided file (harry_potter.txt), printing the top 10 words that start with the letter ‘s’ on the console. Here the first argument is the name of the file. The second argument is numberOfTopNWords (number of most frequent words to be printed). The third argument is console (printing it to the console). The fourth argument is char indicating that we will be finding top numberOfTopNWords which begin with a given char value. The last argument is the value of the char i.e ‘s’

General format of printing the words with their counts is : word(count)&lt;space&gt; You need not print every word on a separate line.

1. The example below shows the output on the console. Note your display might be different from the following based on the width of your console.

&gt; java WordCountListTester inputFiles_DoNotSubmit/harry_potter.txt 10 console

Reading in File: inputFiles_DoNotSubmit/harry_potter.txt

Removing common words

Printing the top 10 words on console

Dursley(37) Mr.(29) Mrs.(19) –(13) people(12) cat(8) he’d(8) Dudley(7) owls(7) called(6)

2. The example below shows the output printing to a file called myOutput.out

&gt; java WordCountListTester inputFiles_DoNotSubmit/harry_potter.txt 10 file

Reading in File: inputFiles_DoNotSubmit/harry_potter.txt

Removing common words

Printing the top 10 words in file a named myOutput.out

And a file called myOutput.out should be created with the following contents:

Dursley(37) Mr.(29) Mrs.(19) –(13) people(12) cat(8) he’d(8) Dudley(7) owls(7) called(6)

Similarity Checker (Sample Output)

javac Similarity.java

This program takes exactly 2 arguments!

java Similarity starwars.txt harry_potter.txt

The files have a 1.3054830287206267% similarity.

java Similarity warandpeace.txt warandpeace.txt
