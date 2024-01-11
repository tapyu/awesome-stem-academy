# Contribution Guidelines


## Table of Contents

- [This is an AWESOME list](#this-is-an-awesome-list)
- [Adding to this list](#adding-to-this-list)


## This is an AWESOME list

Which means that the list does not pretend to contain all the resources available in the world. Do not add well-known software packages, basic tutorials, documentation, etc. Instead contribute with bizarre links about the topics, amazing blog posts and tutorials, new software, interesting people, fresh insights, this essential book you have read and whatever you consider awesome! 

## Adding to this list

Please ensure your pull request adheres to the following guidelines:

- **You must only suggest STEM academic resources**:
    - Technologies geared to academia (e.g., CI/CD to Data Science projects, Open-Hardware projects for signal processing, etc) are allowed, but those technologies that have no adherence with the academia must be avoided.
    - Suggestions of programming language itself (e.g., Python crash course, Julia cheat sheet, etc) are not considered an academic resources.
- Two section levels are allowed: `## Main subject` and `### Subarea`.
    - Both the `## Main subject` and the `### Subarea` must be in [title case](https://capitalizemytitle.com/).
    - You can add items in both `## Main subject` and `### Subarea`.
    - Don't create sections named `## Science`, `## Techonology`, `## Engineering`, or `## Mathematics`. Rather, stick with the feilds of knowledge (e.g., `## Linear Algebra`, `## Algorithm Theory`, `## Electromagnetics`, ...).
    - If your main subject or subarea is formed by many names, you can use "&" instead of "and" for the sake of brevity, if you prefer. For example, `### Machine Learning & Neural Networks`.
    - Try to accommodate your theoretical subject under one of the existing sections. If it is not possible, create a new section and follow these guidelines:
        - Try as much as you can to create `### Subarea` within an existing `## Main subject` instead of creating a new `## Main subject`.
        - Don't modify the table of contents manually. There is a GitHub workflow that does it for us.
- Make sure your suggestion follows this structure:<br><br>
```- [tag](www.link.com) **Short title** - A longer explanation.```<br><br>
where:
    - `tag`: Mandatory. The following tags are allowed (you must obey this order when using multiple tags in an item):
        1. `course`: Suggestions for open-access courses shall use this tag. Whenever you use this tag, the short title must always be the course name and code (for instance, "EE364A, Convex Optimization I"), while the longer explanation must contain other information such as year, professor, platform name, etc. Playlists with structured sequence of videos are consired a course. You must only add free (in "free beer" sense) courses.
        1. `book`: Suggestions for open-access books shall use this tag. If you use this tag without the `course` tag, the short title must be the book name, while longer explanation must contain other information, such as author, year, edition, issue, etc. You must only add open access links to books.
        1. `dataset`: Any open dataset shall use this tag.
        1. `hardware`: Open-source hardware projects, proprietary hardware, or development board platforms shall use this tag.
        1. `software`: Open-source software projects, proprietary programs, toolboxs, or packages shall use this tag.
        1. `solution`: Suggestions for book's solution manuals shall use this tag.
        1. `material`: Suggestions for articles, class notes, websites, or any other reading material shall use this tag.
        1. `video`: Suggestion for isolated videos (which don't belong to a course or a playlist) shall use this tag.
        1. `code`: Codes that implement specific algorithms or are the book's code solution shall use this tag.
        1. `community`: Any online community where one can discuss more about this topic shall use this tag.
    - `Short title`: Mandatory. It must not have hyperlinks.
    - ` - A longer explanation`: Optional. It must not have hyperlinks. When used, you must separate it from the short title by using a dash character, that is, ` - `.
- The item must always end with a period.
- In some cases, you might want to use multiple tags in the same item. For instance, if you have a link to a book, to its solution manual, and to its code solution, you can suggest something like:
    - [`book`](https://drive.google.com/file/d/1zdIDyV8qDBWNmmlwhBw7EtLu_pyacdOh/view) [`solution`](https://github.com/8128/SharedResources/blob/master/Introduction%20to%20Linear%20Algebra%205th%202016/Introduction%20to%20Linear%20Algebra%2C%205th%20%20(Solutions)%20%E2%80%93%202016.pdf) [`material`](https://math.mit.edu/~gs/linearalgebra/ila5/indexila5.html) [`code`](https://www.mathworks.com/matlabcentral/fileexchange/2166-introduction-to-linear-algebra) [`code`](https://github.com/shahrokh-bahtooei/Linear-Algebra-Gilbert-Strang) **Introduction to Linear Algebra** - Gilbert Strang. 5th edition.

  In this example, we have one link to the book, one to solution manual, one to material, and two to code solutions which are all related to the book "Introduction to Linear Algebra". We gain conciseness at the cost of lack of details. When using multiple tag, follow these guidelines:
    - **You should use multiple tags in a same item only if their contents are closely related and if the relationship is easy to infer** (in the previous example, it is easy to understand that all links refer to the same book). If one of these conditions is not met, split the suggestion in multiple items using only one tag per item.
    - Don't try to explain all tags in the short title or in the longer explanation. Instead, stick with the main tag, which is the first tag of the item (in the previous example, the main tag is `book`). All other added tags must be related to the main tag.
    - Although we can repeat a same tag multiple times if necessary, you cannot repeat the main tag multiple times. In the previous example, you can use as many `software-tool`, `solution`, etc... as you need, but you cannot add another `book` tag to this item.
