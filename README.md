To install the package, use the following code.

    install.packages("learnr","car","lsr","ggplot2")
    library(devtools)  
    install_github("chrisaberson/IntroStatsTutorials")  

To run a tutorial, use this code.

    library(learnr)  
    run_tutorial("terminology", package = "IntroStatsTutorials")
    run_tutorial("dataviz", package = "IntroStatsTutorials")
    run_tutorial("ct_dispersion", package = "IntroStatsTutorials")
    run_tutorial("normaldist", package = "IntroStatsTutorials")
    run_tutorial("correlation", package = "IntroStatsTutorials")
    run_tutorial("regression", package = "IntroStatsTutorials")
    run_tutorial("NHST", package = "IntroStatsTutorials")
    run_tutorial("ttest", package = "IntroStatsTutorials")
    run_tutorial("ANOVA1F", package = "IntroStatsTutorials")
    run_tutorial("ANOVA2F", package = "IntroStatsTutorials")
    run_tutorial("ChiSquare", package = "IntroStatsTutorials")

After you run this code, the tutorial will open in a tab on your
browser.

If this doesn’t work, you likely need to update your rtools. Go to
<a href="https://cran.r-project.org/bin/windows/Rtools/" class="uri">https://cran.r-project.org/bin/windows/Rtools/</a>
and download the most recent version (for your platform (Note: Rtools is
just for Windows, I am looking into other platforms). You may also, on
Mac OS have to install the backports package.
