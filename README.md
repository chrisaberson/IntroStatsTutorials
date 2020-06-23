To install the package, use the following code.

    install.packages("devtools")  
    install.packages("learnr")  
    library(devtools)  
    install_github("chrisaberson/IntroStatsTutorials")  

You will likely (if you are new to R), be directed to download RTools. Go to
<a href="https://cran.r-project.org/bin/windows/Rtools/" class="uri">https://cran.r-project.org/bin/windows/Rtools/</a>
and download the most recent version. If you are using a Mac, you will need to use a current operating system. 

You may also be prompted to update packages. Choose all (1), if prompted. 

This process may take several minutes. 

To run a tutorial, use this code..

    library(learnr)  
    library(IntroStatsTutorials)
    run_tutorial("Dataviz", package = "IntroStatsTutorials")

After you run this code, the tutorial will open, either in a separate RStudio standalone window or in a tab on your browser.
