# python_repo_template
a bare-bones Python repository template. This example repo includes all of the Topsakal Lab GitHub Repo requirements (plus a few extra things to make it pretty).

The project description should be at the top of the repo and offer a summary in 3-5 sentences of what the project is. If your project is a continuation, include that.

For additional README.md formatting and markdown, refer to an official guide such as:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax


## Table of Contents
* [Implementation](#implementation)
* [Requirements](#requirements)
* [Organization](#organization)
* [Installation](#installation)
* [Running the Project](#running-the-project)
* [Team Members](#team-members)
* [Citations and References](#citations-and-references)
* [Related Publications and Repositories](#related-publications-and-repositories)


## Implementation
If your project requires hardware, a specialized environment, or other lab equipment, note that here. 

If another program needs to be installed to interface with your code, mention that here. A block diagram might be useful if you need to link multiple projects/programs/devices.


## Requirements

It is HIGHLY recomended to set up a virtual environment for your project. Instructions on how to do that with VSCode are at: https://code.visualstudio.com/docs/python/environments 

Library requirements for locally run Python code are included in requirements.txt and can be 
installed using 'pip install -r requirements.txt'

This project has tested with Python 3.# (primary development).

```python
copy the list from requirements.txt here to show users what they're downloading/installing at a glance
```

Optionally, requirements can be installed manually with:

```python
pip install wxPython, matplotlib, pandas, numpy, ezdxf, Pint, pcb-tools, pcb-tools-extension

```
This is an example for if you've had a difficult time with the requirements.txt file. Sometimes libraries are packaged together.

## Organization

The simplified project structure is shown below.  Full file structure will be updated in the documentation for future collaboration efforts. 

```python
.
├── python_repo_template
|
├── .docs                               # directory for detailed project documentation.
│   └── ...                             # documentation as PDFs.
|
├── .media                              # directory for project media.
│   └── ...                             # imgs, gifs, icons, other small files.
|
├── .src                                # directory for source code of the project.
│   │
│   ├── ...                             # root of the project code.
│   │
│   └── main.py                         # main program file. The project entry point.
|
├── README.md                           # this README.
├── .gitignore                          # the repository gitignore file.
└── requirements.txt                    # project requirement minimum.
```



## Installation

If the project requires a specific setup, license, etc. briefly describe that here. 

If the project needs other code to run, mention that in 'implementation'. This section should answer the question of "what do I do when I've downloaded the GitHub repo".

If your code just runs in VSCode, then mention that.

Python projects will always require some setup. It is highly suggested that extensions, plug-ins, comd compiler versions be listed so that others can replicated the process.

The following were installed for this example:
* VSCode:
  * Python language extension

* Local computer:
  * Python language compiler (https://www.python.org/downloads/)



## Running the Project

This project should be run from main.py, either in an IDE or with 'python main.py'. 

While there are unit testing artifacts in some code files, entry at other points in the program will cause some features to not work. 

It is recommended to run this project in a virtual environment, but it is not a requirement. 



## Team Members

Projects will often have many contributors, sometimes over a number of years. 
If you work on a project, add your name, a contact email, what your roll on the project was, and when you worked on it.

Do not delete old team members. (but you can delete the placeholders below)


|       Name                  |   Best Contact Email          |                 Who Am I?             |     Year on the Project       |
| --------------------------- | ----------------------------- | ------------------------------------- | ----------------------------- |
| Michael Suche               | suchemj@vcu.edu               | Wireless Communications Lab Manager   | 2023 - present                |
| Sarah Johnson               | johnsonse28@vcu.edu           | Ph.D Student                          | 2024 - present                |
| Amber Nunnally              | nunnallyag@vcu.edu            | Ph.D Student                          | 2025 - present                |        
| Lauren Linkous              | linkouslc@vcu.edu             | Post Doc & MDS Testbed Manager        | 2022 - 2024                   |




## Citations and References
Use IEEE format for all citations and references. Include links when possible.
These include tutorials, websites, journals, and other material used to create or continue this project. 


## Related Publications and Repositories

If this project has its own publications or other supporting repositories. Link those here. Use IEEE format for publications.
