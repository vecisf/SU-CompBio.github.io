---
layout: page
title: PhD Course
permalink: /course/
---

## General information

Lecture outlines, recommended reading material and other information for the PhD
course at Semmelweis University, titled "Adatelemzés és programozás orvos
biológusoknak I". This semester, the course will be in hungarian, but the
notes are in english.

The course builds heavily on the [Carpentries
Foundation](https://carpentries.org/) material and teaching philosophy. It is
intended for beginners, with no or very little programming knowledge.

**Location**: Histology Seminar Room (ground floor), Semmelweis University,
1<sup>st</sup> Department of Pathology and Experimental Cancer Research, H-1085
Budapest, Üllői út 26.

**Time**: every Wednesday, from 16:30 to 18:00, starting with the 4<sup>th</sup>
of September.

**Requirements**: participants must bring a laptop with a Mac, Linux, or Windows
operating system (not a tablet, Chromebook, etc.) that they have administrative
privileges on. They are also required to abide by the [Carpentries Code of
Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html).

**Grading and homeworks**: there are going to be 12 short homework exercises (no
homework for Week 1 and Week 8), where you will be asked to think about a
problem, try to solve it, and most importantly, document your thoughts, the
issues or problems you ran into. You will need to submit one or a few small text
files, tables, documents, or scripts through Dropbox File Requests. We are going
to discuss solutions and issues next week. You will need to submit at least 6 of
them to pass, and 10 for excellent. Keep in mind that you are here to
learn and try things out. Active participation, discussing issues and asking
questions is much more important, than submitting perfectly written programming
exercises.

**Contact**: send an email to sebestyen.endre at med dot semmelweis-univ dot hu
if you have any questions or comments.

**Teachers**: Endre Sebestyén, Bence Szalai, Gábor Turu, Miklós Cserző

## Week 1 - 4<sup>th</sup> of September - Endre Sebestyén

*Introduction, software installation, getting around in R and RStudio.*

[Presentation]({{ site.url }}/assets/phd_course/eloadas_2019-09-04.pdf)

Delivery plan:

- Explain content of course
- Explain Code of Conduct
- Explain name labels
- Explain stickies and feedback
- Homeworks and grading
- Short introduction from everybody
- R and RStudio download and setup
- Getting started with R and RStudio
- Discussing *your own* data and analysis plans

### R and RStudio installation

We will use the R programming language, RStudio, and command line tools during
the semester that need to be set up first. Right now, we will install R and
Rstudio.

If you run into issues: [Common configuration problems and
solutions](https://github.com/carpentries/workshop-template/wiki/Configuration-Problems-and-Solutions)

[R](https://www.r-project.org/) is a programming language that is especially
powerful for data exploration, visualization, and statistical analysis. To
interact with R, we use [RStudio](https://www.rstudio.com/).

#### Windows

[Video tutorial](https://www.youtube.com/watch?v=q0PjTAylwoU)

Install R by downloading and running
[this](https://cran.r-project.org/bin/windows/base/release.htm) .exe file from
[CRAN](https://cran.r-project.org/index.html). Also, please install the [RStudio
IDE](https://www.rstudio.com/products/rstudio/download/#download). Note that if
you have separate user and admin accounts, you should run the installers as
administrator (right-click on .exe file and select "Run as administrator"
instead of double-clicking). Otherwise problems may occur later, for example
when installing R packages.

#### macOS

[Video Tutorial](https://www.youtube.com/watch?v=5-ly3kyxwEg)

Install R by downloading and running
[this](https://cran.r-project.org/bin/macosx/R-latest.pkg) .pkg file from
[CRAN](https://cran.r-project.org/index.html).  Also, please install the
[RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download).

#### Linux

You can download the binary files for your distribution from
[CRAN](https://cran.r-project.org/index.html). Or you can use your package
manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora
run `sudo dnf install R`).  Also, please install the [RStudio
IDE](https://www.rstudio.com/products/rstudio/download/#download).

### Getting around in R and RStudio

We will base our R/RStudio lessons on the Data Carpentry [Data Analysis and
Visualization in R for Ecologists](https://datacarpentry.org/R-ecology-lesson/)
lessons. Take a look at the main page and the [Before we
start](https://datacarpentry.org/R-ecology-lesson/00-before-we-start.html)
section.

### Notes

The `??` for getting help in RStudio did not seem to work. Turns out, there is
probably a bug in the current version, as discussed at
[stackoverflow](https://stackoverflow.com/questions/57623417/double-question-mark-help-search-not-working-in-rstudio-and-rstudio-only).

## Week 2 - 11<sup>th</sup> of September - Endre Sebestyén

*Data organization and cleanup, structuring projects, tidy data*

[Presentation]({{ site.url }}/assets/phd_course/eloadas_2019-09-11.pdf)

Delivery plan:

- Recap of basic organizational stuff for newcomers
- Short introduction from everybody
- Checking R, RStudio, LibreOffice/Excel setup
- Discussing data organization in spreadsheets
- Recommended readings
- Homework explanation

### Data organization in spreadsheets

Before diving into the details of R and RStudio, we will discuss data
organization in spreadsheets. Most researchers use spreadsheets to collect data,
and this is the start of every analysis. However, computers need data to be
organized in a particular way. They can't recognize typos, colored excel lines
and other things that are easy to interpret and/or correct by humans.

We will use the Data Carpentry lesson titled [Data Organization in Spreadsheets
for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/) to learn
about these things.

- [Setup](https://datacarpentry.org/spreadsheet-ecology-lesson//setup.html) for
  data download that we will use for this lesson, and software installation
  instructions, if you don't have spreadsheet software installed.
- [Introduction](https://datacarpentry.org/spreadsheet-ecology-lesson/00-intro/index.html) and
  [data formatting](https://datacarpentry.org/spreadsheet-ecology-lesson/01-format-data/index.html)
- [Common formatting problems](https://datacarpentry.org/spreadsheet-ecology-lesson/02-common-mistakes/index.html)
- [Dates as data](https://datacarpentry.org/spreadsheet-ecology-lesson/03-dates-as-data/index.html)
- [Quality control](https://datacarpentry.org/spreadsheet-ecology-lesson/04-quality-control/index.html)
- [Exporting data](https://datacarpentry.org/spreadsheet-ecology-lesson/05-exporting-data/index.html)

You will need some kind of spreadsheet software for this, like Microsoft Excel
or LibreOffice. To setup LibreOffice, check the details
[here](https://datacarpentry.org/spreadsheet-ecology-lesson//setup.html).

### Recommended readings

These are some of the papers that describe basic data organization principles,
how to manage projects, etc.

- Tidy Data [10.18637/jss.v059.i10](http://dx.doi.org/10.18637/jss.v059.i10):
  how to organize your data in a clean, easy to handle way.
- A quick guide to organizing computational biology projects
  [10.1371/journal.pcbi.1000424](http://dx.doi.org/10.1371/journal.pcbi.1000424):
  how to organize any project, not just computational biology projects. Anyway,
  [all biology is computational
  biology](http://dx.doi.org/10.1371/journal.pbio.2002050), right?
- Good enough practices in scientific computing
  [10.1371/journal.pcbi.1005510](http://dx.doi.org/10.1371/journal.pcbi.1005510):
  a set of good computing practices, that every researcher can adopt, regardless
  of current level of computational skills.
- Best Practices for Scientific Computing
  [10.1371/journal.pbio.1001745](http://dx.doi.org/10.1371/journal.pbio.1001745):
  a more detailed explanation on how to organize stuff, write code, plan your
  project, collaborate and so on.
- Nine simple ways to make it easier to (re)use your data
  [10.7287/peerj.preprints.7v2](https://doi.org/10.7287/peerj.preprints.7v2).
  Another set of recommendations on how to make data understandable and
  reusable.
- Gene name errors are widespread in the scientific literature
  [10.1186/s13059-016-1044-7](http://dx.doi.org/10.1186/s13059-016-1044-7): a
  tale about gene names, dates and Excel.

### Homework

*Send an email from the address you would like to use for getting the
homework submission link.* Homework deadline is 24:00, 15<sup>th</sup> of
September. We will discuss them next week.

Think about what we learned today about organizing data in spreadsheets, tidy
data and your own project, datasets and analysis plans. Keeping all of this in
mind, *create a single spreadsheet* showing how you would organize your
experimental data. Add columns as needed, and include a few rows with example
data. You can also add some explanations or comments in the table.

What kind of data will you collect? Clinical information, gene expression
values, genetic information, something else? Is it categorical or continuous?
How many observations, patients or experiments are you planning? Are you
planning to do multiple measurements on the same sample? Is it important to
record experimental setup, machine parameters? What happens if you have missing
data, for example no clinical information, or the experiment failed for a
certain sample?

### Notes

It's ÉV, HÓNAP and NAP (as in hungarian) for the YEAR, MONTH and DAY functions
of Excel, in the hungarian version. One more reason not to use Excel for
anything.

## Week 3 - 18<sup>th</sup> of September - Endre Sebestyén

*Intro to R I: variables, vectors, lists, functions*

Delivery plan:

- Recap of data organization
- Short summary of homeworks
- Discussing homework example data in groups
- Intro to R I.
- Recommended readings
- Homework explanation

### Intro to R I.

During this lesson we will learn what is an R object, variable, function, etc, how to
assign values to objects, comment things, use functions and manipulate vectors.
We will also take a short look at lists.

We will use the Data Carpentry lesson titled [Data Analysis and Visualization in
R for Ecologists](https://datacarpentry.org/R-ecology-lesson/).

- [Introduction to R](https://datacarpentry.org/R-ecology-lesson/01-intro-to-r.html)
  up to the Vectors and data types challenge.

### Recommended readings

- [Advanced R - Style guide](http://adv-r.had.co.nz/Style.html): how to format
  your code. This seems to be an unimportant and trivial thing, but will make
  your work more user friendly, reusable, and easier to understand. Also think
  of your future self, who will need to understand the old analysis, 10 months
  from now.
- [Advanced R - Vocabulary](http://adv-r.had.co.nz/Vocabulary.html): an extended
  list of useful functions. No need to go through everything right now, as you
  just started learning R, but it will come handy later.
- [Programming with R](http://swcarpentry.github.io/r-novice-inflammation/): an
  alternative introduction to R.

### Homework

Homework deadline is 24:00, 22<sup>nd</sup> of September. We will discuss them next week.

Take a look around in R, pick some functions, like the `mean`, `sd`, `max`,
`sum` or others. Open your spreadsheet from homework 1, select a group of
measurements, define it as a vector in R, and get the result of the various
functions. Define at least 3 different vectors with different data, and use at
least 3 functions. Save your code in a file, add comments to explain what you
did and also add the output (or the error messages) of the functions as
comments. Do NOT import the excel table into R using other functions and
packages.  Please define the measurement vectors by typing, so you practice R
syntax.

## Week 4 - 25<sup>th</sup> of September - Endre Sebestyén

*Intro to R II: subsetting and missing data*

Delivery plan:

- Recap of R vectors and functions
- Short intro to lists
- Short summary of homeworks
- Homework discussion in groups
- Intro to R II.
- Recommended readings
- Feedback
- Homework explanation

### Intro to R II.

During the lesson we will discuss subsetting vectors in different ways and
dealing with missing data in vectors.

We will use the Data Carpentry lesson [Data Analysis and Visualization in R
for Ecologists](https://datacarpentry.org/R-ecology-lesson/).

- [Introduction to R](https://datacarpentry.org/R-ecology-lesson/01-intro-to-r.html)
  until the end, starting from the Subsetting vectors section.

### Recommended readings

- [Advanced R - Subsetting](http://adv-r.had.co.nz/Subsetting.html): Everything
  you wanted to know about vector subsetting and much more.
- [CRAN Task View: Missing
  Data](https://cran.r-project.org/web/views/MissingData.html): Dealing with,
  exploring and imputing missing data. We will discuss CRAN in more detail
  later.

### Homework

Homework deadline is 24:00, 29<sup>th</sup> of September. We will discuss them next week.

Open your script from the previous week, improve it as discussed (if needed),
and define a new vector with experimental measurements. However, include missing
data in the new vector. Go over your previous functions that you used in the
script, determine how to deal with missing values, and calculate all previous
results for this new vector as well. Send the improved analysis script.

## Week 5 - 2<sup>nd</sup> of October - Endre Sebestyén

*Intro to R III: reading in and writing out data, factors, data frames*

Delivery plan:

- Recap of R subsetting and missing values
- Short summary of homeworks
- Homework discussion in groups
- Intro to R III.
- Recommended readings
- Homework explanation

### Intro to R III.

During the lesson we will discuss how to import data into R from external
sources, what a data.frame is, and how to use factors.

We will use the Data Carpentry lesson [Data Analysis and Visualization in R
for Ecologists](https://datacarpentry.org/R-ecology-lesson/).

- [Starting with data](https://datacarpentry.org/R-ecology-lesson/01-intro-to-r.html)
  until the Formatting Dates part.

### Recommended readings

- Importing data files with the readr package, from the [R for Data
  Science](https://r4ds.had.co.nz/data-import.html) book.
- R documentation on [data import/export](https://cran.r-project.org/doc/manuals/r-release/R-data.html).
- The [rio package](https://github.com/leeper/rio) for importing/exporting a
  huge range of data formats.

### Homework

Homework deadline is 24:00, 6<sup>th</sup> of October. We will discuss them next week.

Take your final excel dataset from the first lessons, export it as a csv file,
and read it into R with the function(s) discussed today. Run the `head`, `tail`,
`summary`, `nrow`, `ncol` and `str` functions on it. Save the code and the
results as an R script and send it. Write down possible errors, formatting
problems, and their possible sources so we can discuss them next week.

## Week 6 - 9<sup>th</sup> of October - Endre Sebestyén

*Intro to R IV: CRAN and Bioconductor, using dplyr*

Delivery plan:

- Recap of R factors, data.frames, and functions used
- Short summary of homeworks
- Short discussion of stringsAsFactors
- Homework discussion in groups
- Short intro to CRAN and Bioconductor
- Intro to R IV.
- Recommended readings
- Homework explanation

### Intro to R IV.

During the lesson we will learn how to manipulate and analyze data with the
dplyr package, learn about long and wide data formats, and use the
split-apply-combine concept for analysis.

We will use the Data Carpentry lesson [Data Analysis and Visualization in R
for Ecologists](https://datacarpentry.org/R-ecology-lesson/).

- [Manipulating data](https://datacarpentry.org/R-ecology-lesson/03-dplyr.html),
  where we might skip the *Reshaping with gather and spread* part, considering 
  progress and questions.

### Recommended readings

- [Bioconductor: open software development for computational biology and
  bioinformatics](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-10-r80)
- [Managing, installing, updating CRAN
  packages](https://cran.r-project.org/doc/manuals/r-release/R-admin.html#Add_002don-packages)
- Might want to refresh your ideas about tidy data
  [10.18637/jss.v059.i10](http://dx.doi.org/10.18637/jss.v059.i10).

### Homework

Homework deadline is 24:00, 13<sup>th</sup> of October. We will discuss them next week.

Take your csv file from last time (or a similar dataset from a paper or public
repository if you are getting bored with it), and read it into R with the
`tidyverse` based functiondiscussed today. Run the `head`, `tail`, and `str`
functions on it. Select and filter a specific subset with `select` and `filter`,
create a few new columns with `mutate`, group them according to your
experimental design with `group_by` (perhaps using mutation status, treatment,
or similar grouping), and calculate some informative statistics, like `mean`,
`median`, `min`, `max`, etc using `summarize`.  Save the code and the results as
an R script and send it. Write down possible errors, formatting problems, and
their possible sources so we can discuss them next week.

Please keep in mind what we discussed about formatting your code, adding
comments, adding the output of functions as comments, and NOT adding the `>`
character at the start of lines in a script. It might be useful checking out the
[tidyverse style guide](https://style.tidyverse.org/).

## Week 7 - 16<sup>th</sup> of October - Endre Sebestyén

*Intro to R V: using dplyr and the split-apply-combine data analysis strategy*

Delivery plan:

- Recap of dplyr
- Recap of structuring projects
- Short summary of homeworks
- Intro to R V.
- Recommended readings
- Homework explanation

### Intro to R V.

During the lesson we will continue with the dplyr package, learn about long and
wide data formats using the gather and spread functions, and use the
split-apply-combine concept and the summarize and group\_by functions for
analysis. We will also export the results with the write\_csv function.

We will use the Data Carpentry lesson [Data Analysis and Visualization in R
for Ecologists](https://datacarpentry.org/R-ecology-lesson/).

- [Manipulating data](https://datacarpentry.org/R-ecology-lesson/03-dplyr.html)
  lesson until the end.

### Recommended readings

- [Chapter 3 - Data Wrangling](https://moderndive.com/3-wrangling.html) from the
  book Statistical Inference via Data Science: A ModernDive into R and the
  tidyverse by Chester Ismay and Albert Y. Kim.
- Check out the full [R for Data Science](https://r4ds.had.co.nz/) book, if you
  haven't done it yet.

### Homework

Homework deadline is 24:00, 20<sup>th</sup> of October. We will discuss them next time.

Please check out the [last
challenge](https://datacarpentry.org/R-ecology-lesson/03-dplyr.html#challenge18)
from the [Manipulating
data](https://datacarpentry.org/R-ecology-lesson/03-dplyr.html) lesson, write
down your solutions as an R script, export the result tables, after taking a
look at the [Exporting
data](https://datacarpentry.org/R-ecology-lesson/03-dplyr.html#exporting_data)
section, and send the R script with the exported tables.  Write a *fully
reproducible* script, including data download, import, manipulating the data as
needed, and export. Don't forget about the `library` function at the start,
and what we discussed about comments, the length of lines, or stray `>` and `+`
characters at the start of lines.

The ideal R script [example](https://gist.github.com/esebesty/e7b15e66f3b1e6ce7ba992f0f3dfff6d).

## Week 8 - 30<sup>th</sup> of October - Endre Sebestyén

*R graphics: data visualization with ggplot2*

*Recap of R and RStudio, Q & A session*

Delivery plan:

- Recap of R until now
- R graphics: data visualization with ggplot2
- Q & A
- Recommended readings
- Homework explanation

### R graphics

We will use the Data Carpentry lesson [Data Analysis and Visualization in R
for Ecologists](https://datacarpentry.org/R-ecology-lesson/) to learn about the
basics of the ggplot2 package, produce different types of simple and more
complex plots.

- [Data visualization with ggplot2](https://datacarpentry.org/R-ecology-lesson/04-visualization-ggplot2.html).

### Recommended readings

- [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/)
- [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/)

### Homework

Homework deadline is 24:00, 3<sup>rd</sup> of November. We will discuss them later.

Import your real or made-up experimental data that you worked on during previous
homeworks, and create a plot using the `ggplot2` package. Send the R script and
the final plot. Take a look at [this
example](https://gist.github.com/esebesty/e7b15e66f3b1e6ce7ba992f0f3dfff6d)
before sending the script.

## Week 9 - 6<sup>th</sup> of November - Miklós Cserző

*The Linux/UNIX operating systems and the command line*

*Command line I: file system, creating, deleting, editing and looking at files*

Delivery plan

- The Linux operating system
- Linux command line I
- Recommended readings
- Homework explanation

### Linux and the command line

We will use the Software Carpentry lesson [The Unix
Shell](http://swcarpentry.github.io/shell-novice/) to learn about automating
repetitive tasks, combine existing tools and so on. This will be very useful in
high-performance computing environments.

- [The Unix Shell](http://swcarpentry.github.io/shell-novice/) until the end of
  [Working With Files and Directories](http://swcarpentry.github.io/shell-novice/03-create/index.html).

### Recommended readings

- Right now we are using a Windows based command line, but on the long term, you
  will most likely run into UNIX/Linux systems, like
  [Ubuntu](https://ubuntu.com/)
- Check out the [Linux man pages](https://linux.die.net/man/)
- [The Linux command line for beginners](https://tutorials.ubuntu.com/tutorial/command-line-for-beginners#0)

### Homework

Practice the material using the Software Carpentry lesson on the Unix shell.

## Week 10 - 13<sup>th</sup> of November - Endre Sebestyén

*Command line II: manipulating, filtering, rearranging files*

Delivery plan

- Recap of previous week
- Linux command line II
- Recommended readings
- Homework explanation

### Linux and the command line

We will continue using the Software Carpentry lesson [The Unix
Shell](http://swcarpentry.github.io/shell-novice/) to learn about automating
repetitive tasks, combine existing tools and so on.

- [The Unix Shell](http://swcarpentry.github.io/shell-novice/) until the end of
  [Pipes and
  Filters](http://swcarpentry.github.io/shell-novice/04-pipefilter/index.html).

### Recommended readings

- Same as last week.

### Homework

Homework deadline is 24:00, 18<sup>th</sup> of November. We will discuss them
next time.

Save the Pipe Construction exercise solution to a file, using nano and include
some explanation using comments (`#`). Include *all* necessary commands, after
opening Git Bash!

## Week 11 - 20<sup>th</sup> of November - Endre Sebestyén

*Command line III: manipulating, filtering, rearranging files*

Delivery plan

- Recap of previous week
- Linux command line III
- Recommended readings
- Homework explanation

### Linux and the command line

We will continue using the Software Carpentry lesson [The Unix
Shell](http://swcarpentry.github.io/shell-novice/) to learn about automating
repetitive tasks, combine existing tools and so on.

- [The Unix Shell](http://swcarpentry.github.io/shell-novice/) until the end of
  [Shell Scripts](http://swcarpentry.github.io/shell-novice/06-script/index.html).

### Recommended readings

- Same as last week.

### Homework

Homework deadline is 24:00, 24<sup>th</sup> of November. We will discuss them
next time.

Polish and change your script from last week as discussed!

The ideal shell script [example](https://gist.github.com/esebesty/0d9550bd0b6bc7941c6b0c6e0e91232e).

## Week 12 - 27<sup>th</sup> of November - Bence Szalai

*Intro to python I: basic syntax, Jupyter development environment*

## Week 13 - 4<sup>th</sup> of December - Bence Szalai

*Intro to python II: variable types*

## Week 14 - 11<sup>th</sup> of December - Gábor Turu

*Intro to python III: conditional statements, loops, functions*
