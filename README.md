# Quantitative Biodiversity (BIOL Z620)

Biodiversity refers to the variation among life and extends from within populations to across species and entire ecosystems. Due to one of the most rapid rates of extinction in history, the world is currently facing a biodiversity crisis. Consequently, it is imperative that we have an understanding of biodiversity and how to characterize and quantify it.

[Student Portal](https://github.iu.edu/2015-QuantitativeBiodiversity/)
[Assignments](http://documentup.com/QuantitativeBiodiversity/QuantitativeBiodiversity)<br>

## Course Syllabus (Spring 2015)

### Course summary
This course will introduce students to the concepts, patterns, metrics, and tools that are common to the study of biodiversity. Each class meeting will consist of a short lecture followed by computational exercises designed to analyze aspects of biodiversity using data from tree, bird, mammal, bacterial, archaeal, and fungal systems. Students will learn how to calculate diversity metrics, generate and quantify diversity relationships, visualize multivariate data, and test hypotheses with an array of statistical techniques. Because biodiversity extends to the genetic level, students will also learn to map traits to phylogenies using gene sequence data. Students will be introduced to modern statistical computing and graphics environments, as well as the version control tools Git and GitHub.

### Instructor
Dr. Jay Lennon<br>
261B Jordan Hall (office)<br>
812-856-0962 (office phone)<br>
[lennonj@indiana.edu](mailto:lennonj@indiana.edu?Subject=Quantitative%20Biodiversity)<br>

### Class meetings
9:30-12:00 Friday, Public Health (PH) 155

### Recommended Textbooks 
* Measuring Biological Diversity, Anne E. Magurran (2003). *(on reserve in Life Science Library)*
* Numerical Ecology, Legendre and Legendre (2008)
* Introductory Statistics with R, Dalgard (2008) - ([available online](http://link.springer.com/book/10.1007/978-0-387-79054-1))
* Numerical Ecology with R, Borcard, Gillet, & Legendre (2011) – ([available online](http://link.springer.com/book/10.1007/978-1-4419-7976-6))
* Functional and Phylogenetic Ecology in R, Swenson (2014) - ([available online](http://link.springer.com/book/10.1007/978-1-4614-9542-0))

### Git and Github
Git is a version control system that allows users to track, record, and recover all changes throughout the history of any project. GitHub is a professional web-based service that allows users to store and work from a master copy of their work in a stable cloud environment that is safer than personal computers and lab hard drives. GitHub is also the premier tool for collaborative and social development of computing-based projects, allowing instructors, students, and collaborators to develop a project (or class) from remote locations and to easily follow the entire history. We will use Indiana University’s GitHub (https://github.iu.edu/) to host for course material including lecture slides, required readings, syllabus, schedule, and material relevant to other course activities. Each student will have their own private GitHub repository and will use Git and GitHub to store and submit their work.

### Learning Objectives
**Quantitative Biodiversity is organized around the following learning objectives**<br>
&nbsp;&nbsp;***Upon completion of the course, students will be able to:***<br>
&nbsp;&nbsp;&nbsp;&nbsp;1. Identify and discuss core concepts of biodiversity<br>
&nbsp;&nbsp;&nbsp;&nbsp;2. Quantify and compare measures of taxonomic diversity within and among samples<br>
&nbsp;&nbsp;&nbsp;&nbsp;3. Quantify the distribution of traits and species in a phylogenetic context<br>
&nbsp;&nbsp;&nbsp;&nbsp;4. Use cutting-edge computational tools for analyzing biodiversity data<br>
&nbsp;&nbsp;&nbsp;&nbsp;5. Use cutting-edge version control tools for the management of research projects<br>

### Student Assessment
* **Assignments:** Students will be assigned in-class exercises, which will have problem sets that need to be submitted via GitHub.
* **Reading:** Students will be expected to read assigned papers from the primary literature prior to class meetings. Students will submit brief reviews of each paper via GitHub.
* **Participation:** Students will need to attend and actively engage in each discussion and computational exercise.

### Academic Integrity
As a student at IU, you are expected to adhere to the standards and policies detailed in the [Code of Student Rights, Responsibilities, and Conduct](http://www.iu.edu/~code/). When you submit an assignment with your name on it in this course, you are signifying that the work contained therein is all yours, unless otherwise cited or referenced. Similar standards are assumed for presentations and the generation of web-based media. Any ideas or materials taken from another source for either written or oral use must be fully acknowledged. If you are unsure about the expectations for completing an assignment, be sure to seek clarification beforehand. All suspected violations of the Code will be handled according to University policies. Sanctions for academic misconduct may include a failing grade on the assignment, reduction in your final grade, a failing grade in the course, among other possibilities, and must include a report to the Dean of Students.

### Attendance
Given the small number of class meetings, absences are strongly discouraged. Any conflicts should be communicated to the instructor as early as possible.

### Special needs
Please contact me as soon as possible (first two weeks of the semester) if you have a documented disability that will interfere your performance of the activities planned for the course.

## Schedule

### Week 1
**Lecture:** ***Introduction to Biodiversity***<br>

What it is and why we study it. Provide an overview of alpha, beta, and gamma diversity (part 1 of course). Provide an overview of phylogenetic diversity (part 2 of course). Segue into the need for a quantitative approach. Introduce class to the quantitative tools that we are going to use to study biodiversity.

**Lab:** ***The Computer Environment: Github and Basic R***<br>

1. Getting set up in Git. Creating accounts. Exercises that might include:<br>
&nbsp;&nbsp;&nbsp;&nbsp;A. Creating a repository<br>
&nbsp;&nbsp;&nbsp;&nbsp;B. Forking a repository<br>
&nbsp;&nbsp;&nbsp;&nbsp;C. Pushing changes<br>
&nbsp;&nbsp;&nbsp;&nbsp;D. Creating a pull request<br>
&nbsp;&nbsp;&nbsp;&nbsp;E. Merging a pull request<br>

2. Getting set up in R. Exercises that might include:<br>
&nbsp;&nbsp;&nbsp;&nbsp;A. Presumably R studio will already be installed<br>
&nbsp;&nbsp;&nbsp;&nbsp;B. A walk through R studio layout (windows: Console, Editor, Workspace/History, Files/Plots/Packages/Help)<br>
&nbsp;&nbsp;&nbsp;&nbsp;C. Data structures: vectors, matrices, and data frames.<br>
&nbsp;&nbsp;&nbsp;&nbsp;D. Importing data<br>
&nbsp;&nbsp;&nbsp;&nbsp;E. Other data types? (dates, characters, etc.)<br>
&nbsp;&nbsp;&nbsp;&nbsp;F. Data manipulations<br>
&nbsp;&nbsp;&nbsp;&nbsp;G. R Functions and arguments<br>
&nbsp;&nbsp;&nbsp;&nbsp;H. Programming tools<br>
&nbsp;&nbsp;&nbsp;&nbsp;I. Basic plotting<br>

3. ***Homework:*** need ideas; ones that will rely on R and GitHub. **Create a plot from data.**

### Week 2
**Lecture:** ***Diversity Within a Sample***<br>

Primary components of diversity: richness and evenness. With this information we can think about species abundance distributions (SAD) and associated topics such as dominance and rarity. Discuss the theoretical and practical applications of these concepts. Also, introduce diversity metrics along with their positives and negatives. 

**Lab:** ***Alpha Diversity***<br>

1. Plotting SADs. What can we tell from them? Which underlying models fit the data best (AIC)? What can we infer from these models?

2. Estimate richness (collectors curves, rarefaction, and error)

3. Estimate evenness (compare metrics that are biased and unbiased by S)

4. ***Homework:*** Compare and contrast diversity estimators for a real-world dataset and make some conclusions. Basically repeat this paper: http://www.ncbi.nlm.nih.gov/pubmed/18637951

### Week 3
**Lecture:** ***Diversity Among Samples***<br>

Space and time. Importance of scale, etc.

**Lab:** ***Beta Diversity***<br>

1. introduce sample x species matrix

2. introduction to similarity metrics; pres-abs vs. rel abund; Jaccard Bray-Curtis, Sorenson. 

3. Visualization techniques: clustering and ordination

4. Explore how similarity metrics influence visual and quantitative estimates of beta diversity

5. Hypothesis testing approaches with multivariate data. 


### Week 4 
**Lecture:** ***Biogeography***<br>



**Lab:** ***Biogeographic Patterns: distance decay, SAR,...***<br>

1. Nested SAR

2. Island SAR 

3. Model fittings and interpretation

4. Exercise: BCI would be great for this


### Week 5
**Lecture:** ***Recap/Exercises/More R***<br>

***Group Projects***

**Lab:** ***More to Come***<br>

1. 

### Week 6
**Lecture:** ***Introduction to Phylogenetic Diversity***<br>



**Lab:** ***Phylogenetic Tree Building***<br>

1. Visualize and align sequences<br>

2. Making trees: neighbor joining, maximum likelihood, etc.

3. Comparisons

4. Homework: Make your own tree


**Resources:**<br>
[http://www.r-phylo.org/wiki/Main_Page](http://www.r-phylo.org/wiki/Main_Page)<br>
[http://www.springer.com/life+sciences/evolutionary+%26+developmental+biology/book/978-1-4614-1742-2](http://www.springer.com/life+sciences/evolutionary+%26+developmental+biology/book/978-1-4614-1742-2)<br>
[http://bodegaphylo.wikispot.org/R_Tutorial_%28Glor_%26_O%27Meara%29](http://bodegaphylo.wikispot.org/R_Tutorial_%28Glor_%26_O%27Meara%29)<br>
[http://blog.phytools.org](http://blog.phytools.org)<br>

### Week 7
**Lecture:** ***Phylogenetic Traits***<br>

Traits and Signals

**Lab:** ***Traits and Signals***<br>

1. 


### Week 8
**Lecture:** ***Phylogenetic Community Ecology***<br>



**Lab:** ***Community Phylogenetics***<br>

1. Analyzing community data in a phylogenetic context: unifrac

2. Mapping traits onto a phylogeney (Picante package in R)

3. Other phylogenetic community ecology methods



**Other ideas to fill in the gaps:**<br>
1. more explicit handling of spatial ecology? exercises?<br>
2. Individual based models? to address....what particular questions?<br>
3. Data Viz<br>