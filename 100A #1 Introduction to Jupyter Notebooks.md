# 100A #1: Introduction to Jupyter Notebooks
You have been learning R in the textbook using the *DataCamp* interface. But statisticians and data scientists don't use *DataCamp* in their work. They use either RStudio or Jupyter Notebooks. The main advantage of these platforms is that they enable you to save your work and continue it later.
## 1. Jupyter Basics
Here are a few basic concepts to get you started with Jupyter Notebooks:
1. **A notebook is a page.** The page you are looking at right now is a single Jupyter Notebook. In some ways it is like any other document. But there is one important difference: if you write code on a Jupyter Notebook page the code can be run right on the page. And if you run the code, the output will be inserted on the page right below the code.
2. **A notebook consists of a series of *cells*.** There are two main types of cells: a *markdown* cell, which is used for entering text; and a *code* cell, which is used for entering R code. (We have over-simplified a bit here, but this is enough to get you started.) The text you are reading now is inside of a *markdown* cell. A little further down the page we will show you some *code* cells.
3. **A notebook is a great way to organize, present, and share a data analysis.** The notebook format fits well with the practice of data analysis. In a *markdown* cell you can pose questions and then propose a data analysis plan. You can then add a *code* cell to write R code and actually run the analyses you want to run. After you run an analysis, you can add another *markdown* cell to interpret the results of the anlysis you ran.


## 2. Jupyter Notebooks Have Two Modes

**Edit mode:** To enter EDIT mode, press ENTER on your keyboard, double-click in a markdown cell, or click in a code cell. Edit mode can be identified by a green border around the cell with green left margin. When you are in edit mode, you can type in the cells.

**Command mode:**
To enter COMMAND mode press ESC or click anywhere outside the cell. You will see a grey border around the cell with a blue left margin. When you are in COMMAND mode, you can't type in the cells. But you can use keystroke equivalents for navigating around your notebook. (Click the keyboard icon on the toolbar to start learning keystroke equivalents.)

## 3. Markdown Cells
Now lets take a closer look at how *markdown* cells work. Here are some key points:
1. Click on a cell (go ahead and click on this one). The blue bar on the left side shows that the cell is selected.
2. Look at the dropdown menu on the far right side of the toolbar and you will see that it says **Markdown**. That's how you can tell for sure what kind of cell you have selected. (You also can use the dropdown to change one cell type to another.)
3. When you double-click in a markdown cell **(don't do it yet)**, it puts the cell in **edit** mode, and you can then modify the contents of the cell.
4. When you are in edit mode the markdown text isn't as nicely formatted. Markdown is a way to enter plain text, and make it look nicely formatted when it is finally rendered in a page. 
5. To render a *markdown* cell when it is in **edit** mode you just need to **run** it. You can do this in a number of ways:

-Click on the **Cell** menu (above the toolbar) and select **Run Cells**

-Click on the **Run** button on the toolbar

-Hit **Shift + Return**

<div class="alert alert-block alert-info">
<b>TRY THIS:</b> Double-click in the markdown cell above to go into </b>edit</b> mode. Notice that the text gets ugly! Now </b>run</b> the cell using any of the three methods above. It renders the text back into its nicely-formatted state.
</div>

## 4. Edit a Markdown Cell
Using just a few *markdown* conventions you can make your Jupyter Notebook look nice and organized. To add headings and subheadings you just put some # symbols at the beginning of a line. 
# First Level Headings
To add a first level heading just put a single # symbol, then a space, before a line of text (as we did here). 
## Second Level Headings
For these you put two ## followed by a space in front of a line of text, etc.
### And here's a third level

**Putting two asterisks in front of and at the end of some text makes the text bold.**
*Putting a single asterisk in front of and at the end of some text makes it italics.*
Putting a dash and space at the beginning of a line adds a bullet. Like this:
- Item 1
- Item 2
- Item 3

Note that you can also do some fancy stuff in Jupyter Notebooks, like show alert boxes in different colors. You don't need to worry about this, except to note that we will sometimes use color to make our notebooks easier to follow (like in the paragraph below).

<div class="alert alert-block alert-info">
<b>TRY THIS:</b> Click somewhere here to select this markdown cell. Then double-click to go into edit mode. Edit the text in the cell however you want, then run the cell (using <b>Shift + Return</b>.) See how it works? Go ahead and practice making more changes, then running the cell.
</div>

## 5. Code Cells
Now let's look at *code* cells and see how they work. The cell right below this one is a code cell. One way to instantly see that it's a code cell is that it has the notation `In [  ]:` off to the left of it. 

By now you probably recognize the R code in the cell below: it tells R to print out the phrase "Hello World." The `In` means **Input**. After you run the code, the **output** will appear below it. 

<div class="alert alert-block alert-info">
<b>TRY THIS:</b> Click in the code cell below (you can just click where it says "Hello World") to select it. Note that the bar to the left turns green indicating that you are in edit mode. Now </b>run</b> the code cell by clicking <b>Shift + Return</b> (or by using either of the other two methods you've learned for running a cell).
</div>


```R
print("Hello World")
```

    [1] "Hello World"


Notice that two things happened when you ran the code cell:
1. The output of the code suddenly appeared right below the code:
`[1] "Hello World"`
2. The text to the left of the code cell changed from `In [ ]` to `In [1]` 

<div class="alert alert-block alert-warning">
    <b>QUESTION:</b> What do you think the <b>[1]</b> means where it says <b>In [1]</b> to the left of the code cell? See if you can figure it out. Try running the cell again. How does it change? What does it mean?
</div>


[write your answer in this *markdown* cell]
