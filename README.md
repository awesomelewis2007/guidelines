# Guidelines

A set of guidelines that I follow when writing code and working on projects.

## Table of Contents

- [Markdown](#markdown)
- [General Code](#general-code)
- [Commit Messages](#commit-messages)


## Markdown

Markdown should be used for all documentation. It is a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

Always Use the `.md` file extension for all markdown files.

Each project should have a `README.md` file in the root directory. This file should contain a description of the project, how to install it, how to use it, and how to contribute to it.

The `README.md` file should be written in [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

The `README.md` file should be structured as follows:

```markdown
# Project Name

A brief description of what this project does and who it's for

Content of the README.md file

## Licence

This project is licensed under the [licence name](link to licence file)
```



## General Code

All code should be written in English. This includes comments, commit messages, and documentation. This is to ensure that all code is consistent and easy to understand. All code should be written in the same style. This includes indentation, spacing, and naming conventions.

When starting a project all files that can have comments excluding documentation should have a comment at the top of the file that contains the following information:

```python
# Project Name
# Project Description
# Github Link
# Licence
# Author
```

For example:

```python
# Py scanner
# A metasploit like tool but for scanning and retrieving data from websites.
# Github: https://www.github.com/awesomelewis2007/pyscan
# Licence: GNU General Public License v3.0
# By: Lewis Evans
```

## Commit Messages

Commit messages should be written in the present tense. For example:

```
Add new feature

Signed-off-by: Author Name <Author Email>
```

If you are writing a commit message that is longer than one line then you should use the following format:

```
Add new feature

Changed the way that the program works so that it is more efficient.

Files changed:
- main.py
- README.md

By removing the need to do X the program now runs 10x faster. This is because Y and Z. This also means that the program is now more secure because of A and B.

Signed-off-by: Author Name <Author Email>
```

All commits should be signed off. This is to ensure that all commits are traceable to a person. This is done by adding the `Signed-off-by` line to the end of the commit message. This should be done by adding the following line to the end of the commit message:

```
Signed-off-by: Author Name <Author Email>
```