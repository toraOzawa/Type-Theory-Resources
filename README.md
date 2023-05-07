# Type Theory Resources
Type theory spans quite a lot of areas and is deeply rooted within areas of mathematics, logic, and computer science. So when curious about the subject
it can be hard to know where to start. When I was first looking for sources I was certainly overwhelemed and also did not fully understand how different 
some materials were and the different sort of directions one can take when learning and applying type theory. The direction I took my learning was certainly 
more on the mathematical, theoretical side as opposed to the applied. There are lots of great sources on learning about "using" type theory, mainly through 
formal methods, proof asistants, designing type systems and so on, but I do not have much experience with them. Likewise this list is in no means
comprehensive and is a bit heavier on the material related to my interests. 

I used the sources mainly for an independent study I did in Spring of 2023 on Type Theory. The accompanying slides for the talk I did 
and the paper I wrote for it can be found in this repo as well. The paper was written with the intention of being accessible for anyone with 
exposure/passing familiarity with set theory, programming, propositional/first order logic and inference rule notation (the last of which can likely just 
be learned on one's owwn in one sitting if not already familiar with it). Hopefully, it can serve as a very brief, first pass of the technical aspects of 
the subject for those new to learning about type theory. The material is heavily adapted from the [HoTTest Summer School](https://github.com/martinescardo/HoTTEST-Summer-School). 
I strongly encourage to accompany this starting material, either through the paper or the lectures, with some of the "Casual Resources" listed below.
More specifically, if one is interested in learning how to use proof assistants, then I think the early material of the lectures/paper can be quite useful 

A brief disclaimer that I have not gone through all of these comprehensively and in fact I plan to continue to use many of them myself as well. 
The annotations below for the sources will include how much I have gone through and the remarks be tailored around that as well. 

## Introductory Material and "Main" Resources 
### [Propositions as Types](https://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)
An amazing, brief introduction to the subject. It does a great job coheisvely covering some history on logic, the Curry-Howard Corresponedence, the relation between logic and computation, natural deduction, the lambda calculus and more. 

### [HoTTest Summer School](https://github.com/martinescardo/HoTTEST-Summer-School)
A large online lecture series from the summer of 2022. Their tracks were "Homtopy Type Theory" and "Formalization in Agda", and I only really used the lectures
from the Homotopy Type Theory track, as I was concurrently taking a seminar course on learning how to use Coq. This combination was quite nice because the Coq
proof assitant is quite high level in the sense that it abstract aways a lot more of the nitty gritty details it using to perform the inference and being able
to recognize what was going on under the hood certainly complimented my learning of both. For learning Coq, my seminar an online volume from the infamous
[Software Foundations](https://softwarefoundations.cis.upenn.edu/lf-current/toc.html) series. Overall, the lectures were great and while someone who is more
interested as a practioner of proof assitants may not benefit from all the lectures, the first 4-5 are fundamental to many type theories used today, including 
those which underly proof assistants. They also have great exercises and video sessions of instructors solving them. The first lecture takes somewhat of a 
different approach than the accompanying **Introduction to Homtopy Type Theory** listed below, outlining proof trees in natural deduction and also referring 
to the statically typed lambda calculus to outline some of the starting types. It is still however self-contained, although familiarity with logic will only
help as well. 

### [Introduction to Homtopy Type Theory](https://arxiv.org/abs/2212.11082)
A wonderful self contained book on (homotopy) type theory. Goes with the lectures for HoTTest great. Lots of exercises. They formally fill in some of the 
details which are left out from the lectures, especially towards the beginning with judgments and contextes. 

### [Homotopy Type Theory](https://homotopytypetheory.org/book/)
A standard text for homotopy type theory that I have not read much of, just partially to fill in bits pieces and to get some more ideas for motivating
in my talk. This book is not as self-contained in the sense that some mathematical maturity is required and certainly familiairity with cateogry theory 
is needed. 

## Secondary Resources and alternate lists 
These sources I did not use as directly within the scope of my independent study, but are certainly useful for learning about closely related topics and areas. 
### [Oregon Programming Languges Summer School](https://www.cs.uoregon.edu/research/summerschool/summer23/)
A great program that has been running yearly and uploading their lectures online. Lots of great sets of lectures which serves as great introductory material to topics such as proof theory, category theory, type theory. There are also intrigueing lectures on applications of type theory and related topics to specific computer science related domains. 

### [learn-tt](https://github.com/jozefg/learn-tt/blob/master/README.md#learn-tt)
### [Programming Language Theory](https://steshaw.org/plt/)
Two lists of resources which I found useful and wish I had found earlier in my initial research, lots of sources on both mathematically related areas to type theory as well as the practical side of things. 

## Casual Resources 
### [Type Theory For all Podcast](https://www.typetheoryforall.com/)
An amazing podcast hosted by [Pedro Abreu](https://pedroabreu0.github.io/), a PHD student in programming languages at Purdue University. The episodes are 
a great combination of discussions of formal methods in industry and research, as well as primers on technical ideas and results related to type theory and 
logic. I was able to listen to all the episodes over the semester

### [Iowa Type Theory Commute](https://homepage.divms.uiowa.edu/~astump/ittc.html)
Another amazing podcast, hosted by Aaron Stump, a professor at the University of Iowa. The topics themselves are a bit more technical than in Pedro Abreu's 
podcast, however their presentation and discussion are extremely acessible. Again works best s a primer of sorts. 
