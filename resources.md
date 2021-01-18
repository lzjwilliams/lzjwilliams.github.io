---
layout: post
title: Resources
permalink: /resources/
---
This is a list of resources, covering a range of topics, that I have either found useful during my PhD or would like to get around to. This is an ongoing project, and will _hopefully_ be updated regularly. Everything listed here is freely available - [_information not shared is information lost_](https://brainder.org/).

Of note: 
1. The resources are heavily biased towards those that are in a video format, which reflects how I prefer to learn.
2. Within each heading/sub-heading, resources are listed in terms of domain knowledge required (least to most) which is biased by educational background. Hopefully there is something for everyone, given your own background and interests.

I am always happy for feedback, suggestions or recommendations!

## Contents
--- 

1. [Medical Imaging](#medical-imaging)<br>
  a. [Neuroimaging](#neuroimaging)<br>

2. [Machine Learning](#machine-learning)<br>
  a. [Classic Machine Learning](#classic-machine-learning)<br>
  b. [Deep Learning](#deep-learning)<br>
  c. [Geometric Deep Learning](#geometric-deep-learning)<br>
  d. [Natural Language Processing](#natural-language-processing)<br>
  e. [Reinforcement Learning](#reinforcement-learning)<br>
  f. [Unsupervised Deep Learning](#unsupervised-deep-learning)<br>

3. [Mathematics](#mathematics)<br>
  a. [Linear Algebra](#linear-algebra)<br>
  b. [Calculus](#calculus)<br>
  c. [Probability & Statistics](#probability-&-statistics)<br>

4. [Population Genetics](#population-genetics)<br>
5. [Programming](#programming)<br>
6. [Causal Inference](#causal-inference)<br>


## Medical Imaging
---

|Link|Description|
|:---:|-----------|
| [MICCAI Medical Imaging Summer School 2018](https://www.youtube.com/playlist?list=PL_VeUGLULXQux1dV4iA3XuMX6AueJmGGa) [Videos] | [MICCAI](http://www.miccai.org/) is one of the biggest medical imaging conferences worldwide. They hold a summer school biennially, and all lectures are available on Youtube. Recordings for [2016](https://www.youtube.com/playlist?list=PL_VeUGLULXQtESfpvkzC_R9SWMxGe7j4_) and [2014](https://www.youtube.com/playlist?list=PL_VeUGLULXQtvcCdAgmvKoJ1k0Ajhz-Qu) are also online. |
| [Radiopaedia](https://radiopaedia.org) [Website] | "Radiopaedia is a rapidly growing open-edit educational radiology resource which has been primarily compiled by radiologists and radiology trainees from across the world." This is a great resource for visualisng radiological anatomy and pathology!  |


### Neuroimaging 

|Link|Description|
|:---:|-----------|
| [FSL Course 2020](https://fsl.fmrib.ox.ac.uk/fslcourse/online_materials.html) [Videos and Practicals] | This is the first year that the FSL course moved to an enitrely virtual format, and as a participant it was the perfect introduction to neuroimaging analysis. Topics include image pre-processing, structural, functional (task and resting-state) and diffusion MR analyses. |
| [Mumford Brain Stats](https://www.youtube.com/channel/UCZ7gF0zm35FwrFpDND6DWeA) | [Dr. Jeanette Mumford](https://www.ohbmbrainmappingblog.com/blog/ohbm-education-in-neuroimaging-award-2019-jeanette-mumford) has created a fantastic set of lectures dedicated to statistics in neuroimaging. These are definitely worth a look!| 
| [Radiology Cafe MRI Physics](https://www.radiologycafe.com/radiology-trainees/frcr-physics-notes/mr-imaging) [Notes] | An introduction to the physical properties underlying magnetic resonance imaging. Set at the level expected of radiology trainees for the [FRCR part 1](https://www.rcr.ac.uk/clinical-radiology/examinations/first-frcr-examination) examination.  |
| [Questions and Answers in MRI](https://www.mriquestions.com/index.html) [Notes] | A more comprehensive resource describing the physical properties of MRI. The Q&A format makes it a lot easier to navigate! Recommended reading for the King's College London [Medical Image Acquisition](https://www.kcl.ac.uk/lsm/research/divisions/imaging/study/beng-degree/study/medical-image-acquisition) course. |
| [MRI of the Neonatal Brain](http://www.mrineonatalbrain.com/) [Textbook] | A freely available textbook written by [Professor Mary Rutherford](https://scholar.google.com/citations?hl=en&user=8RVMsmEAAAAJ&view_op=list_works&sortby=pubdate), a world-expert in neonatal neuroimaging. This book describes typical perinatal neurodevelopment, and radiological changes that occurs during neonatal illness. |
| [Paediatric Neuroradiology](https://www.ismrm.org/online-education-program/neuro/#pediatrics) [Videos] | [ISMRM](https://www.ismrm.org) organises one of the biggest MRI conferences worldwide. They are in the process of curating their [MR Academy](https://www.ismrm.org/online-education-program/), which has a very comprehensive paediatric neuroradiology section covering a range of clinical disorders. |
| [Introduction to Imaging Genetics](https://www.pathlms.com/ohbm/courses/5158/sections/7790) [Videos] | [OHBM](https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=3267&pageid=1) hold educational courses around the time of their annual conference.  Their imaging genetics course has been running for several years, and is a good introduction to the area. The content of the educational courses in [2016](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/nichols/presentations/ohbm2016/imggen/) and [2014](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/nichols/presentations/ohbm2014/imggen) are slightly different but complementary.  |
| Brain Parcellation and Functional Territories [Videos] | An OHBM educational course that comes in several installments: parts [one](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137450), [two](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137466) and [three](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137467). Also available is a talk on [multi-modal parcellation](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/138055) by [Matt Glasser](https://scholar.google.com/citations?user=hqA9AugAAAAJ&hl=en) |
| Deep Learning for Human Brain Mapping [Videos] | An OHBM educational course that comes in several installments: parts [one](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/139629),  [two](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137440), [three](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137441) and [four](https://www.pathlms.com/ohbm/courses/12238/sections/15846/video_presentations/137444). See below for resources on machine learning/deep learning without a neuroimaging spin (MRI pun?) |
| [Magnetic Resonance Diffusion Imaging](https://www.pathlms.com/ohbm/courses/5158/sections/7777) [Videos] | An OHBM educational course that covers diffusion MRI acquisiton, diffusion modelling, tractography and more. |
| [Neuroimaging Meta-Analysis](https://www.pathlms.com/ohbm/courses/5158/sections/7792) [Videos] | An OHBM educational course covering fundamental concepts and challenges in neuroimaging meta-analyses. This is especially important for investigating genetic architecture of brain structure and function (e.g. [ENIGMA](http://enigma.ini.usc.edu)), where genetic effects are typically small thus requiring massive datasets. |
| [Advanced fMRI](https://www.pathlms.com/ohbm/courses/5158/sections/7756) [Videos] | An OHBM educational course covering fundamental concepts including analysis and interpretation. You should also check out the [Advanced Methods for Cleaning up fMRI Time-Series](https://www.pathlms.com/ohbm/courses/5158/sections/7788). |
| [Network Analysis of Brain Imaging Data](https://www.pathlms.com/ohbm/courses/5158/sections/7789) [Videos] | An OHBM educational course that covers the basics for network analyses of the brain. Integrating brain connectomics in precision psychiatry is fascinating, and may hold some clinical promise in the future.  |
| [Dr. Emma Robinson](https://emmarobinson01.com/blog/) [Blog] | Shameless plug for my supervisor's blog that focuses on a range of topics in neuroimaging including [multimodal surface matching](https://emmarobinson01.com/2020/04/05/advanced-features-of-msm-a-guide/) (which she developed!) | 
| [Neuromatch Academy](https://www.youtube.com/channel/UC4LoD4yNBuLKQwDOV6t-KPw/playlists) [Videos] | Bookmarked for later. | 
| [Human Brain Function](https://www.fil.ion.ucl.ac.uk/spm/doc/books/hbf2/) [Book] | Bookmarked for later. | 
| [FMRIB Analysis Group Technical Reports](https://www.fmrib.ox.ac.uk/datasets/techrep/) [Reports] | Bookmarked for later. | 
| [Conceptualizing mental disorders as deviations from normative functioning](https://www.nature.com/articles/s41380-019-0441-1) [Article] | Bookmarked for later.  | 

## Machine Learning 
--- 

### Classic Machine Learning

| Link | Description |
|:---:|-----------|
| [StatQuest: Machine Learning](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) [Videos] | This is a fun introduction to _classic_ machine learning with minimal mathematics. The videos are short and focus on intuition, which I am a big fan of. |
| [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) [Textbook] | This textbook by James et al. is highly regarded and extremely thorough. There are also lecture recordings by the author's that mirror the book's content and organisation, available [here](https://www.r-bloggers.com/2014/09/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/) |
| [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/) [Textbook] | This book by Hastie et al. is a step-up from _Introduction to Statistical Learning_, for those wanting more detail. |
| [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/) [Book] | Interpretability is becoming an increasingly important area in machine learning - especially in the context of healthcare. This book comes highly rated by [Mariana da Silva](https://twitter.com/marianaftsilva?lang=en-gb), who is doing her PhD in interpretable deep learning for medical imaging within the [MeTrICS lab](https://metrics-lab.github.io). | 
| [Computer Age Statistical Inference](https://web.stanford.edu/~hastie/CASI_files/PDF/casi.pdf) [Book] | Bookmarked for later. | 


### Deep Learning 

| Link | Description |
|:---:|-----------|
| [3Blue1Brown: Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) [Videos]| Grant Sanderson, creator of [3Blue1Brown](https://www.3blue1brown.com/about), creates such beautiful visualisations that really help provide an intuition behind many of the concepts that underpin basic neural networks. A great introduction to the topic. 
| A Beginner's Guide to Convolutional Neural Networks: [Part One](https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks/) and [Part Two](https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks-Part-2/) [Blog] | Convolutional neural networks (CNNs) have revolutionised computer vision and medical imaging. This blog series summarises the basics of CNNs nicely. |
| [Stanford CS231n: Convolutional Neural Networks for Visual Recognition](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) [Videos] | This is a resource I cannot recommend highly enough. It introduces a range of deep learning methods (not just CNNs) in the context of computer vision, with some mathematical notation. | 
| [Intuitively Understanding VAEs](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf) [Blog] | If you haven't guessed by now, I am very fond of resources that explain concepts using intuition - partly because I don't come from a quantitative background, but also because these sorts of resources help put the quantitative aspects in context. This is a great blog describing the main concepts underpinning variational autoencoders. |
| Representation Learning in VAEs [Blog]| Bookmarked for later - [part one](https://towardsdatascience.com/what-a-disentangled-net-we-weave-representation-learning-in-vaes-pt-1-9e5dbc205bd1) and [part two.](https://towardsdatascience.com/with-great-power-comes-poor-latent-codes-representation-learning-in-vaes-pt-2-57403690e92b)  |
| [Mathematics for Machine Learning](https://mml-book.github.io/book/mml-book.pdf) [Textbook]| A very comprehensive book that I have used to help bring some of my mathematics up to scratch.   |
| [NYU Deep Learning (with PyTorch)](https://www.youtube.com/playlist?list=PLLHTzKZzVU9eaEyErdV26ikyolxOsz6mq) [Videos] | A 14-week course run by Yann LeCun and co. at NYU, which includes lectures as well as practicals. This is one of the most up-to-date courses (uploaded this year), which is reflected in the course content (e.g. graph convolutional networks). |
| [DeepMind x UCL Deep Learning Course](https://www.youtube.com/playlist?list=PLqYmG7hTraZCkftCvihsG2eCTH2OyGScc) [Videos] | Another very up-to-date course (uploaded this year), covering a broad range of deep learning topics. Probably the best video and audio quality of all the courses I have listed. | 
| [Deep Learning](https://www.deeplearningbook.org/) [Book]| Bookmarked for later. |
| [Advanced Deep Learning for Computer Vision](https://www.youtube.com/playlist?list=PLog3nOPCjKBnjhuHMIXu4ISE4Z4f2jm39) [Videos] | A more technical set of recordings uploaded by the Technische Universität München (Technical University of Munich). Lecture topics include graph neural networks and interpretability.|
| [Probabilistic Graphical Models](https://www.youtube.com/watch?v=oqvdH_8lmCA&list=PLoZgVqqHOumTqxIhcdcpOAJOOimrRCGZn&index=1) [Videos] | Bookmarked for later.|
| [Machine Learning Blinks](https://www.youtube.com/playlist?list=PLug43ldmRSo1LDlvQOPzgoJ6wKnfmzimQ&utm_campaign=OpenMLU%20Newsletter&utm_medium=email&utm_source=Revue%20newsletter) [Videos] | Bookmarked for later. |
| [Mathematical Monk](https://www.youtube.com/user/mathematicalmonk/playlists) [Videos] | Bookmarked for later. Also videos on probability and information theory. | 

#### Geometric Deep Learning 

| Link | Description |
|:---:|-----------|
| [What is Geometric Deep Learning?](https://medium.com/@flawnsontong1/what-is-geometric-deep-learning-b2adb662d91d) [Blog] | Geometric deep learning is an umbrella term for methods that can be applied to non-Euclidean data structures (e.g. cortical surfaces represented as meshes). Because this field is relatively new, it is even harder to find introductory materials. This blog is the first of a series that fills that gap. The series also covers the [basics of graph theory](https://towardsdatascience.com/graph-theory-and-deep-learning-know-hows-6556b0e9891b), [deep learning on graphs](https://towardsdatascience.com/overview-of-deep-learning-on-graph-embeddings-4305c10ad4a4) and [graph convolutions.](https://towardsdatascience.com/graph-convolutional-networks-for-geometric-deep-learning-1faf17dee008 ) |
| [A Tale of Two Convolutions](https://towardsdatascience.com/a-tale-of-two-convolutions-differing-design-paradigms-for-graph-neural-networks-8dadffa5b4b0) [Blog] | Another well-written blog that introduces the two major approaches when applying deep learning to graphs (spectral vs. spatial). |
| [Geometric Deep Learning](https://www.youtube.com/watch?v=P4yTKhcQqOk&list=PL_VeUGLULXQux1dV4iA3XuMX6AueJmGGa&index=9&t=3055s) [Video] | A detailed review of geometric deep learning presented by [Michael Bronstein](https://scholar.google.com/citations?user=UU3N6-UAAAAJ&hl=en) at the 2018 MICCAI Medical Imaging Summer School. This talk is similar to his review article on geometric deep learning available [here](https://arxiv.org/pdf/1611.08097.pdf) |

#### Natural Language Processing 

| Link | Description |
|:---:|-----------|
| [Stanford CS224U: Natural Language Understanding](https://www.youtube.com/playlist?list=PLoROMvodv4rObpMCir6rNNUlFAn56Js20) [Videos]| Bookmarked for later. |
| [Stanford CS224N: Natural Language Processing with Deep Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) [Videos] | Bookmarked for later. |

#### Reinforcement Learning 

| Link | Description |
|:---:|-----------|
| [Stanford CS234: Reinforcement Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u) [Videos] | Bookmarked for later. |
| [DeepMind x UCL Reinforcement Learning Course](https://www.youtube.com/playlist?list=PLqYmG7hTraZBKeNJ-JE_eyJHZ7XgBoAyb) [Videos] | Bookmarked for later. | 

#### Unsupervised Deep Learning

| Link | Description |
|:---:|-----------|
| [Berkeley CS294: Deep Unsupervised Learning](https://www.youtube.com/playlist?list=PLwRJQ4m4UJjPiJP3691u-qWwPGVKzSlNP) [Videos] | Bookmarked for later. |

## Mathematics 
--- 

### Linear Algebra 

|Link|Description|
|:---:|---|
| [3Blue1Brown: The Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) [Videos] | For those with no background in linear algebra, this is the perfect introduction. Again aided with beautiful visualisations, Grant Sanderson is able to convey why linear algebra is so fundamnetal for disciplines like machine learning and medical imaging. |
| [Khan Academy: Linear Algebra](https://www.khanacademy.org/math/linear-algebra) [Videos] | [Khan Academy](https://www.khanacademy.org/profile/kaid_605952256686860540208345/courses) is a great resource for all subjects at a range of levels. Their linear algebra course is a nice introduction to the topic. |
| [Stanford CS229 Linear Algebra Review](http://cs229.stanford.edu/section/cs229-linalg.pdf) [Notes] | A concise review of the main linear algebra concepts required for machine learning.  |

### Calculus

|Link|Description|
|:---:|-----------|
| [3Blue1Brown: The Essence of Calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) [Videos] | There isn't much to say that hasn't already been said about Grant Sanderson's work, other than that this one provides insight into the fundamentals of calculus. |
| Khan Academy: Calculus [Videos] | There are several courses available that allow one to develop a working knowledge of calculus: [Calculus 1](https://www.khanacademy.org/math/calculus-1), [Calculus 2](https://www.khanacademy.org/math/calculus-2), and [Multivariable Calculus](https://www.khanacademy.org/math/multivariable-calculus) |
| [Matrix Calculus for Deep Learning](https://arxiv.org/pdf/1802.01528.pdf) [Notes] | A concise review of matrix calculus by Terence Parr and Jeremy Howard (one of the founders of [fast.ai](https://www.fast.ai), another freely availably deep learning course. |

### Probability & Statistics

| Link | Description |
|:---:|-----------|
| [StatQuest: Statistics Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) [Videos] | Teaching on statistics is either lacking or poorly taught. This series is a fantastic whistle-stop tour of statistics fundamentals. |
| [StatQuest: Linear Regression & Linear Models](https://www.youtube.com/playlist?list=PLblh5JKOoLUIzaEkCLIUxQFjPIlapw8nU) [Videos] | I found this additional series on linear regression a useful primer for aspects of the [FSL course](https://fsl.fmrib.ox.ac.uk/fslcourse/online_materials.html) described earlier. |
| [MIT 6.041: Probabilistic Systems Analysis and Applied Probability](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/video-lectures/) [Videos] | A more theoretical approach to probability, which has been useful for neuroimaging, machine learning and population genetics (below). |
| [Stanford CS229 Review of Probability Theory](http://cs229.stanford.edu/section/cs229-prob.pdf) [Notes] | A concise review of probability theory required for machine learning. |


## Population Genetics 
---

| Link | Description |
|:---:|-----------|
| [Workshop on Methods for Genone-wide Association Studies](https://www.staff.ncl.ac.uk/heather.cordell/HongKongGWAS.pdf) [Notes] | A nice set of lecture slides curated by [Professor Heather Cordell](https://scholar.google.co.uk/citations?hl=en&user=Ug15dlAAAAAJ&view_op=list_works&sortby=pubdate) covering the basics of genome-wide association studies (GWAS). The content is similar to that presented in the [Genetic Analysis of Population-based Association Studies](https://coursesandconferences.wellcomegenomecampus.org/our-events/association-studies-2019/) course, which I attended this year and __strongly__ recommend. |
| [Broad Institute Medical and Population Genetics Primers](https://www.youtube.com/playlist?list=PLEEE2A91B09B77B4A) [Videos] | With over 80 recordings, this is a comprehensive set of primers for those looking to expand their knowledge about GWAS. Their [Models, Inference and Algorithms](https://www.youtube.com/playlist?list=PLlMMtlgw6qNjROoMNTBQjAcdx53kV50cS) series also looks great. |
| [Reading Mendelian randomisation studies: a guide, glossary, and checklist for clinicians](https://www.bmj.com/content/362/bmj.k601) [Article]| An open-access article in the BMJ by Davies et al. that provides an overview of Mendelian randomisation.  |
| [Brainder](https://brainder.org) [Blog] | This blog, written by [Anderson Winkler](https://scholar.google.com/citations?user=zvMnvWIAAAAJ&hl=en), contains a wealth of knowledge. For population genetics, he has a series of blogs describing the [genetic resemblance between relatives](https://brainder.org/2015/06/13/genetic-resemblance-between-relatives/), [the kinship matrix](https://brainder.org/2015/07/29/understanding-the-kinship-matrix/) and [variance components in genetic analyses](https://brainder.org/2015/08/02/variance-components/). |
| [Basic statistical analysis in genetic case-control studies](https://pubmed.ncbi.nlm.nih.gov/21293453/) [Article]| Nature Protocols article by [Professor Andrew Morris](https://scholar.google.com/citations?hl=en&user=-3K3OIYAAAAJ&view_op=list_works), who taught in the [Genetic Analysis of Population-based Association Studies](https://coursesandconferences.wellcomegenomecampus.org/our-events/association-studies-2019/) course. The article introduces the concepts of the statistical analyses, and then provides detailed guidance about how to perform such analyses with freely available software. |
| [Data quality control in genetic case-control association studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3025522/) [Article]| Another article by Professor Andrew Morris and co. that covers data QC (which is __the most important__ part of genetic studies). | 

## Programming
---

| Link | Description |
|:---:|-----------|
| [DataCamp Python Cheatsheets](https://www.datacamp.com/community/data-science-cheatsheets) [Notes] | DataCamp have curated a number of cheatsheets for Python including: [Python Basics](https://datacamp-community-prod.s3.amazonaws.com/e30fbcd9-f595-4a9f-803d-05ca5bf84612), [Importing Data](https://datacamp-community-prod.s3.amazonaws.com/50d31142-3de0-4159-89b9-18b718a728ef), [Matplotlib](https://datacamp-community-prod.s3.amazonaws.com/28b8210c-60cc-4f13-b0b4-5b4f2ad4790b) and [Seaborn](https://datacamp-community-prod.s3.amazonaws.com/f9f06e72-519a-4722-9912-b5de742dbac4) (data visualisation), [NumPy](https://datacamp-community-prod.s3.amazonaws.com/e9f83f72-a81b-42c7-af44-4e35b48b20b7) and [SciPy](https://datacamp-community-prod.s3.amazonaws.com/5710caa7-94d4-4248-be94-d23dea9e668f) (scientific computing), Pandas [one](http://datacamp-community-prod.s3.amazonaws.com/dbed353d-2757-4617-8206-8767ab379ab3) and [two](https://datacamp-community-prod.s3.amazonaws.com/9f0f2ae1-8bd8-4302-a67b-e17f3059d9e8) (data manipulation), [Scikit-Learn](https://datacamp-community-prod.s3.amazonaws.com/5433fa18-9f43-44cc-b228-74672efcd116) (machine learning), and [Jupyter Notebooks](https://datacamp-community-prod.s3.amazonaws.com/48093c40-5303-45f4-bbf9-0c96c0133c40). | 
| [Complete Python Bootcamp](https://github.com/Pierian-Data/Complete-Python-3-Bootcamp) [Course]| A concise set of [Jupyter notebooks](https://jupyter.org) available to work through for those who want to practice coding in [Python](https://www.python.org). | 
| [Fast.ai] [Courses]| High quality material and a number of course offerings: [Practical Deep Learning for Coders](https://course.fast.ai), [Deep Learning from the Foundations](https://course19.fast.ai/part2), [Computational Linear Algebra](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md) and [Code-First Introduction to Natural Language Processing](https://www.fast.ai/2019/07/08/fastai-nlp/). | 
| [PyTorch](https://pytorch.org/tutorials/) [Tutorials]| This looks like a great set of tutorials for those wanting to learn how to build deep neural networks in [PyTorch](https://pytorch.org). |
| [Kaggle](https://www.kaggle.com/learn/overview) [Courses] | Kaggle, well-known for hosting machine learning competitions (sometimes accompanied by significant monetary prizes), have a set of short courses available including [Machine Learning Explainability](https://www.kaggle.com/learn/machine-learning-explainability) and [Intro to Game AI and Reinforcement Learning](https://www.kaggle.com/learn/intro-to-game-ai-and-reinforcement-learning). | 

## Causal Inference
---

| Link | Description |
|:---:|-----------|
| [Causal Inference: What If?](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1268/2020/07/ci_hernanrobins_31july20.pdf) | Moving beyond simple associations to causal relationships should be the ultimate goal of _any_ applied biomedical research. Recently, [Ben Glocker](https://scholar.google.com/citations?user=g_HtjLIAAAAJ&hl=en) and co. at [BioMedIA](https://biomedia.doc.ic.ac.uk) have started exploring causality in medical imaging (see [here](https://www.nature.com/articles/s41467-020-17478-w)). This is one textbook I have found covering basic concepts, courtesy of [Sam Finlayson](https://sgfin.github.io). | 
| [Elements of Causal Inference](https://library.oapen.org/bitstream/handle/20.500.12657/26040/11283.pdf?sequence=1&isAllowed=y) | Another textbook covering fundamental concepts in causal inference. | 
| [Lectures on Causality](https://www.youtube.com/watch?v=zvrcyqcN9Wo&t) [Videos] | Bookmarked for later. | 

