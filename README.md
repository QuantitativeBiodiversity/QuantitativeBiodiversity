# BIOL Z620 - Quantitative Biodiversity

## Course Syllabus (Spring 2015)

Biodiversity refers to the variation among life and extends from within populations to across species and entire ecosystems. Due to one of the most rapid rates of extinction in history, the world is currently facing a biodiversity crisis. Consequently, it is imperative that we have an understanding of biodiversity and how to characterize and quantify it.

### Course summary
This course will introduce students to the concepts, patterns, metrics, and tools that are common to the study of biodiversity. Each class meeting will consist of a short lecture followed by computational exercises designed to analyze aspects of biodiversity using data from tree, bird, mammal, bacterial, archaeal, and fungal systems. Students will learn how to calculate diversity metrics, generate and quantify diversity relationships, visualize multivariate data, and test hypotheses with an array of statistical techniques. Because biodiversity extends to the genetic level, students will also learn to map traits to phylogenies using gene sequence data. Students will be introduced to modern statistical computing and graphics environments, as well as the version control tools Git and GitHub.

### Instructor
Dr. Jay Lennon </br>
261B Jordan Hall (office) </br>
812-856-0962 (office phone) </br>
[lennonj@indiana.edu](mailto:lennonj@indiana.edu?Subject=Quantitative%20Biodiversity)</br>

### Class meetings
9:30-12:00 Friday, TBD  

### Recommended Textbooks (on reserve in Life Science Library)

* Measuring Biological Diversity, Anne E. Magurran (2003). 
* R books?
* Legendre and Legendre?

### Github
We will use Github for course material including lecture slides, required readings, syllabus, schedule, and material relevant to other course activities. 

### Student evaluation
* Assignments: Students will be assigned exercises in class, which will have problem sets that need to be pushed to Github for credit.  
* Reading: Students will be expected to read papers from the primary literature associated with each class meeting.
* Participation: Need to show up and participate in discussion and computer exericeses.

### Academic Integrity 
As a student at IU, you are expected to adhere to the standards and policies detailed in the Code of Student Rights, Responsibilities, and Conduct (http://www.iu.edu/~code/). When you submit a paper or exam with your name on it in this course, you are signifying that the work contained therein is all yours, unless otherwise cited or referenced. Similar standards are assumed for presentations and the generation of web-based media. Any ideas or materials taken from another source for either written or oral use must be fully acknowledged. If you are unsure about the expectations for completing an assignment or taking a test or exam, be sure to seek clarification beforehand. All suspected violations of the Code will be handled according to University policies. Sanctions for academic misconduct may include a failing grade on the assignment, reduction in your final grade, a failing grade in the course, among other possibilities, and must include a report to the Dean of Students.

### Attendance: 
I expect that enrolled students will be punctual and attend all classes. As a general rule, exams will not be rescheduled unless there is documentation of an illness or other emergency. These conflicts or other events should be communicated with the instructor as early as possible.

### Special needs: 
Please contact me as soon as possible (first two weeks of the semester) if you have a documented disability that will interfere your performance of the activities planned for the course.  
 
## Schedule

### Week 1 
**Lecture:** Introduction to the course (Github and R) </br>
**Lab:** Getting computer environment set up: Github and basic R </br>
- importing data sets
- basics of data structures and data manipulation
- basic plotting  

### Week 2
**Lecture:** Introduction to biodiversity: alpha diversity </br>
**Lab:** Alpha diversity </br>
- estimating richness, including rarefaction
- estimating evenness, compare and contrast
- other diversity estimators (Shannon, etc.)
- introduce functions, loops?, bootstrapping?  If not here, somewhere
- Exercise: use vegan (canned estimators), but also write functions for other estimators not found in vegan
- Exercise: compare and contrast diversity estimators for a real-world dataset and make some conclusions. Basically repeat this paper: http://www.ncbi.nlm.nih.gov/pubmed/18637951

### Week 3
**Lecture:** Introduction to biodiversity: species abundance distributions</br>
**Lab:** Species abundance distributions</br>
- SADs
- Model fitting (log series, lognormal, etc.)
- Exercise: BCI data?

### Week 4 
**Lecture:** Introduction to biodiversity: beta diversity</br>
**Lab:** Beta diversity</br>
- visualizing multivariate data; ordinations, etc. 
- Distance metrics (Euclidean, Bray, Sorenson, etc.). 
- Other more classical measures of measuring beta diversity
- Hypothesis testing: PERMANOVA
- Use a cool dataset? NEON? Have them download it? Show them how to get cool data. 

### Week 5
**Lecture:** Introduction to biodiversity: species area relationship? </br>
**Lab:** Species area relationship? </br>

### Week 6
*Lecture:* Introduction to biodiversity: phylogenetics
*Lab:* constructing a phylogeny

- Of course, there’s probably better ways to do this, but we can build trees in R
- Look at sequences
- Align sequences
- Tree files
- Making a tree: neighbor joining, maximum likelihood, etc. 
- Compare how different
- Get your own sequences…make a tree. Test a question?
- NOT MEANT to pretend to do what evolutionary biologists in dept do.  Demystify…for ecologists in a common (R) work environment. 

http://www.r-phylo.org/wiki/Main_Page
http://www.springer.com/life+sciences/evolutionary+%26+developmental+biology/book/978-1-4614-1742-2
http://bodegaphylo.wikispot.org/R_Tutorial_%28Glor_%26_O%27Meara%29
http://blog.phytools.org/


**Week 6:** 
*Lecture:* Introduction to biodiversity: phylogenetic community ecology
*Lab:* phylogenetic community ecology
- Analyzing community data in a phylogenetic context: unifrac
- Mapping traits onto a phylogeny (Picante package in R)
- Other phylogenetic community ecology methods in Picante 

**Other ideas to fill in gaps:**
- more explicit handling of spatial ecology? Exercises?
- Individual based models? To address….what particular questions?
- “Data visualization methods” 
- Starting to accumulate examples from other classes: see MoPad
