## Modelling-Derivatario-as-LLOD ##

It is a Linguistic Linked Open Data (LLOD) project as well as my master thesis project.

# Italian derivational morphology #

Traditionally, morphology is defined as the discipline that studies the internal structure of words: its
existence therefore presupposes the existence of words. The two main categories are: inflectional morphology
and derivational morphology. Our studies focus on derivational morphology which concerns the formation of new lexemes on the basis
of existing morph.

# Linguistic linked open data (LLOD) #

LLOD Cloud is a community project initiated by the Open Knowledge Foundation's Open Linguistics Working
Group (OWLG) to bridge the gap between developments in language technology and linguistics and progress in the
Semantic Web and artificial intelligence. Its core objective is to promote and track the application of open data in
linguistics and facilitate the sharing of existing language resources.

**Generally speaking, our study is based on these two backgrouds.**

# The motivation: fill the gap # 

LiITA: LiITA: Linking Italian is a knowledge base of linguistic
resources for Italian. https://www.liita.it/

However, in LiITA, it lacks the derivational morphology information (The affixes, the word formation process etc.)
Meanwhile, the study of Talamo et al. DerIvaTario : An annotated lexicon of Italian derivatives offers the detailed annotations for
Italian derivatives which could enrich the morphological information in LiITA. But the annotated lexicon is in format of CSV which is not
the suitable for LOD.

# Linking to LiIta # 

We first obtain the LiITA URIs for each base and derivatives represented in our model as Ontolex-lemon lexical entries which link those 
URIs via ontolex:canonicalForm or ontolex-lexicalForm.

# Modelling the data #

We use the Ontolex-lemon model and its modules (Morph)

# The data we created # 

The data is in turtle format ready to be integrated in liIta in the future and be requested through Sparql.
