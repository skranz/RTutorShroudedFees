Authors:
  Tobias Krabel (main author)
  Sebastian Kranz (some modifications)

This package constitutes an interactive R tutorial about the AER paper **"The Impact of Shrouded Fees: Evidence From a Natural Experiment in the Indian Mutual Funds Market"** by Santosh Anagol and Hugh Hoikwang Kim. You learn about shrouded fees in investment funds, and applied econometrics and data analysis in R. The problem set is based on the RTutor package (https://github.com/skranz/RTutor) that allows to interactively solve R exercises. Note that RTutor and this problem set are still in a preliminary version.

## 1. Installation

To install RTutor and this problem set run in R the following 4 lines of codes:
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)
  
install_github("skranz/RTutorShroudedFees")
```

## 2. Show and work on the problem set
To start the problem set first pick a directory in which you want to store files related to the problem set and your solution. Then adapt and run the following code.

```s
library(RTutorShroudedFees)

# Adapt your working directory to an existing folder
setwd("D:/libraries/RTutor/examples")
setwd("C:/problemsets")
# Adapt your user name
run.ps(user.name="Jon Doe")
```
If everything works fine, a browser window should open in which you can start exploring the problem set.