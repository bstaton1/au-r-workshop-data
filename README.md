# au-r-workshop-data

This repository houses the data for the R workshop and book: Introduction to R for Natural Resource Scientists. The book is located at the URL: <https://bstaton1.github.io/au-r-workshop/>.

To acquire the data for this book, you should:

  1.  click the green _Clone or download_ button at the top right of this page,
  2.  click _Download ZIP_,
  3.  and unzip the contents of this folder into the location on your computer: `C:/Users/YOU/Documents/R-Book/Data`
  
When `YOU` is replaced with something specific to your computer. The full file path does not need to be the same as above, but it is recommended to at least maintain the `/R-Book/Data` portion. Make sure you place this somewhere easy to find on your computer.

## Data Descriptions

Each of the data files is described below, listed in alphabetical order.

####`asl.csv`

**Description**

Contains the ages, sexes, and lengths of approximately 50,000 Chinook salmon (_Oncorhynchus tshawytscha_) sampled over 50 years (1996-2015).

**Source**: simulated by author

**Variables**:

*  `year`: the year the individual fish were sampled
*  `sex`: the sex of the sampled fish
*  `age`: the age of the sampled fish
*  `length`: the length of the sampled fish, in mm, mid-eye to fork of tail length

**Found in Chapter(s)**: 5

---

####`creel.csv`

**Description**

Contains the number of hours fished by 300 anglers separated by the fishery sector each angler participated in.

**Source**: simulated by author

**Variables**:

*  `fishery`: the fishery sector the angler participated in: "Harvest", "Non.Tournament", "Tournament"
*  `hours`: the number of reported hours the angler fished in the year of interest.

**Found in Chapter(s)**: 2

---

####`daily_catch.csv`

**Description**

Contains the daily harvest of pink salmon (_Oncorhynchus gorbuscha_) in a commercial fishery. Records span the same 50 days in each of 50 consecutive odd-numbered years (1917-2015).

**Source**: simulated by author

**Variables**:

*  `doy`: the day of the year the observation corresponds to.
*  `y_*`: 50 columns which separate the year each observation corresponds to.

**Found in Chapter(s)**: 5

---

####`daily_escape.csv`

**Description**

Contains the daily escapement counts of pink salmon (_Oncorhynchus gorbuscha_) made at a counting tower. Records span the same 50 days in each of 50 consecutive odd-numbered years (1917-2015).

**Source**: simulated by author

**Variables**:

*  `doy`: the day of the year the observation corresponds to.
*  `y_*`: 50 columns which separate the year each observation corresponds to.

**Found in Chapter(s)**: 5


