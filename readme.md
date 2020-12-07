# Intro to data visualisation using ggplot

Delaney Glass, Li-Ying Wang, Gayoung Park, Anwesha Pan, Monica Keith, Shane Scaggs, Ben Marwick, & Melanie Martin

## Details

Date and time: 12/15/20 9am-11am Pacific Standard Time

You can join our workshop at this link:
https://washington.zoom.us/j/91569853974 

Here are our [slides](https://docs.google.com/presentation/d/15c764TPcJWQvoZasN5PtVxpwyyqEuLm8V-n7brMvx2I/edit#slide=id.gc6f90357f_0_0)

Backup is https://rstudio.cloud/ if you have a problem with your computer.

## Outline

### 1. Finding your way around R and RStudio (DG)
- Check everyone could download and open R & RStudio
- Check version numbers for R (we want 4.0.2)
- A brief tour of the main panes (Console, Files, Environ, text editor, pkgs and help) 
- Have to make sure everyone can make the console work before we move on, e.g. console as a calculator 

### 2. Starting a new RStudio project & installing R pkgs (DG) 
- Create a new RStudio project 
- Run `install.packages("tidyverse")` in the console

### 3. reading and inspecting data (LW)
- Read data and take a look, intro to dataframe
- Get basic summary information about our dataset

### 4. Data manipulation with dplyr and tidyr (LW)
- Select specific columns and rows using select () and filter ()
- Intro to the concept of pipes
- Create new columns using mutate ()

### 5. Data visualization with ggplot2- Histogram and Scatterplots (LW)
- Histogram for one variable
- Scatterplots for two variables 

### 6. Data visualization with ggplot2- Boxplots and Faceting (GP)
- Boxplots and play with themes
- Faceting to create multiple plots
- Name a title and change X & Y axis labels

## Setup instructions

Before you join the workshop, please make sure you have the most recent versions of R and RStudio installed on your computer. Here's how to get those programs:

<h3>R & RStudio</h3>

<p>
    <a href="https://www.r-project.org">R</a> is a programming language
    that is especially powerful for data exploration, visualization, and
    statistical analysis. To interact with R, we use
    <a href="https://www.rstudio.com/">RStudio</a>.
</p>


<h4 id="r-windows">Windows</h4>
<a href="https://www.youtube.com/watch?v=q0PjTAylwoU">Video Tutorial</a>
<p>
        Install R by downloading and running
        <a href="https://cran.r-project.org/bin/windows/base/release.htm">this .exe file</a>
        from <a href="https://cran.r-project.org/index.html">CRAN</a>.
        Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
        Note that if you have separate user and admin accounts, you should run the
        installers as administrator (right-click on .exe file and select "Run as
        administrator" instead of double-clicking). Otherwise problems may occur later,
        for example when installing R packages.
</p>

<h4 id="r-macosx">macOS</h4>
<a href="https://www.youtube.com/watch?v=5-ly3kyxwEg">Video Tutorial</a>
<p>
        Install R by downloading and running
        <a href="https://cran.r-project.org/bin/macosx/R-latest.pkg">this .pkg file</a>
        from <a href="https://cran.r-project.org/index.html">CRAN</a>.
        Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
</p>

<h4 id="r-linux">Linux</h4>
<p>
        You can download the binary files for your distribution
        from <a href="https://cran.r-project.org/index.html">CRAN</a>. Or
        you can use your package manager (e.g. for Debian/Ubuntu
        run <code>sudo apt-get install r-base</code> and for Fedora run
        <code>sudo dnf install R</code>).  Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
</p>

Further reading:

Content on this site is licensed under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/).
