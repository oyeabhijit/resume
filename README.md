# Resume
<img alt="LaTeX" src="https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white"/>

* Single Page LATEX document to efficiently create resume without using Google Docs or Microsoft Word

### Requirements
* An [OverLeaf](https://www.overleaf.com/) Account

### Steps to get the LaTeX document working
1. Download this repository as ZIP
2. Open your Overleaf account
3. Create a new project & give a name as you like
4. Unzip the repo ZIP
5. Locate resume.tex and resumeclass.cls in the folders
6. In your overleaf workstation, on top left corner click on upload
7. Select resume.tex and resume.cls
8. Edit the LaTeX file as you like

* Remember not to rename any of the files.

### DOCUMENT START section
1. In ```\name{Abhijit Rout}``` change it to your name replacing Abhijit Rout
2. In ```\address{(+91)~$\cdot$~824xxxxxxx\\``` replace 824xxxxxxx with yout own contact number
3. In```\href{mailto:abhijitxxxxxxxxxx@gmail.com}{abhijitxxxxxxxxxx@gmail.com} \\``` Replace with your own email address
   In```\href{https://www.github.com/oyeabhijit}{github.com/oyeabhijit} \\``` Replace the links with your own github link
   In```\href{https://www.linkedin.com/in/oyeabhijit}{linkedin.com/in/oyeabhijit}}``` Replace the links with your own linkedin link

### EDUCATION section
1. There are 3 ```\begin{rSubsection}```
2. The first Subsection is for Bachelors Degree,  second is for 12th School, and the third section is for 10th School.
3. Each section has a name of Institution, Degree Information, Marks Obtained and City name. 

### WORK EXPERIENCE section
1. The subsection ```\begin{rSubsection}``` contains details about name of company, date of join & date of leave, name of your working position and job loaction.
2. ```\item``` are unordered lists which explains your work experience in that internship/job

### PROJECTS section
1. Each ```\begin{rSubsection}``` contains the name of the projects, project link and date.
2. Each ```\item``` represent the unordered list which explains what you learned from the proejct

### TECHNICAL SKILLS section
1. In ```\begin{tabular}``` change topic after the parenthesis

Example:
Change
```
Languages & Python, Java, LaTeX \\
Web skills & HTML5, CSS, JavaScript \\
Tools & Figma, Adobe Creatuve Cloud Suite, Blender, MySQL
```
to this
```
Languages & Languege 1, Languege 2, Languege 3 \\
Web skills & Skill 1, Skill 2, Skill 3 \\
Tools & Tool 1, Tool 2, Tool 3, Tool 4
```

### INTERESTS section
1. In ```\begin{rSection}``` change your interests in ```Astronomy~$\cdot$~Computer Vision~$\cdot$~Photogrammetry~$\cdot$~Psychology\\```
2. Chnage hobbies in ```3D Modeling~$\cdot$~Tech Article Writing~$\cdot$~UI Designing~$\cdot$~Pixel Art```

### ADDITIONAL SKILL section
1. In ```\begin{rSection}{Additional Skills}```,  change your skills for every ```~$\cdot$~```

### Saving the document as pdf
* In the top right of PDF section, click download. It will download your resume in .pdf extension

### Preview
![Resume Screenshot](/resumess.png)
