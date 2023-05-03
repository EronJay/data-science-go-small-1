##code of how to install R in linux
sudo apt-get update
##how to download a file from a URL and save it to a local file
wget https://raw.githubusercontent.com/oceanumeric/data-science-go-small/main/drawio/R-data-table-illustration.drawio
##how to read a google sheet into a data.table and skip over bad lines

```r
install.packages("curl")
library(curl)
install.packages("data.table")
library(data.table)
link <- "https://docs.google.com/spreadsheets/d/1Ral3hG1AHCuiaWYtB3taCSKuWl_j1_A0aKOTb_uh43E/edit?usp=sharing"
fread(link, skip = 1)

```

