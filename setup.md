---
layout: page
title: Setup
---


<h3>Software</h3>

<p>
  For this course you will need the UNIX shell and <a href= "http://www.sqlite.org/">SQLite3</a>.
</p>

<p>
If you are running <strong>macOS</strong> you should already have SQLite installed. You can run `sqlite3 --version`
in a terminal to confirm that it is available.  
</p>

<p>
If you are running <strong>Linux</strong>, you may already have SQLite3 installed, please use the command
`which sqlite3` to see the path of the program, otherwise you should be able to get it
from your package manager (on Debian/Ubuntu, you can use the command `apt install sqlite3`).  
</p>

<p>
If you are running <strong>Windows</strong>, run installers as administrator. You may find the latest release of SQLite <a href= "http://www.sqlite.org/">on their website</a>.
Additionally, make sure you select the right installer version for your system.
We recommend that you use <a href= "https://gitforwindows.org/">git for Windows</a>.
This is described in the <a href= "http://swcarpentry.github.io/shell-novice/setup.html">UNIX Shell lesson</a>.
If the installer asks to add the path to the environment variables, check yes, otherwise you have to manually add the path of the executable to the `PATH` environmental variables.
This path informs the system where to find the executable program. Once Git for Windows is installed, you can open a terminal by running the program "Git Bash" from the Windows start menu.
</p>

<p>
  If installing SQLite3 using Anaconda, refer to the <a href="https://anaconda.org/anaconda/sqlite">anaconda sqlite docs</a>.  
</p>

<p>
After the installation and the setting of the paths, close the terminal and reopen a new terminal.
This enables paths and configurations to be loaded.  
</p>

<h3>Files and Libraries</h3>

Please download the database we'll be using:
- <a href= "https://github.com/UCSBCarpentry/2022-02-04-ucsb-sql-online/blob/gh-pages/data/survey.db?raw=true">survey.db</a>. Be sure to unzip if needed, and put the file in a location that easily accessible (e.g. desktop).

If you wish to access a database from R during the Workshop, ensure you have a recent version of RStudio: In RStudio, go to the <strong>Help</strong> tab and select <strong>Check for Updates</strong>. You also need to install the RSQLite Package: In RStudio, go to the <strong>Tools</strong> tab and select <strong>Install Packages...</strong>.  

From Repository (CRAN), search for and install "RSQLite".  
