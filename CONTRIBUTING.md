# Contribution Guidelines

## Adding to this list

### What to add

> What **is** a STEM academic resource?
- Books, courses, and codes that implements algorithm which require some theoterical background from a field of Science (e.g., Physics), Technology, Engineering, and Mathematics.
> What **is not** a STEM academic resource?
- Suggestions of programming language itself (e.g., Python crash course, Julia cheat sheet, etc).
- Software and hardware (e.g., a specific board development board).

### How to add

**The contributors are encouraged to condense related contents into one single item**. For instance, if you took an [MOOC](https://en.wikipedia.org/wiki/Massive_open_online_course) course, which used a specific book that contains a solution manual, and you solved the all the computational homeworks from this course. You are encouraged to create a single item with all these gathered links.

Please ensure that your pull request adheres to the following guidelines:

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
        1. `solution`: Suggestions for book's solution manuals shall use this tag. If the solution is code, you must use `code` instead.
        1. `reading`: Suggestions for articles, class notes, websites, or any other reading material shall use this tag.
        1. `video`: Suggestion for isolated videos (which don't belong to a course or a playlist) shall use this tag. Very small playlists consisting of few short-duration videos should use this tag if you find more sensible than tagging it as `course`.
        1. `code`: Codes that implement specific algorithms or are the book's code solution shall use this tag.
    - `Short title`: Mandatory. It must not have hyperlinks.
    - ` - A longer explanation`: Optional. It must not have hyperlinks. When used, you must separate it from the short title by using a dash character, that is, ` - `.
- The item must always end with a period.
- In some cases, you might want to use multiple tags in the same item. For instance, if you have many links related to a book, you can suggest something like:
    - [`book`](https://drive.google.com/file/d/1zdIDyV8qDBWNmmlwhBw7EtLu_pyacdOh/view) [`solution`](https://github.com/8128/SharedResources/blob/master/Introduction%20to%20Linear%20Algebra%205th%202016/Introduction%20to%20Linear%20Algebra%2C%205th%20%20(Solutions)%20%E2%80%93%202016.pdf) [`reading`](https://math.mit.edu/~gs/linearalgebra/ila5/indexila5.html) [`code`](https://www.mathworks.com/matlabcentral/fileexchange/2166-introduction-to-linear-algebra) [`code`](https://github.com/shahrokh-bahtooei/Linear-Algebra-Gilbert-Strang) **Introduction to Linear Algebra** - Gilbert Strang. 5th edition.

  In this example, we have one link to the book, one to solution manual, one to material, and two to code solutions which are all related to the book "Introduction to Linear Algebra". We gain conciseness at the cost of lack of details. When using multiple tags, follow these guidelines:
    - **You should use multiple tags in a same item only if their contents are closely related and if the relationship is easy to infer** (in the previous example, it is easy to understand that all links refer to the same book). If one of these conditions is not met, split the suggestion in multiple items.
    - Don't try to explain all tags in the short title or in the longer explanation. Instead, stick with the main tag, which is the first tag of the item (in the previous example, the main tag is `book`). All other added tags must be related to the main tag.
    - Although we can repeat a same tag multiple times if necessary, you cannot repeat the main tag multiple times. In the previous example, you can use as many `reading`, `code`, etc... as you need, but you cannot add another `book` tag to this item. Exceptional cases should be duly justified in the PR.
    - `solution` cannot be a main tag.
