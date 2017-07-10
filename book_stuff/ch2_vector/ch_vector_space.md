\chapter{Vectorisation and its consequences}
\label{ch:vector}



>The table has the function of treating multiplicity itself, distributing it and deriving from it as many effects as possible [@Foucault_1997, 149] \index{table} \index{Foucault, Michel}

>We call _any_ set that satisfies these properties (or axioms) a *vector space*, and the objects in the set are called *vectors*. [@Larson_1996, 166] \index{vector} \index{vector space|see also {mathematics!linear algebra}}

>All things are vectors [@Whitehead_1960,309]\index{Whitehead, Alfred North!on vectors}

The operational power of  machine learning locates data practice in an expanding epistemic space. The space derives, I will suggest, from a  specific operational diagram that maps data into  a \gls{vector space}. It  \textit{\glspl{vectorize}} data according to axes, coordinates, and scales. Machine learning, in turn, inhabits a vectorised space, and its  operations vectorise data.  \index{data!vectorization|see {vector space!vectorization}}

Often data is  represented as an homogeneous mass or a continuous flowing stream. My aim here, however, is to archaeologically examine some of the transformations that allow different shapes and densities of data, whether in the form of numbers, words or images, to become machine learnable. Data in its local complexes spaces out in many different density shapes, depending on how the data has been generated or instanced.[^2.104] \index{data!density of} Whatever the starting point -- a measuring instrument, people clicking and typing on websites, a device like a camera, a random number generator, etc. --  machine learners only ever encounter data in specific *vectorised* shapes (vectors,  matrices, arrays, etc.), mapped to  a geometrically coordinate volume. The mapping and forming, when mentioned at all,  is sometimes referred to as 'data cleaning' but that term covers over important but largely taken for granted and constitutive transformations. \index{data!cleaning} The archaeology of data shapes presented in this chapter explores a range of transformations focused around the table or row-column grid. \index{archaeology!of tables}

The reshaping and re-flowing of data densities into vectors deeply affects machine learning.   This forming and reforming of data is evidence of  implicated relations. The philosopher A.N. Whitehead called 'strain':

>a feeling in which the forms exemplified in the datum concern geometrical, straight, and flat loci will be called a "strain." In a strain, qualitative elements, other than the geometrical forms, express themselves as qualities implicated in those forms [@Whitehead_1960, 310]. \index{Whitehead, A. North}  \index{data!strain}

In many machine learning models the exemplified forms are straight or flat loci (as we see in chapter \ref{ch:function}).  Yet  different practices also elicit relations that strain the linear shaping of data and these divergent relations sometimes combine in generative and provocative ways. 

#  Vector space and geometry

Statistical modelling, data-mining, pattern recognition, recommendation systems, network modelling and machine learning rely very much on the operation called 'fitting a model.' \index{model!fitting} Fitting as a spatial practice has some elements that resemble the phenomenologist Edmund Husserl's account of the origin of geometry. Husserl writes:

>First to be singled out from the thing-shapes are surfaces -- more or less "smooth," more or less perfect surfaces; edges, more or less rough or fairly "even"; in other words, more or less pure lines, angles, more or less perfect points; then again, among the lines, for examples, straight lines are especially preferred, and among surfaces, the even surfaces. ... Thus the production of even surfaces and their perfection (polishing) always plays its role in praxis [@Derrida_1989, 178] \index{Husserl, Edmund!on thing-shapes in geometry}

Husserl here refers is attempting to describe something of the way in which forms such as planes, lines, circles, triangles, squares, and points became objects of geometrical practice. A similar polishing and smoothing of surfaces is certainly taking place today in the thing-shapes we call data. The basic machine learning work of 'fitting a model' (or many models)  to data is often literally implemented, as we will see, by  constraining data within a coordinate, discretized space, which I term the \textit\gls{vector space}. \index{vector space} 

Critical thought from phenomenology to social theory has a long-standing  nervousness about the power of geometry and its gradual movement away from shapes and things towards mathematical operations.   The philosopher Hannah Arendt, for instance, observes: 

>decisive is the entirely un-Platonic subjection of geometry to algebraic treatment, which discloses the modern idea of reducing terrestrial sense data and movements to mathematical symbols [@Arendt_1998,265] \index{Arendt, Hannah!on geometry and algebra}

The crux of the problem rests on the 'treatment' or operations that 'reduce terrestrial sense data and movements' to symbols. One challenge for contemporary thought is how to orient itself to such operations, particularly in their data-intensive forms,  without assuming that the familiar story of scientific and technical reduction of sense and movement to the lines and planes of modern geometry is simply reinforced in contemporary data practice. \index{critical thought!relation to geometry} If an archaeology of data vectorization does anything, it needs to offer an alternative to that reduction.  

They also, as we will see, reach down into the practices of programming, infrastructure and hardware production in ways that differ somewhat from increases in computational power or speed. Familiar narratives of Moore's Law increases in  speed or efficiency of computation do not account for transformations of   data in  `R` and other computing environments (for instance, the popular `Map-Reduce` architecture invented at Google Corporation to speed up its search engine services [@Mackenzie_2011] \index{data!architecture!map-reduce}).  Vectorisation transforms data along more diagrammatic lines.[^2.1]  

# Mixing places


```
## Error in library(ElemStatLearn): there is no package called 'ElemStatLearn'
```

```
## Error in find.package(package, lib.loc, verbose = verbose): there is no package called 'ElemStatLearn'
```

```
## Error in as.data.frame(datasets_results): object 'datasets_results' not found
```

```
## Error in nrow(datasets): object 'datasets' not found
```

```
## Error in xtable(datasets, caption = "Datasets in \\textit{Elements of Statistical Learning}", : object 'datasets' not found
```

```
## Error in print.xtable(dataset_table, type = "latex"): object 'dataset_table' not found
```












