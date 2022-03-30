<img src="https://firebasestorage.googleapis.com/v0/b/portfoliobymartinnilsen.appspot.com/o/Projects%2FsetupLatex.png?alt=media&token=850c745b-d9b6-41a6-a4b5-ccaff3f0523e" width="600" height="250" />


<center> 
    <h1>
        setupLatex
    </h1> 
</center>


---

Command Line Interface for setting up a LaTeX report based on a template without hassle. As of today there is only one assignment report template available, but feel free to create your own templates and include them to the project.

---

## How to get started

By downloading the project as a zip-file or cloning the repository, you can proceed to run

`pip install -r requirements.txt` 

for installing the required Python modules.

## Usage

The tool takes use of the `argh` module, making it possible to send arguments when running the command.

```
> setuplatex --help
usage: setuplatex [-h] [-p PATH] [-s SUBJECT] [-t TITLE] [-a AUTHOR] [-d DATE] [-T]

Creates a clean LaTeX report based on template, and fills in title page.

optional arguments:
  -h, --help            show this help message and exit
  -p PATH, --path PATH  Insert path to root directory (default: -)
  -s SUBJECT, --subject SUBJECT
                        Insert subject (default: -)
  -t TITLE, --title TITLE
                        Insert title (default: -)
  -a AUTHOR, --author AUTHOR
                        Insert author (default: -)
  -d DATE, --date DATE  Insert date (default: -)
  -T, --Template        Set template (default: False)
```
Note that the recommended usage is to use the shebang for not needing the file extension. Further on, proceed to mark it as an executable and add it to dirand you can run it in any working directories. For more information you can read this post on [StackOverflow](https://stackoverflow.com/questions/27494758/how-do-i-make-a-python-script-executable/27494871). You may also use aliases for the same purposes. If not you can always run the file from the correct directory, and send the path to the project you want the report folder to be placed.

---

If you were to find bugs in the code, feel free to create a PR, add an issue or send it to me on [mail](mailto:martinjnilsen@icloud.com?subject=[GitHub]%20Karakterkalkulator).

Licence: [MIT](LICENSE)