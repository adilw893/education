# Markdown resources

---

## Projects / use cases

- [ ] GitHub
- [ ] Spark notebooks
- [ ] [Rmd][rmd] files
- [ ] use Markdown Here browser extension for writing email and other web forms (try in Gmail)
- [ ] create website via [GitHub Pages](https://pages.github.com/) / [Jekyll][jek]
- [ ] self-publish a book on [Leanpub][lp]

---

## Books
- [x] The Markdown Guide - Matt Cone (PDF)  

[companion site](https://www.markdownguide.org/) included in [links](../markdown#links) below  
created by [John Gruber]((https://daringfireball.net/projects/markdown/)) in 2004, WYSIWYG editor (what you see is what you get)  
1. create file with a `.md` or `.markdown` extension  
2. open file in a Markdown app  
3. convert Markdown file to an HTML document  
4. view HTML file in a web browser or use app to convert to another file format (like PDF)  

[Markdown Cheat Sheet](../markdown/markdown-cheat-sheet.md)  

you can still use HTML tags within Markdown documents (such as for changing text color, etc.)  
but be careful about mixing and matching (Markdown won't format accurately within HTML tags)  

headings are created by putting one to six `#` in front of heading text  

paragraph breaks are created with a blank line in betweeen blocks of text  

line breaks are made by adding 2+ spaces to end of a line ('trailing whitespace')  
and another option for line breaks is to use the HTML break tag `<br>` <br>

*italic text* is wrapped with single `*` (best practice) or `_`  
**bold text** is wrapped with double `**` (best practice) or `__`  
***bold and italic text*** uses three `***` (best practice) or `___` (or combinations thereof)  

> blockquotes are made with a leading `>`  
> they can span multiple lines and paragraphs  
>> they can also be nested with multiple `>>`  
>> and they support *some* Markdown formatting  

1. ordered lists use numbers followed by periods, e.g., `1.`
6. the first item has to start with a 1, but otherwise they don't need to be in any order
    1. and they can be nested too via indenting
* unordered lists are made with `*`, `+`, or `-`
  - and of course support indented nesting
* and the different list types can be mixed too
  1. nest an ordered list within an unordered list
  2. and vice versa

use tick marks \` to display `inline code`  
and you escape ``code that contains `tick marks` in it`` with double ticks \`\`  
triple ticks \`\`\` allow for a fenced code block like this:  
```
# this is my code
hw <- 'hello world'
print(hw)
```

horizontal rules are made of a separate line with just three `---`, `___`, or `***`  
put blank lines before and after horizontal rules, otherwise text could display as heading (an alternate style to using `#`)  

inline-style links are `[text enclosed in brackets](url 'optional tooltip title')`  
a quick link can just use angle brackets `<url>`, but some Markdown processors don't even require brackets and just create links automatically  
    if you'd like to disable the automatic linking, use tick marks to denote it as code, e.g., `` `url` ``  
reference-style links are broken into two parts:  
* in paragraph: `[text to display][link reference]`
* anywhere else in your document: `[link reference]: url`
* generally placed at end (like footnotes)  

images are added just like links, except with a `!` in front of the `[bracketed text (which becomes the caption)]`  

use a backslash `\` in front of a Markdown formatting character to escape it and display the literal character  
e.g., `\*` displays the \* rather than starting an unordered list  

extended syntax (beyond Gruber's original design) available in certain lightweight markup languages, such as:
* [Common Mark](https://commonmark.org/)
* [GitHub Flavored Markdown (GFM)][gfm]
* [Markdown Extra](https://michelf.ca/projects/php-markdown/extra/)
* [MultiMarkdown](https://fletcherpenney.net/multimarkdown/)
* [R Markdown](https://rmarkdown.rstudio.com/)

tables can be built with `---` and `|`  
e.g.,  
```
|syntax|description
|---|---
|header|title
|paragraph|text
```
becomes  
|syntax|description
|---|---
|header|title
|paragraph|text

and add colons to the header hyphens to align text
* left align = `:---`
* center align = `:---:`
* right align = `---:`

tables also support links, inline code, and emphasis (but not fenced code blocks, headings, blockquotes, lists, horizontal rules, images, or HTML tags)  

to display a pipe character `|` within a table, use the HTML character code `&#124;` to escape  

use triple ticks `` ``` `` before and after code to create fenced code blocks  
and you can specify the language for syntax highlighting after the triple ticks: `` ```R `` or `` ```python ``  

for task lists, `- [ ]` creates an empty checkbox, and `- [x]` marks it as checked  

~~strikethrough~~ text with double `~~`  

emojis can be copied and pasted (from a source like [Emojipedia](https://emojipedia.org/))  
e.g., 🥰  
or some Markdown applications have their own emoji shortcodes
e.g., `:tent:` or `:joy:` become :tent: and :joy:

*AJD - footnotes do not appear to work for GFM...*  

~~add footnotes similar to reference-style links~~
~~1. use a caret and identifier within brackets, such as `[^1]`~~
~~2. then define it somewhere else in the document, e.g., `[^1]: footnote text`~~

*AJD - custom heading IDs do not appear to work for GFM...*  

~~adding custom heading IDs allos you to link directly to headings and modify them with CSS~~  
~~make custom heading IDs with curly braces `### Heading {#custom-id}`~~  
~~then link within the file using that ID `[text](#custom-id)`~~  
~~or link from other websites with full URL and ID `[text](https://www.mywebsite.com/documentation#custom-id)`~~  

*AJD - definition lists do not appear to work for GFM...*  

~~some Markdown processors allow for definition lists~~
```
term
: definition
```
~~becomes~~
~~term~~
~~: definition~~

- [ ] **[Learn Markdown](https://gitbookio.gitbooks.io/markdown/content/)**


### Bookdown
- [ ] [R Markdown: The Definitive Guide - Yihui Xie, J.J. Allaire, Garrett Grolemund](https://bookdown.org/yihui/rmarkdown/)
- [ ] [R Markdown Cookbook - Yihui Xie, Christophe Dervieux, Emily Riederer](https://bookdown.org/yihui/rmarkdown-cookbook/)
- [ ] [blogdown: Creating Websites with R Markdown - Yihui Xie, Amber Thomas, Alison Presmanes Hill](https://bookdown.org/yihui/blogdown/)
- [ ] [bookdown: Authoring Books and Technical Documents with R Markdown - Yihui Xie](https://bookdown.org/yihui/bookdown/)
### Additional books...
- [ ] *Introducing Markdown and Pandoc - Thomas Mailund (free?)*
- [ ] *The Beginner's Guide to Markdown and Pandoc - Thomas Mailund (free?)*
- [ ] *Learn Markdown - Khurshid Alam (free?)*
- [ ] *Reproducible Research with R and RStudio - Christopher Gandrud (free?)*
- [ ] *Instant Markdown - Arturo Herrero (free?)*
- [ ] *Learning Markdown: Write for the Web, Faster - Bakari Chavanu (free?)*

---

## Courses
### Udemy
- [ ] [Markdown Essentials](https://www.udemy.com/course/markdown-essentials/)
### Udacity
- [ ] [Writing Readmes](https://www.udacity.com/course/writing-readmes--ud777)
### edX
- [ ] [Data Science Productivity Tools](https://www.edx.org/course/data-science-productivity-tools)
- [ ] [Data Science Tools](https://www.edx.org/course/data-science-tools)
- [ ] [Principles Statistical and Computational Tools for](https://www.edx.org/course/principles-statistical-and-computational-tools-for)
### Coursera
- [ ] [Open Source Tools for Data Science](https://www.coursera.org/learn/open-source-tools-for-data-science)
- [ ] [Data Scientists Tools](https://www.coursera.org/learn/data-scientists-tools)
- [ ] [Perfecting Readme](https://www.coursera.org/projects/pefecting-readme)

---

## Links
### Tutorials
- [x] [The Markdown Guide](https://www.markdownguide.org/): companion site to [Matt Cone's book](../markdown#books) above
- [ ] **[John Gruber's Markdown documentation](https://daringfireball.net/projects/markdown/): creator of Markdown**
- [ ] [Markdown Tutorial](https://www.markdowntutorial.com/)
- [ ] [Awesome Markdown](https://github.com/mundimark/awesome-markdown): GitHub repo featuring a collection of Markdown goodies
- [ ] https://www.youtube.com/watch?v=6A5EpqqDOdk
- [ ] https://five.squarespace.com/display/ShowHelp?section=Markdown
- [ ] https://chibicode.github.io/markdown-toolbar-cheatsheet/
- [ ] http://code.ahren.org/markdown-cheatsheet
- [ ] https://www.toptal.com/web/markdown-the-writing-tool-for-software-developers
- [ ] https://www.abhaytalreja.me/markdown-crash-course-learn-markdown-in-30-minutes-markdown-cheatsheet/
- [ ] https://medium.com/programmers-developers/building-books-with-markdown-using-pandoc-f0d19df7b2ca
- [ ] https://learn.getgrav.org/17/content/markdown

### GitHub
- [x] [Mastering Markdown](https://guides.github.com/features/mastering-markdown/): GitHub Guides

can use Markdown on GitHub in gists, comments, and `.md` files  
GFM also supports directed comments (called '@mentions') to individuals and teams with the `@` symbol  
if you include a task list `- [ ]` in the first comment of an issue or pull request, you will get a progress indicator in your issue list  
using a number that refers to an issue or pull request will automatically be converted into a link, e.g., `#1`  

- [ ] [Writing on GitHub](https://docs.github.com/en/github/writing-on-github): GitHub Docs
- [ ] **[GitHub Flavored Markdown Spec][gfm]**
- [ ] [GitHub Pages][ghpages]: turns Markdown files into a website and hosts them for free (uses [Jekyll][jek] as the backend)

### Browser tools
- [x] [Markdown Here](https://markdown-here.com/): browser extension that converts Markdown text in website forms (e.g., Gmail, Evernote) to properly-formatted rich text
  installed on Mac, `CTRL` + `ALT` + `M` = toggle shortcut (otherwise right click)
- [ ] [Dillinger](https://dillinger.io/): online Markdown editor
- [ ] [StackEdit](https://stackedit.io/): online Markdown editor

### Build a website
- [ ] [Jekyll][jek]: static site generator that takes Markdown files and builds an HTML website ([GitHub Pages][ghpages] provides free hosting for Jekyll-generated websites)
- [ ] [Ghost Guide to Markdown](https://ghost.org/changelog/markdown/): tutorial from [Ghost](https://ghost.org/), a free blogging platform / content management system (CMS)

### Self-publishing
- [ ] [Leanpub][lp]: self-publish Markdown-formatted ebooks
- [ ] [How I wrote and published my novel using only open source tools](https://medium.com/techspiration-ideas-making-it-happen/how-i-wrote-and-published-my-novel-using-only-open-source-tools-5cdfbd7c00ca): blog on self-publishing experience

### Emojis
- [ ] [Emojipedia](https://emojipedia.org/): searchable index of emojis that can then be copied and pasted into Markdown files
- [ ] [Complete list of GitHub Markdown emoji](https://gist.github.com/rxaviers/7360908): list of GFM emoji shortcodes
- [ ] [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md): every emoji GitHub supports

### Lightweight markup languages
- [ ] [Common Mark](https://commonmark.org/): lightweight markup language
- [ ] [GitHub Flavored Markdown (GFM)][gfm]: lightweight markup language
- [ ] [Markdown Extra](https://michelf.ca/projects/php-markdown/extra/): lightweight markup language
- [ ] [MultiMarkdown](https://fletcherpenney.net/multimarkdown/): lightweight markup language
- [ ] [R Markdown][rmd]: lightweight markup language



[gfm]: https://github.github.com/gfm/
[ghpages]: https://pages.github.com/
[jek]: https://jekyllrb.com/
[lp]: https://leanpub.com/
[rmd]: https://rmarkdown.rstudio.com/
