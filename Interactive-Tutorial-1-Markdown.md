# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Sarah.

I am a member of the Fluoride Gravity team at AguaClara.

## Headers

Make a 3rd level header with your name:

### Sarah

## Emphasis

Write 4 of your favorite words using each type of emphasis:

_petrichor_ **ineffable** **_effervescent_** ~~seafoam~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Join more organizations
  a. like AguaClara!
2. Learn more about fluid dynamics!!
3. Not freeze
  a. it is too cold

* Differential Equations
* Physics 1112
* Cell and Developmental Biology

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[Chemical Engineering](https://www.cheme.cornell.edu/cbe) is a very multifaceted major with many different applications such as in energy or biology.

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

  <img src="/images/Cornell_University_seal.png">

  <img src="https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/images/Cornell_University_seal.png">

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals       | Books              | Places|
| ------------- |:-------------:     | -----:|
| Dog           | The Little Prince  | SF    |
| Cat           | Slaughterhouse Five| Hawaii|
| Dolphin       | Catch 22           | Home  |


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

>Just because you're trash doesn't mean you can't do great things. It's called garbage can, not garbage cannot.
-Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
