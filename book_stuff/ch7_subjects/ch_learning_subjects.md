\chapter{Propagating subject positions}
\label{ch:subjects}



> If a proposition, a sentence, a group of signs can be called 'statement,' it is not therefore because, one day, someone happened to speak them or put them into some concrete form of writing; it is because the position of the subject can be assigned [@Foucault_1972, 95] \index{statements!position of subject}

> Generalization error is what we care about  [@Ng_2008f]

> *Predict if an online bid is made by a machine or a human*, 'Facebook Recruiting IV: Human or Robot?' [@Kaggle_2015e]

Who is the subject of machine learning? \index{machine learning!subject positions in}  In early 2002, while carrying out an ethnographic study of 'extreme programming,' a software development methodology popular at that time [@Mackenzie_2004], I spent several months visiting a company in Manchester developing software for call centres. The software was to manage 'knowledge' in call centres such that any query from a caller could be readily answered by staff who would query a knowledge management system to find answers to the query. \index{knowledge!management of}  This system was marketed on the promise of machine learning. It relied on an artificial neural network that learned to match queries and responses over time. \index{machine learner!neural net} A taciturn neural network expert, Vlad, sat in a different part of the room from the developers working on the databases and the web interfaces. Vlad's work on the neural network was at the core of the knowledge management system yet outside the orbit of the software development team and its agile software development processes. The rest of the team  generally regarded Vlad and the neural net as an esoteric,  temperamental yet powerful component, a hidden node we might say, of the knowledge management system.\index{machine learner!neural net} 

As we have seen with `kittydar`,\index{machine learner!\texttt{kittydar}} the position of machine learners is changing. They are no longer exotic or specialized, but banal or occasionally spectacular. Hilary Mason, who was Chief Scientist at bitly.com (an online service that shortens URLs), outlined an everyday  machine learning subject position at a London conference in 2012 called 'Bacon: Things Developers Love': \index{Mason, Hilary}

>You have all of these things that are different – engineering, infrastructure, mathematics and computer science, curiosity and an understanding of human behaviour – that is something that usually falls under the social sciences. At the intersection of all these things are wonderful people. But we're starting to develop something new, and that is - not that all of these things have not been done for a very long time - but we are only just now building systems where people, individual people, have all of these tools in one package, in one mind. (Hilary Mason, Chief Scientist, bitly.com) [@Mason_2012] 

These 'things that are different,'  what I have been calling an operational formation,  assign subject positions.  In what ways does machine learning assign subject positions? In front of an audience of several hundred software developers, Mason describes shifts in the work of programming associated with the growth of large amounts of data associated with 'human behaviour.' At the centre of this shift stand 'wonderful people' who combine practices and knowledges of communication infrastructure, technology, statistics, and 'human behaviour' through curiosity and technical skills.  Mason was, in effect, telling her audience of software developers who they could  become in relation to expansive changes occurring around and in their work. \index{programming!work!transformation of}  The title of her talk was 'machine learning for hackers', and her audience were those hackers or programmers whose coding and programming attention may have been previously trained on web interfaces or database queries, but was now drawn towards machine learning. A change in programming practice and a shift towards machine learning was, she implied,  the key to programmers becoming the wonderful people, agents of their own time, capable of doing what is only now just possible because it is all together in 'one package, one mind.'

Neural nets stand at an intersection of infrastructure and cognition, and then propagate subject positions forwards and backwards. Their operations encourage and eleict competitively ranking as an  ordering that not only compares human and machines, but subject positions more generally.\index{subject positions}  

# Propagation across human-machine boundaries

The  concatenation of 'one package, one mind' does not definitively allocate agency to people or things. (A 'package' after all is another name for a library of code.)  Mason adumbrates the outline of a subject position located  at the intersection of network infrastructure, mathematics and human behaviour.[^7.1] Mason, herself one of _Fortune_ magazines 'Top 40 under 40' business leaders to watch [@CNN_2011] and also featured in _Glamour_, a teenage fashion magazine [@Mason_2012], might personify such a 'wonderful person.' \index{Mason, Hilary} She is not a lone example. In mid-2016 Google announced a comprehensive program to re-train its software developers as machine learners [@Levy_2016].[^7.2] 

'It is the privileged machine in this context that creates its marginalized human others' writes Lucy Suchman in her account of  the encounters that 'effect "persons" and "machines" as distinct entities' [@Suchman_2006, 269]. \index{Suchman, Lucy!human-machine difference} \index{differences!human-machine}  While Mason and other relatively well-known human machine learners are not exactly marginalized (just the opposite, they achieve minor celebrity status in some cases), Suchman recommends 'recognition of the particularities of bodies and artifacts, of the cultural-historical practices through which human-machine differences are (re-)iteratively drawn, and of the possibilities for and politics of redistribution across the human machine boundary' (285). The intersections that machine learners currently occupy are heavily re-distributional. In almost every instance, machine learners claim to do something that humans alone, no matter how expert, could not. Does the re-distribution of engineering, mathematics, curiosity, infrastructure and 'something that usually falls under the social sciences' (but perhaps no longer does so?) both energise subjects ('its a pretty exciting time to be in any of these things') and assign them a marginal albeit still pivotal position in relation to privileged machines?

Machine learner subject positions are the topic of this chapter. I focus on artificial neural networks, or neural nets, in their various forms ranging from the multilayer perceptron (MLP) to the convolutional neural nets (CNN), recurrent neural nets (RNN) and deep belief networks of many recent deep learning projects (particularly in machine learning  competitions, as discussed below [@Dahl_2013]). \index{neural net|see{machine learner!neural net}} in exploring the re-drawing of subject-machine positions.  \index{diagram!machine learner as} Neural nets propagate between infrastructures, engineering and human behaviour (as Mason puts it), re-drawing human-machine differences, sometimes making it hard to seen what subject position they entail, where subjects are located or what they say, see and do. 

Like other machine learners, neural nets re-draw human-machine differences. Geoffrey Hinton, Simon Osindero and Yee-Why Teh \index{Hinton, Geoffrey} writing in _Neural Computation_ in 2006 described a 'fast learning algorithm for deep belief nets' [@Hinton_2006a]. Their description, whilst mostly couched in terms of conditional distributions, model parameters, and error rates,  also contains a section entitled 'Looking into the Mind of a Neural Network' (1545-1546). In that section, they describe how they used their deep belief network to _generate_ rather than classify images.[^7.01] In the process they were able to see what the 'associative memory has in mind' (1545). The term 'mind,' they comment, 'is not intended to be metaphorical' (1546) because the neural net in question has a distributed memory of the digits it has seen. Put slightly more formally, 'the network has a full generative model, so it is easy to look into its mind - we simply generate an image from its high-level representations' (1529).  \index{model!generative} 'Looking,' as often the case in machine learning, takes the form of diagramming a pattern, partition or strain in the data. 

The substitution of 'mind' and model reproduces many aspects of the figure  of artificial intelligence (which has typically relied on rule-based or symbolic reasoning), but the appearance of 'mind' in the form of a generative model (see chapter \ref{ch:probability}) suggests a rather different subject position. Archaeologically, the description of subject positions entails more than giving voice the existential threat of artificial intelligence.\index{archaeology!subject positions}. It first of all entails multiple positions linked to different groupings and statements in the operational formation.  As I will suggest, neural nets are particularly interesting because they re-draw human-machine boundaries through a combination of feeding-forward of potentials and propagating backwards of differences specifically concerned with images. Similarly, the practice of machine learning shifts  subject positions in a backward and forward movement. It  propagates potentializing optimism even as it undercuts the very differences that give rise to that optimism. 



```
## Error in library(tidyr): there is no package called 'tidyr'
```

```
## Error in function_list[[k]](value): could not find function "unnest"
```

```
## Error in function_list[[k]](value): could not find function "unnest"
```

```
## Error in function_list[[k]](value): could not find function "unnest"
```

```
## Error in function_list[[k]](value): could not find function "unnest"
```

```
## Error in rbind(stat_df, compsci_df, eng_df): object 'stat_df' not found
```

```
## Error in df$techniques: object of type 'closure' is not subsettable
```

```
## Error in df$techniques: object of type 'closure' is not subsettable
```

```
## Error in table(df_top$techniques[df_top$discipline == "statistics"]): object 'df_top' not found
```

```
## Error in ggplot(df_top, aes(x = year, fill = discipline)): object 'df_top' not found
```






