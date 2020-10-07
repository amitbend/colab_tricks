# Google Colab Tricks and Best Practices

![Colab Tricks & Best practices](https://github.com/amitbend/colab_tricks/raw/master/media/Colab%20Tricks.png)


# `1. Commands & Tricks`

## ✔ 1.1 Run all *but*

**What?** Paste `%%script false --no-raise-error` at the start of the cell to avoid cell to Run when using "Run All"


**Why?** Helpful when you don't want to run a cell which doesn't contribute to the overall run or just a part of the exploration phase.
For example EDA cells 


</br></br>
## ✔ 1.2 Undo tricks

**What?** Use `Ctrl+Z` to undo latest changes in a cell scope, use Ctrl+M+Z for cell level undo` 

**Why?** Helpful when you don't want to run a cell which doesn't contribute to the overall run or just a part of the exploration phase.
For example EDA cells 


<br/><br/>
## ✔ 1.3 Peek definition on Colab

**What?** `Ctrl+Click` top peek on the function definition. if it's your function - you can peek on the whole cell

**Why?** Looking at the implentation details of a function which already defined requires a lot of scrolling, peek definition allows you to open it side by side with your current cell, run it, scoll or copy it into a scratch cell

!['colab peek example'](https://github.com/amitbend/colab_tricks/blob/master/media/peek.png?raw=true)


<br/><br/>



# `2. Notebook Structure Practices`

## ✔ 1.1 Structure 

**What?** TBD

**Why?** TBD


<br/><br/>

# `3. Utilities 

## ✔ 3.1 Find and replace 

To find and replace items **globally** hit `Ctrl+H`
To find and replace in a cell hit `Ctrl+D`, it will auto select matches to the keyword one by one


<br/><br/>


design inspired by https://github.com/goldbergyoni/nodebestpractices
