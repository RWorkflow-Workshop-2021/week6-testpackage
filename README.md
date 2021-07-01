# TestPackage
A small package for students to experiment with.

To install, use this code. You might need to install the **devtools** package.
```
# install.packages("devtools")
devtools::install_github("RWorkflow-Workshop-2021/week6-testpackage")
```

To run the example
```
library(TestPackage)
dat <- WWWusage
littleforecast(dat, nyears=100)
```

