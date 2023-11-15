---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<h1>Introduction and objectives </h1>

This course is about designing algorithms for computational problems, and how to think clearly about analyzing correctness and running time. The main goal is to provide the intellectual tools needed for designing and analyzing your own algorithms for new problems you need to solve in the future.

The official plan of this course is hosted in FCUP [here](https://sigarra.up.pt/fcup/pt/ucurr_geral.ficha_uc_view?pv_ocorrencia_id=528072).

# Learning outcomes and competences

Students should be able to understand the relationship between algorithm design, correctness proof and complexity analysis. Students should learn algorithmic techniques of general applicability and get to know some major algorithms in a few common domains. They will also obtain practical experience in applying generic algorithms to specific problems.

# Syllabus

- Algorithm correctness
- Complexity: worst/best-case analysis
- Fundamentals of asymptotic analysis
- Average-case and randomized algorithms
- Recursive algorithms
- Amortized analysis
- Data structures - Collections and Graphs
<!-- - Graph traversals and Dynamic programming -->
- Fundamentals of NP-completeness

<!-- - Sorting algorithms (after rec. alg. -->


<!-- - Fundamentals of asymptotic analysis
- Divide and conquer design pattern and how to solve recurrences
- Amortized analysis
- Probabilistic analysis and randomized algorithms
- Linear sorting and selection algorithms
- Greedy and dynamic programming design patterns
- Fundamentals of NP-completeness
- Introduction to approximation algorithms and parameterized algorithms
- Applications and some classical algorithms (e.g. graph algorithms, string matching algorithms, geometric algorithms) 
-->

# Lectures

- __22 Sep 23__: Introduction ([1-intro.pdf](slides/1-intro.pdf)) and algorithm correctness: specifying problems logically ([2-correctness.pdf - pages 1-18](slides/2-correctness.pdf))
- __29 Sep 23__: Algorithm correctness: partial and complete correctness ([2-correctness.pdf - pages 13-36](slides/2-correctness.pdf)); motivation for performance analysis ([3-countingsteps.pdf - pages 1-29](slides/3-countingsteps.pdf))
- __6 Oct 23__: Algorithms complexity: best and worst case analysis. Counting steps and asymptotic notation ([3-countingsteps.pdf - pages 23-63](slides/3-countingsteps.pdf))
- __13 Oct 23__: Exercises with asymptotic notation ([3-countingsteps.pdf - pages 64-66](slides/3-countingsteps.pdf)); Time complexity of recursive algorithms ([3-countingsteps.pdf - pages 67-95](slides/3-countingsteps.pdf))
- __20 Oct 23__: Exercises on the time complexity of recursive algorithms and the master theorem ([3-countingsteps.pdf - pages 96-112](slides/3-countingsteps.pdf)); Average time complexity ([4-average-time.pdf - pages 1-19](slides/4-average-time.pdf))
- __27 Oct 23__: Average time complexity and analysis of the quicksort algorithm ([4-average-time.pdf - pages 20-32](slides/4-average-time.pdf)); Randomised algorithms ([4-average-time.pdf - pages 33-40](slides/4-average-time.pdf)); Amortised analysis and the aggregate method ([5-amortised.pdf - pages 1-11](slides/5-amortised.pdf))
- __10 Nov 23__: Test (30%): 9h30-10h30 (Specification, Correction, Worst/Best time analysis, Asymptotic analysis); Rest of the lesson starts at 11h15 - Amortised analysis ([5-amortised.pdf - pages 11-26](slides/5-amortised.pdf))
- __17 Nov 23__: Amortised analysis ([5-amortised.pdf - pages 27-44](slides/5-amortised.pdf)); Data structures: sequences and buffers ([6-data-structures.pdf](slides/6-data-structures.pdf))
- __24 Nov 23__: tbd
- __1 Dec 23__: _Holiday_
- __8 Dec 23__: _Holiday_
- __15 Dec 23__: Test (70%): 9h30-11h30 (all topics); no lesson after the test



# Literature and Material

### Slides
1. [Introduction to the course](slides/1-intro.pdf)
2. [Algorithm correctness](slides/2-correctness.pdf)
3. [Counting steps and asymptotic notation](slides/3-countingsteps.pdf)
4. [Average-time and probabilistic algorithms](slides/4-average-time.pdf)
5. [Amortised analysis](slides/5-amortised.pdf)
6. [Data structures](slides/6-data-structures.pdf)

### Main book

- [Introduction to algorithms](http://catalogo.up.pt/F/-?func=find-b&local_base=FCUP&find_code=SYS&request=000287411), _Cormen Thomas H. et al._; ISBN: 9780262033848

### Previous years

- Slides from [Pedro Ribeiro](https://www.dcc.fc.up.pt/~pribeiro/) (2018/19): [https://www.dcc.fc.up.pt/~pribeiro/aulas/alg1819/material.html#slides](https://www.dcc.fc.up.pt/~pribeiro/aulas/alg1819/material.html#slides)
- Content from [Ana Paula Tomás]() (2021/22): [https://www.dcc.fc.up.pt/~apt/Aulas/ALGO2223.html](https://www.dcc.fc.up.pt/~apt/Aulas/ALGO2223.html)
- Slides from similar courses:
  + By [E. Demaine, C.E. Leiserson, MIT, 2001](http://www.cs.virginia.edu/~robins/cs6161/slides/Cormen_Algorithms_Slides.pdf) (companion of the main book - [more on the course](https://dspace.mit.edu/bitstream/handle/1721.1/36847/6-046JFall-2001/OcwWeb/Electrical-Engineering-and-Computer-Science/6-046JIntroduction-to-AlgorithmsFall2001/CourseHome/index.htm))
  + By [Skiena, Stony Brook University, 2012](https://www3.cs.stonybrook.edu/~algorith/video-lectures/)
  + By [J. Barros, J.S. Pinto et. al, U. Minho (2022/23)](https://www4.di.uminho.pt/~jno/sitedi/uc_J303N6.html) (no content online)
  
<!-- also companion slides, structured by lecture:
  https://dspace.mit.edu/bitstream/handle/1721.1/36847/6-046JFall-2001/OcwWeb/Electrical-Engineering-and-Computer-Science/6-046JIntroduction-to-AlgorithmsFall2001/LectureNotes/index.htm -->

### Complementary Bibliography

- [The algorithm design manual;](https://www.algorist.com) _Skiena Steven S._;  ISBN: 978-1-84800-069-8
- [Competitive Programming 3: The New Lower Bound of Programming Contests](https://sites.google.com/site/stevenhalim/); Steven Halim and Felix Halim; 2023
- [Algorithms](http://catalogo.up.pt/F/-?func=find-b&local_base=FCUP&find_code=SYS&request=000237593); _Sedgewick Robert_; ISBN: 0-201-06673-4
- [Algorithm Design](http://www.cs.princeton.edu/~wayne/kleinberg-tardos/); _Jon Kleinberg and Éva Tardos;_ 2005. ISBN: 978-0321295354
- [Tópicos Avançados em Algoritmos](http://www.dcc.fc.up.pt/~acm/aulas/aa/t1.pdf); _Armando Matos;_ DCC/FCUP, 2008 (In Portuguese - some lecture notes)
- [Desenho e Análise de Algoritmos – Alguns Apontamentos](http://www.dcc.fc.up.pt/~apt/aulas/DAA/1314/ApontamentosDAA.pdf); _Ana Paula Tomás;_ DCC/FCUP, 2013

# Teaching methods and learning activities

Lectures; intermediate test (mandatory) and final test  or final exam.

The lectures mix the presentation of new material (introducing concepts, main algorithms and some results) with interactive discussion of their application when solving real problems.

The homework focus is on practical application of algorithmic concepts, consolidating the learned material. 

The final exam and intermediate tests (closed book), globally evaluates the knowledge acquired by the students.

# Evaluation Type

Distributed evaluation with final exam

### Assessment Components

|designation | Weight (%)|
|------------|-----------|
|Exam |70,00|
|Test | 30,00|


### Amount of time allocated to each course unit

|designation | Time (hours)|
|------------|-------------|
|Home study | 120,00|
|Attendance time | 42,00|
|**Total:** | 162,00|


# Eligibility for exams

All students will be admitted to the exams.


# Calculation formula of final grade

 - __(IT)__ intermediate mid-term test (mandatory) 30%
   + __10 Nov__, during the lecture time.

 - __(FE)__ final exam: 70% (can be replaced by IT2)

 - __(IT2)__ improvement test: can replace the final exam. Required IT2 >= 8.


1st Exam ("Normal") classification: C = max(FE,IT2)*0.7+ IT*0.3 >= 9.5

2nd Exam ("Recurso") classification: C = max(FE*0.7+IT*0.3, FE) >= 9.5

Required FE >=8.


<!--
# Classification improvement

By final exam.
-->
   

# Contact

The day and time for _appointments_ is Friday afternoon ([José Proença](https://jose.proenca.org)). Please
email me the day before if you wish to meet. If you prefer you
can also just send an email with your questions to [José Proença](mailto:jose.proenca@fc.up.pt), or we can try to book an online meeting[.](https://github.com/cister-labs/alg2324)
