## Commands , < arguments?> ##

# pwd
lists the present working directory (working directory is the directory you are currently in on your command line)
# cd < insert directory name?>
routes you to anothers working directory (change directory)
# mkdir < insert new directory name?>
makes a new direcotry in the PWD
# rmdir < insert directory .>
removes the directory inserted
# rm < insert fileName .>
removes a file
# touch < insert file name .>
creates a new file in the working directory
# ls < can take directory name .>
lists all files in the working directory
# clear
takes you to a clean line in the directory terminal (scroll back up to see previous work)

## GIT commands ## 

# git clone < repository URL .>
downloads repository to your local PWD

# git init
starts a local git repository

`(PULL ALL UPDATES BEFORE BEGGINNING WORK, then add, then commit your changes and then push)`

# git pull <server/branch.>
receives commits from the server (can use git pull "server name" or "branch name")

# git add < file/folder name.> (step 1/3 of sending data out)
Tracks a file or folder (you can use "git add ." to track everything)

# git commit <-m> <message.> (step 2/3 of sending data out)
takes a snapshot of the directory as it is in the moment the command is run.
(if you forget to type -m you will be pushed into vs (a command line text editor). 
hit the `i` key (to insert) then type your message, then press `esc`, then :wq and then `enter`)

# git push < server/branch.> (step 3/3 of sending data out)
sends your commits to the server (can use git push "server name" or "branch name")

`(PULL ALL UPDATES BEFORE BEGGINNING WORK, then add, then commit your changes and then push)`


## Special Directories ##


takes you home

..
takes you up a directory level

.
keeps you at the same directory level

/
takes you to the root (top level) directory

## HTML Syntax Basics
# < > 
necessary for creating a line of code

# < a href="www.link.example.com" > </a > 
how to create a link reference

# < h1> <h/1 > - 
Heading 1 is the largest heading (replace the # up to 6 total headings)

### HTML Containers
#<html> </html> 
begins and ends the entire code top and bottom of page, everything else is contained within (there can be only 1)

# <head> </head>
wraps the header of the page (there can be only 1)

# <body> </body>
wraps all the main content (there can be only 1)

# <div> </div>
Contains content sections (can alternatively use <header> <nav> <footer> for cleaner organization)

# <p> </p>
Paragraphs within <div>

### Common HTML TAGS

# <strong> </strong>
bold

# <em> </em>
emphasis

# <img> </img>
images

#<a href> </a href>
links

#<li> </li>
lists items

#<title> </title>
title

#<br> </br>
line break (avoid if possible)

# <table> </table>
Table

# <!-- -->
(comments)

#See less common tags @ http://www.w3schools.com/tags/

###Common UI (user interface) form elements:

# <form> </form>
creates a form section in HTML

# <input> </input>
Input Boxes (there are many, look up in W3schools)

# <label> </label>
Lables for boxes

# <button> </button>
Button

# <textera> </textera>
Large textbox

### CSS Syntax
css works by hooking onto selectors added into HTML using classes and identifiers.
Once hooked, we apply STYLES to those HTML elements using CSS.

#CSS Example = a { background-color: yellow; }  
a= selector 
background-color: = property
yellow; = 
{} Curley brackets

Put each Class or ID on their own line

#Class Selectors
#In HTML:
<body>
    <div class="box-set">
        <figure class="box box-1">Box 1</figure>
        <figure class="box box-2">Box 2</figure>
    </div>
</body>

#In CSS:
.box-set {
        Position:relative;
        width: 150px;
        height: 150px;
        background: #2db34a;
        border: 2px solid black;
}

##CSS Style Tags <style></style> 
(set under the head section or reference and external style sheet)

# Color - sets color
font-size 
font-style
font-weight

#Allignment
margin (margin the measurement of the workable area)
border (defined area surrounding the padding and content)
padding (the buffer space around a content block)
float ( allows sections of code to align next to each other)

#Background
background-color
background-image

###CSS Style Examples: 

#Insheet Style Example below would only effect the H1 category
H1 {
    margin-top: 15px;
    font-size: 20px;
    text-align: center;
}

# Class Style external sheet
in head section of html link the external style sheet:
<link rel="reference" 
in css create the style classes

in html 


