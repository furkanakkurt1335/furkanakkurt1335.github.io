---
layout: post
title: "Interlingua"
date: 2022-12-22 00:49:14 +0300
categories: 58h ssw ontology
giscus_comments: true
---

Originally posted as part of the [CMPE58H](https://cmpe.boun.edu.tr/courses/cmpe58h) course at `https://furkanakkurt5204.gitlab.io/personal/ontology/2022/12/21/interlingua`.

---

The EuroWordNet project<sup>1</sup> aimed to "develop a multilingual database with wordnets in several European languages".
It was started in 1996 and its project manager was Piek Vossen<sup>2</sup>.
They produced wordnets for many European languages as a part of this project.
The files were not open to the public and they had Euro rates per synsets.

Continuing with this idea, Mr Vossen founded the Global WordNet Association<sup>3</sup> (GWA).
GWA has the Collaborative InterLingual Index<sup>4</sup> (CILI) which provides mappings from their generated URIs of concepts to the Princeton WordNet's<sup>5</sup> URIs.
So these concepts can be linked to wordnets of other languages by a relation.

**Example from CILI**:

```rdf
<i23197>	a	<Concept> ;
	skos:definition	"make neat, smart, or trim"@en ;
	dc:source	pwn30:00293977-v .

<i23198>	a	<Concept> ;
	skos:definition	"produce or yield flowers"@en ;
	dc:source	pwn30:00294245-v .
```

`pwn30:00294245-v` corresponds to [this](http://wordnet-rdf.princeton.edu/pwn30/00294245-v) and `pwn30:00293977-v` corresponds to [this](http://wordnet-rdf.princeton.edu/pwn30/00293977-v).

The title of the blog refers to an international auxiliary language<sup>6</sup> (IAL), probably the most widely used.
IALs are constructed to be used to facilitate communication between persons of any nationality that have no common native tongues.

## References

1. [The EuroWordNet project](https://archive.illc.uva.nl//EuroWordNet/)
2. [Piek Vossen](https://vossen.info/)
3. [Global WordNet Association](http://globalwordnet.org/)
4. [Collaborative InterLingual Index](https://github.com/globalwordnet/cili)
5. [Princeton WordNet](https://wordnet.princeton.edu/)
6. [International auxiliary language](https://en.wikipedia.org/wiki/International_auxiliary_language)
