
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bnssg-quarto

This repository provides a quarto template and a project structure to
support BNSSG analytical teams to use R.

## Installation

### Using the Terminal

Before proceeding, make sure your “Terminal” options are correctly set.
To do this go to:

1.  **Tools \> Terminal \> Terminal Options**
2.  Select “New Terminals open with:” **Git Bash** (preferably), but if
    that isn’t an option, select **Windows PowerShell**
3.  Select **OK**
4.  **Tools \> Terminal \> New Terminal**

The template can be installed using the below command in the Terminal
tab in RStudio. A quirk is that you often can’t copy and paste with
Ctrl+V into a terminal, you have to right click and press paste, then
Enter.

``` bash
quarto use template nhs-bnssg-analytics/bnssg-quarto
```

5.  The terminal might then ask if you trust the authors of the template
    press `Y` and `Enter`

6.  The terminal will then ask for a `? Directory name:`, which you
    cannot leave blank. Give a sensible name to the folder you want the
    template files to be downloaded into, and press Enter. Files should
    then download.

7.  Go to the location of your new folder, open `MyQuartoTest.qmd` in R
    and that’s your template ready to go! You might need to run
    `install.packages` first on a few packages if they’ve not been
    installed before.

### Using GitHub Desktop

If you are not comfortable with the Terminal, you can follow the steps
using GitHub Dekstop [this
link](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop),
which requires having the program [GitHub
Dekstop](https://desktop.github.com/) installed first.

This should get you to step 7. above, where you can copy the files that
have been cloned across to the folder you’re wanting to use the Quarto
template in.
