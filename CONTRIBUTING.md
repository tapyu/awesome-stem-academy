# Contribution Guidelines


## Table of Contents

- [This is an AWESOME list](#this-is-an-awesome-list)
- [Adding to this list](#adding-to-this-list)


## This is an AWESOME list

Which means that the list does not pretend to contain all the resources available in the world. Do not add well-known software packages, basic tutorials, documentation, etc. Instead contribute with bizarre links about the topics, amazing blog posts and tutorials, new software, interesting people, fresh insights, this essential book you have read and whatever you consider awesome! 

## Adding to this list

Please ensure your pull request adheres to the following guidelines:

- We have the `## Main subject` and the `### Subarea` sections. Don't create section for Science, Techonology, Engineering, or Mathematics. Rather, stich with the feilds of knowledge (E.g., Linear Algebra, Algorithm Theory, Electromagnetics, ...). Both the `## Main subject` and the `### Subarea` must be in [title case](https://capitalizemytitle.com/). If your main subject or subarea is formed by many names, you can use "&" instead of "and" for the sake of brevity, if you prefer. For example, `### Machine Learning & Neural Networks`.
- Try to accommodate your theoretical subject under the existing structures. If it is not possible, create a new section. Try as much as you can to create `### Subarea` within an existing `## Main subject` instead of creating a new `## Main subject`.
- Make sure your suggestion follows this structure:<br><br>
```&nbsp;&nbsp;:small_orange_diamond: <a href="link"><code>tag</code></a> <b>Short title</b> - A longer explanation.<br>```<br><br>
where:
    - `tag`: Mandatory. The following tags are allowed (you must obey this order when using multiple tags in an item):
        1. `course`: Suggestions for open-access courses shall use this tag. Whenever you use this tag, the short title must always be the course name and code (for instance, "EE364A, Convex Optimization I"), while the longer explanation must contain other information such as year, professor, platform name, etc. You must only add free (in "free beer" sense) courses.
        1. `book`: Suggestions for open-access books shall use this tag. If you use this tag without the `course` tag, the short title must be the book name, while longer explanation must contain other information, such as author, year, edition, issue, etc. You must only add open access links to books.
        1. `software-tool`: Any software, toolbox, or package about this topic shall use this tag.
        1. `solution`: Suggestions for book's solution manuals shall use this tag.
        1. `material`: Suggestions for articles, class notes, websites, videos (which don't belong to a course), etc, shall use this tag.
        1. `code`: Codes that implement specific algorithms or are the book's code solution shall use this tag.
        1. `dataset`: Any open dataset shall use this tag.
        1. `community`: Any online community where one can discuss more about this topic shall use this tag.
    - `Short title`: Mandatory.
    - ` - A longer explanation`: Optional. When used, you must separate it from the short title by using a dash character, that is, ` - `. No matter whether you use it or not, the suggestion must always end with a period.
- In some cases, you might want to use multiple tags. For instance, if you have a link to a book, to its solution manual, and to its code solution, you can suggest something like:<br><br>
&nbsp;&nbsp;:small_orange_diamond: <a href="https://drive.google.com/file/d/1zdIDyV8qDBWNmmlwhBw7EtLu_pyacdOh/view"><code>book</code></a> <a href="https://github.com/8128/SharedResources/blob/master/Introduction%20to%20Linear%20Algebra%205th%202016/Introduction%20to%20Linear%20Algebra%2C%205th%20%20(Solutions)%20%E2%80%93%202016.pdf"><code>solution</code></a> <a href="https://math.mit.edu/~gs/linearalgebra/ila5/indexila5.html"><code>material</code></a> <a href="https://www.mathworks.com/matlabcentral/fileexchange/2166-introduction-to-linear-algebra"><code>code</code></a> <a href="https://github.com/shahrokh-bahtooei/Linear-Algebra-Gilbert-Strang"><code>code</code></a> <b>Introduction to Linear Algebra</b> - Gilbert Strang. 5th edition.<br><br>
In this example, we have a link to the book, one solution manual, one material, and two code solutions which are all related to the book "Introduction to Linear Algebra". We gain conciseness at the cost of lack of details. When using multiple tag, follow these guidelines:
    - **You should use multiple tags in a same item only if their contents are closely related and if the relationship is easy to infer** (in the previous example, it is easy to understand that all links refer to the same book). If one of these conditions is not met, split the suggestion in multiple items using only one tag per item.
    - Don't try explain all tags in the short title or in the longer explanation. Instead, stick with the main tag, which is the first tag of the item (in the previous example, the main tag is `book`). All other tags add must be related to the main tag.
    - Although we can repeat a same tag multiple times if necessary, you cannot repeat the main tag multiple times. For instance, if `course` is the main tag of an item, you cannot have another `course` for it, but you can have multiple `book`, `software-tool`, etc.
