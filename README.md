# cs252-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CS252 Project #1 Solved](https://www.ankitcodinghub.com/product/cs-252-fall-23-computer-organization-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120274&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS252 Project #1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Assembly Project #1

1 Purpose

In this project, you’ll be getting some basic experience with how to write assembly language. You will write a simple function (which we’ll name studentMain()), and in it you will perform some simple tasks.

1.1 Required Filenames to Turn in

Name your assembly language file asm1.s.

You will also turn in a short report about the code that you wrote. The purpose of this is primarily to make sure you actually start using MARS for development (rather than simply leaning on the grading script). Using MARS will help you understand things better – even if it takes a little bit of time to get to know it.

To make sure we can read it, your report must be a PDF.

1.2 Resources

Before you get started, make sure to check out my Panopto video, which I’ve posted to the class, which gives you a good introduction into how to use the MARS simulator.

Also, you should go to the class website, and look up the assembly language style guide that I’ve posted. The TAs will be checking to verify that you followed the style guide!

2 The Report

NOTE: You will need to compose your code before you can write the report. So read the section on the task requirements first, and also read up on how to run using the MARS gui. But after your code is ready, come back and write this report.

For this project, in addition to writing some assembly, you also need to write a short report, detailing some features of your code. To find out the required information, load up your solution (asm1.s), and also one of the testcases. The easiest way to do this is to put both of these files in the same directory (with no other .s files), and then turn on the “Compile all files in directory” option of MARS.

Assemble these two files, and do a quick test run to make sure that your code works (check to see if the output produced looks right; for this part of the project, you don’t have to confirm that it’s perfect).

For the first part of your report, you need to find some place where you used an LA instruction to get the address of some variable provided to you by the testcase. In MARS, you can do this as follows:

If it’s not already active, click on the “Execute” tab, near the top left of the window.

Inside Execute, you should see the “Text Segment” at the top. This is your code. Scroll up and down that window until you see your LA instruction. (Use the line numbers to help you find it.)

You will find that the LA instruction is actually a pseudoinstruction it actually is implemented as 2 instructions in hardware.

Set a breakpoint at your LA instruction. (Breakpoints are the check-boxes on the left edge of the Text Segment window.) Then re-run the program again from the beginning. Your program will automatically pause when your LA instruction is just about to run.

Look for the “Run one step at a time” button on the toolbar; use it to run exactly two instructions. You will see that the first one modifies the register $at (MARS will highlight that register in the “Registers” pane on the right). The second instruction is the one that actually will modify the register that you mentioned in your LA instruction.

First item for your report – The address of some variable.

Now, look more closely at what LA did. It put the address of the variable into the register you chose. Give the address in hexadecimal.

If all of the registers are in decimal instead of hexadecimal, look at the Settings menu to change them to hexadecimal.

Second item for your report – The two instructions that make up LA

Next, look at the two instructions which make up the LA pseudoinstruction (the first is LUI). Write down, for your report, exactly what MARS shows in the Basic column of the Text Segment for these two instructions. The register names won’t look familiar – this column uses register numbers instead of names – but the second instruction should have a number that you’ve seen before.

Third item for your report – Hex encodings

Finally, write down the actual 32-bit hex encodings of these two instructions (which you can find in the Code column). Do you see the constants used by these instructions stored inside those encodings somewhere?

Thus, the first part of your report should include:

The full 32-bit address of the variable, in hex.

The full text of the assembly instructions which make up the LA pseudoinstruction.

The encodings of both instructions, also as 32-bit hex numbers.

2.1 Strings and Data

The second part of your report will observe how strings are loaded into memory. (Choose any one of the string constants that you used in your code.)

Find where you declared this constant in assembly (probably an .asciiz directive). Look at the first four characters of that string. Compare these four to an ASCII table (I link to one from the class webpage, but basically any ASCII table will work). What are the ASCII codes (in hex) for these four characters?

Now, find the LA instruction in your code which reads this string. Run the program to that point, and use it to figure out the address of this string in memory. (It probably starts with 0x1001….)

Now, look at the Data Segment window (just below the Text Segment). Each row of this table represents 32 (0x20) bytes of data; on the left, you can see the addresses that the rows represent. Scroll until you can see the region of memory where your string is.

(If you are completely in the wrong section of memory, use the drop-down at the bottom of the Data Segment window to choose what region you’re looking at. You want the .data section.)

Once you’ve found the right row, look across the columns to find the cell that represents where your string is. (Each cell is 4 bytes of data.) Look for hex values that match the ASCII codes you’re expecting. If your string address is a multiple of 4, then they should all be inside the same word of memory; if your address is not aligned (which is just fine for strings), then they will be spread across two words.

What do you notice? Probably, you’ll see that the characters appear to be in reverse order!

For the second part of your report, write down:

The entire string constant from your code that you chose to use.

The ASCII codes (in hex) for the first 4 characters in that string.

The address where the string ended up.

The word (or maybe 2 words) in memory which contained the ASCII codes you were expecting.

Finally, write at least one paragraph about your investigation. You can discuss any one (or more) of the following questions:

What was something new that you learned from this exercise, and how might you use it in the future?

What questions do you have that were inspired by this exercise?

Explain your process for finding the information required by this exercise. Include screenshots to show what you saw, and discuss a bit of what you did.

I mentioned that the constant loaded by the LA instruction is present in the two instructions that LA becomes. Looking at the instruction encodings, what can you conclude about where the constants are stored?

Turn in all three parts of your report to GradeScope, along with your code.

3 Allowable Instructions

When writing MIPS assembly, the only instructions that you are allowed to use (so far) are:

add, addi, sub, addu, addiu, subu and, andi, or, ori, xor, xori, nor beq, bne, j slt, slti sll, sra, srl lw, lh, lb, sw, sh, sb

la syscall

While MIPS has many other useful instructions (and the assembler recognizes many pseudo-instructions), do not use them! We want you to learn the fundamentals of how assembly language works – you can use fancy tricks after this class is over.

4 Standard Wrapper

Your code will need to define a single function, named studentMain(). Later, when you learn how to write functions, things will get more interesting; for now, you should just copy-paste the code below.

The following lines of code should be placed before your first instruction. This declares the function studentMain(), makes it available to the testcase, and then also gives the function “prologue” – that is, the basic code to start a function.

.globl studentMain studentMain:

addiu $sp, $sp, -24 # allocate stack space — default of 24 here sw $fp, 0($sp) # save caller’s frame pointer sw $ra, 4($sp) # save return address addiu $fp, $sp, 20 # setup main’s frame pointer

(spec continues on the next page)

The following lines of code should be placed after your last instruction; this implements the “epilogue”, which basically is the return statement at the end

of your function.

lw $ra, 4($sp) # get return address from stack

lw $fp, 0($sp) # restore the caller’s frame pointer

addiu $sp, $sp, 24 # restore the caller’s stack pointer

jr $ra # return to caller’s code

(Both of these pieces should be inside a .text section.)

5 Task Overview

You must never assume that you know the relative arrangement of variables in any of the projects this semester (except when the data is an array). So don’t assume that mar is 4 bytes beyond feb, and load it using an offset! Instead, always load the address of each variable independently.

(To check that you’re doing this, some of my testcases will shuffle up the order of the variables!)

5.1 Task 1: minimum

For this task, you will read the six variables and compare them to each other. Then, print out the smallest value, along with a little description, like this: minimum: 123

HINT: This code will be easiest to write if you use a register to keep the smallest value so far – and you compare that against each of the variables.

5.2 Task 2: negate

NOTE: For this task, you will use all six values.

Read each of the values. Arithmetically negate each one, and store it back into its slot in memory. Note: If you fail to store the values back into memory, you will fail operations which follow this one – because they’ll read the wrong values.

Then, just so that I know that you did something, print ‘‘NEGATE’’.

5.3 Task 3: evens

For this task, read all six values. Check to see if each one is even; print the ones that are even, one per line. (Don’t print anything about the odd values.)

So that I can be sure you did something, you must print ‘‘EVENS START’’ at the beginning, before any of the numbers, and ‘‘EVENS END’’ after the last one.

But wait – I haven’t shown you how to do division in assembly (yet). How are you going to check to see if a number is even or odd? To do this, use the ANDI instruction to mask off certain bits. Which bits should be 0 or 1, to tell you if a number is even or odd? Which ones can be ignored, and thus masked off?

5.4 Task 4: Print

For this task, print out the six values, as shown below. Put each value on its own line, with a string in front of it, giving its name. It should look like this:

6 Implementation Hint

One possible way to implement this project, which saves on code duplication, is to load all of the variables into registers first, before you do any checking. (Note: If you do this, you still ought to store into memory in the “negate” task, even if you also have a copy in a register.)

If you do this, then document which registers are used for each variable, with a block comment at the head of your function. Be careful not to modify any of these registers – otherwise, actions taken during one task might affect another.

6.1 Requirement: Don’t Assume Memory Layout!

To make sure that you don’t make this mistake, we will include testcases that have the variables in many different orders.

7 Running Your Code

You should always run your code using the grading script before you turn it in. However, while you are writing (or debugging) your code, it often handy to run the code yourself.

7.1 Running With Mars (GUI)

This will open a GUI, where you can edit and then run your code. Put your code, plus one testcase, in some directory. Open your code in the Mars editor; you can edit it there. When it’s ready to run, assemble it (F3), run it (F5), or step through it one instruction at a time (F7). You can even step backwards in time (F8)!

7.1.1 Running the Mars GUI the First Time

The first time that you run the Mars GUI, you will need to go into the Settings menu, and set two options:

Assemble all files in directory – so your code will find, and link with, the testcase

Initialize Program Counter to ’main’ if defined – so that the program will begin with main() (in the testcase) instead of the first line of code in your file.

7.2 Running Mars at the Command Line

You can also run Mars without a GUI. This will only print out the things that you explicitly print inside your program (and errors, of course). However, it’s an easy way to test simple fixes. (And of course, it’s how the grading script works.) Perhaps the nicest part of it is that (unlike the GUI, as far as I can tell), you can tell Mars exactly what files you want to run – so multiple testcases in the directory is OK.

To run Mars at the command line, type the following command: java -jar &lt;marsJarFileName&gt; sm &lt;testcaseName&gt;.s &lt;yourSolution&gt;.s

8 A Note About Grading

Your code will be tested automatically. Therefore, your code must:

Use exactly the filenames that we specify (remember that names are case sensitive).

Not use any other files (unless allowed by the project spec) – since our grading script won’t know to use them.

Follow the spec precisely (don’t change any names, or edit the files I give you, unless the spec says to do so).

(In projects that require output) match the required output exactly! Any extra spaces, blank lines misspelled words, etc. will cause the testcase to fail.

To make it easy to check, I have provided the grading script. I strongly recommend that you download the grading script and all of the testcases, and use them to test your code from the beginning. You want to detect any problems early on!

8.1 mips checker.pl

In addition to downloading grade asm1, you should also download mips checker.pl, and put it in the same directory. The grading script will call the checker script.

8.2 Testcases

For assembly language programs, the testcases will be named test *.s . For C programs, the testcases will be named test *.c . For Java programs, the testcases will be named Test *.java . (You will only have testcases for the languages that you have to actually write for each project, of course.)

Each testcase has a matching output file, which ends in .out; our grading script needs to have both files available in order to test your code.

8.3 Automatic Testing

We have provided a testing script (in the same directory), named grade asm1, along with a helper script, mips checker.pl. Place both scripts, all of the testcase files (including their .out files), and your program files in the same directory. (I recommend that you do this on Lectura, or a similar department machine. It might also work on your Mac or Linux box, but no promises!)

8.4 Writing Your Own Testcases

The grading script will grade your code based on the testcases it finds in the current directory. Start with the testcases I provide – however, I encourage you to write your own as well. If you write your own, simply name your testcases using the same pattern as mine, and the grading script will pick them up.

9 Turning in Your Solution

You must turn in your code to GradeScope. Turn in only your program; do not turn in any testcases.

In addition, you must turn in your report (see details above). Part of your score for Asm 1 will come from this report.
