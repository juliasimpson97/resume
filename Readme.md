<!-- Create a Dummy Resume Repository

Use JupyterLab to launch a terminal and use the terminal to do the following tasks:

Create a new directory called resume within your home directory
Create an empty file within this directory called Readme.md
Now use JupyterLab to edit the file:

Navigate to the directory in the file browser
Open Readme.md in the text editor
Open Readme.md in in Markdown Preview 
Arrange these files side-by-side so you can see your document rendered
Edit the file in the editor. Add the following information:
Top level heading with your name
An image. It can be a photo of you or, if you prefer, a photo of your spirit animal.
Secondary heading entitled “Education”
A list of schools you attended, hyperlinked to the websites of those insitutions
Save the file -->

# Julia L. Simpson

![JuliaPhoto](JuliaPhoto.png) <!-- Question: why does this not work with resume/JuliaPhoto.png? -->

## Education
### [*Columbia University*](https://www.columbia.edu)
*In Progress*: Ph.D. in Chemical Oceanography, Department of Earth and Environmental Sciences

### [*Washington University in St. Louis*](https://wustl.edu) <!--To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).-->
B.S. Chemical Engineering
> Minors in Energy Engineering, Environmental Engineering, and Psychology-Neuroscience-Psychology

### [*University College Dublin*](https://www.ucd.ie)
Semester Abroad in Chemical and Bioprocess Engineering

### [*National Taiwan University*](https://www.ntu.edu.tw/english/)
International Experience in Energy, Environmental, and Chemical Engineering

<!--Now go back to the terminal and do the following:

Initialize a new git repository in the resume directory: git init (after cd resume and ls to be sure in resume directory)
Add the Readme.md file to the repository: git add 
Create a new commit with a commit message: git commit GOT ERROR, had to write it config --global user.name "jls2391@columbia.edu" then just added test commit one to new screen, escape shift Z shift Z to exit
Check the git log to see your commit history : git log, confirm worked, test commit one there--> 

<!--
Go to GitHub and create a new public repository entitled resume
Push your local resume repository to GitHub following the instructions.
View your online resume at http://github.com/<your github username>/resume
Finally, go back to the editor and add a new subsection called “Research Interests” to your Readme.md file. Update your local git repository and push your changes to GitHub. Verify that the remote repository is updated.-->


## Research Interests
### [*McKinley Ocean Carbon Group*](https://galenmckinley.github.io)
Julia is a first-year PhD student in the McKinley group. Her research is conducted through the NSF-funded Learning the Earth through Artificial Intelligence and Physics (LEAP) center, where she utilizes machine learning to study ocean carbon uptake representations in the Community Earth System Model.

Her general topics of interest include: chemical oceanography, machine learning, climate data science, and air-sea interaction.

<!-- To “hand in” this part of the assignment, put a link to it in the Readme.md file in the next part. -->

<!-- Create your Assignments Repository

Now that you know how to create a git repository, you should create your assignments repository.

Create a new directory called rces-assignments in your home directory. : git init rces-assignments, then cd rces-assignments
Create a Readme.md markdown file that contains your name and a link to your “resume” repo.
Initialize a new git repository
git remote add origin git@github.com:juliasimpson97/rces-assignments.git
git branch -M main : must use master instead of main
git push -u origin main :must use master instead of main
Add the file and make your first commit
Create a new private repository on GitHub called rces-assignments. (Call it exactly like that. Do not vary the spelling, capitalization, or punctuation.)
Push your rces-assignments repository to GitHub :had to remove origin, using git remote remove origin, and confirm with git remote -v
On GitHub, go to “settings” -> “collaborators” and add tjcrone and cjuang.
Push new commits to this repository whenever you are ready to hand in your assignments

Other troubleshooting/directions from github:
git remote add origin https://github.com/juliasimpson97/resume.git
git branch -M main
git push -u origin main 
git remote set-url origin git@github.com:juliasimpson97/resume.git then git remote -v