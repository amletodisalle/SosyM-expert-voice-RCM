# From low-level programming to full-fledged industrial model-based development: the story of the Rubus Component Model
- Alessio Bucaioni (Mälardalen University, Västerås, Sweden)
- Federico Ciccozzi (Mälardalen University, Västerås, Sweden)
- Amleto Di Salle (European University of Rome, Rome, Italy)
- Mikael Sjödin (Mälardalen University, Västerås, Sweden)

## **Abstract**
Developing distributed real-time systems is a complex task that has historically entailed specialised handcraft. In this paper, we propose a retrospective on the (r)evolutionary changes that led to the transition from low-level programming to industrial full-fledged model-based development embodied by the Rubus Component Model and its underlying tools. We focus on the needs, challenges, and solutions of a 15-year-long evolution of a development approach that has gone from low-level and manual programming to a highly automated environment offering modelling, analysis, and development of vehicular software systems with multi-criticality for deployment on single- and multi-core platforms.

## **Research questions (RQs)**
- RQ1: _Which are the publication trends in research on RCM?_
- RQ2a: _Which were the main requirements that drove the design and development of RCM?_
- RQ2b: _Which were the main challenges to be tackled for fulfilling the requirements?_
- RQ3a: _Which were the requirements that triggered the evolution of RCM?_
- RQ3b: _Which were the challenges to be tackled for evolving RCM?_

## **Pubblication trends (RQ1)**
To answer RQ1, we conducted a lightweight literature review to identify the publication trends of this 15-year-long collaboration over time.
We collected the data through the web search engine [Google Scholar](https://scholar.google.com) using the following search string: 

_rubus AND component AND model_

We did a full-text search. The RCM was formally defined in 2008 by Häanninen et al.[1], but the first hints on RCM date back to 2003. 
For this reason, we carried out our search from 2003 to date (December 15, 2022). 

The initial search gave [265 results](google-scholar.csv). Then, we removed impurities and duplicates; eventually, we applied the following inclusion and exclusion criteria:
- **I1**: Studies written in English
- **I2**: Studies exploiting the Rubus Component Model 
- **E1**: Studies with full-text not available
- **E2**: Studies in the form of tutorial papers, editorials, reports, etc., since they do not carry the type of information that we seek.

At the end of the process, we obtained a set of 171 primary studies.

## References
1. Hänninen, K., Mäki-Turja, J., Nolin, M., Lindberg, M., Lundbäck, J., Lundbäck, K.: The rubus component model for resource onstrained real-time systems. In: IEEE Third International Symposium on Industrial Embedded Systems, SIES 2008, Montpellier / La Grande Motte, France, June 11-13, 2008, p. 177–183. IEEE (2008). https://doi.org/10.1109/SIES.2008.4577697