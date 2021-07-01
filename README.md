# TestPackage
A small package for students to experiment with.

To install, use this code. You might need to install the **devtools** package.
```
devtools::install_github("RVerse-Tutorials/TestPackage")
```

To run the example
```
library(TestPackage)
dat <- WWWusage
littleforecast(dat, nyears=100)
```

