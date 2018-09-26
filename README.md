# au-r-workshop-data

This repository houses the data for the R workshop and book: Introduction to R for Natural Resource Scientists. The book is located at the URL: <https://bstaton1.github.io/au-r-workshop/>.

**To acquire the data for this book**, you should:

  1.  click the green _Clone or download_ button at the top right of this page,
  2.  click _Download ZIP_,
  3.  and unzip the contents of this folder into the location on your computer: `C:/Users/YOU/Documents/R-Book/Data`
  
Where `YOU` is replaced with something specific to your computer. The full file path does not need to be the same as above, but it is recommended to at least maintain the `/R-Book/Data` portion. Make sure you place this somewhere easy to find on your computer.

## Data Sets

The contents of each data file is described below, listed in alphabetical order.

#### `asl.csv`

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

#### `creel.csv`

**Description**

Contains the number of hours fished by 300 anglers separated by the fishery sector each angler participated in.

**Source**: simulated by author

**Variables**:

*  `fishery`: the fishery sector the angler participated in: "Harvest", "Non.Tournament", "Tournament"
*  `hours`: the number of reported hours the angler fished in the year of interest.

**Found in Chapter(s)**: 2

---

#### `daily_catch.csv`

**Description**

Contains the daily harvest of pink salmon (_Oncorhynchus gorbuscha_) in a commercial fishery. Records span the same 50 days in each of 50 consecutive odd-numbered years (1917-2015).

**Source**: simulated by author

**Variables**:

*  `doy`: the day of the year the observation corresponds to.
*  `y_*`: 50 columns which separate the year each observation corresponds to.

**Found in Chapter(s)**: 5

---

#### `daily_escape.csv`

**Description**

Contains the daily escapement counts of pink salmon (_Oncorhynchus gorbuscha_) made at a counting tower. Records span the same 50 days in each of 50 consecutive odd-numbered years (1917-2015).

**Source**: simulated by author

**Variables**:

*  `doy`: the day of the year the observation corresponds to.
*  `y_*`: 50 columns which separate the year each observation corresponds to.

**Found in Chapter(s)**: 5

---

#### `feeding.csv`

**Description**

Contains the results of an experiment where the investigator manipulated the density of a prey item and observed how many were consumed by a predator in a given time interval. The experiment was replicated 50 times at randomly-generated prey densities. 

**Source**: simulated by author

**Variables**:

*  `prey`: the density of the prey item
*  `cons*`: the number of prey consumed by the predator

**Found in Chapter(s)**: 4

---

#### `growth.csv`

**Description**

Contains 100 samples taken randomly from a fish population. The length (total length; mm) and age (years) are recorded.

**Source**: simulated by author

**Variables**:

*  `age`: the age of the fish in years
*  `length`: the total length of the fish in mm.

**Found in Chapter(s)**: 3,4

---

#### `ponds.csv`

**Description**

Contains data from a hypothetical pond experiment. Nutrients were experimentally added to 5 replicated mesocosms within two different ponds. The ponds had 5 replicate mesocosms for the control group (no nutrients added) per pond as well.

_There is an error in this data set you should fix using a spreadsheet program before reading it into R (this was intentional)._

**Source**: simulated by author

**Variables**:

*  `pond`: identifier for the pond: `S.28` or `S.30`
*  `treatment`: identifier for the treatment type: `Add` or `Control`
*  `replicate`: the id for the replicate within each pond/treatment combination
*  `chl.a`: measurements of average chlorophyll _a_ present in each mesocosm
*  `daph`, `bosm`, `cope`, and `chao`: measurements of average density of four zooplankton taxa in each mesocosm

**Found in Chapter(s)**: 1,4

---

#### `sockeye.csv`

**Description**

Contains records of various biological variables measured for both hatchery and wild fish in paired years from the Redfish Lake sockeye salmon (_Oncorhynchus nerka_) in Idaho. 

**Source**: Kline and Flag ([2004](https://bstaton1.github.io/au-r-workshop/ch2.html#ref-sockeye-cite))

**Variables**:

*  `year`: the year the observation corresponds to
*  `type`: the type of fish the observation corresponds to
*  `weight`: the average weight (grams) of fish
*  `fecund`: the average number of eggs carried by females
*  `egg_size`: the diameter of the average egg (mm)
*  `survival`: the average percent survival of all eggs laid to the `eyed-egg` stage

**Found in Chapter(s)**: 2,3,4

---

#### `streams.csv`

**Description**

Contains information on 20 streams in the Southeastern United States.

**Source**: simulated by the author

**Variables**:

*  `state`: the state the stream is located in
*  `stream_width`: the width of the stream
*  `flow`: the flow rate of the stream (volume/sec)

**Found in Chapter(s)**: 1

---

### Chapter 6 Data

Henry will put stuff here using similar formatting as Ben. He will try to include all references in some format. 
