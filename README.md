Leader-Election-Models-used-in-Improved-On-The-Fly-Livelock-Detection
=====================================================================

Promela and DVE Models for Leader Election, used in the paper Improved On-The-Fly Livelock Detection

The PROMELA database at http://www.albertolluch.com/research/promelamodels contains the original models. 
This repository contains the models that were modified:

the divine directory contains modified, unwinded dve-models of the Dolev, Klawe & Rodeh leader election: 
  progress was inserted and instances created that have between 6 and 17 nodes
 
the promela directory contains modified, unwinded promela-models for various leader election algorithms:
* for Dolev, Klawe & Rodeh, again progress was inserted and two instances unwound, with 9 and 10 nodes;
* for the timing algorithm, progress was inserted and instances created that have between 4 and 9 nodes; 
  furthermore, two models with 9 nodes and a few injected NPcycles, either at a shallow or a deeper level;
* for round based ItaiRodeh with limited number of rounds, two unwinded instances with 6 nodes 
  and a few injected NPcycle were created, either at a shallow or a deeper level;
