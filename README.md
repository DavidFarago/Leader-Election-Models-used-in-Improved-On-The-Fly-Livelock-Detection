Leader-Election-Models-used-in-Improved-On-The-Fly-Livelock-Detection
=====================================================================

Promela and DVE Models for Leader Election, used in the paper Improved On-The-Fly Livelock Detection

The PROMELA database at http://www.albertolluch.com/research/promelamodels contains the original models. 
This repository contains the models that were modified:

The divine directory contains modified, unwound DVE models of the Dolev, Klawe & Rodeh leader election: 
  progress was inserted and instances created that have between 6 and 17 nodes.
 
The PROMELA directory contains modified, unwound PROMELA models for various leader election algorithms:
* for Dolev, Klawe & Rodeh, again progress was inserted and two instances unwound, with 9 and 10 nodes;
* for the timing algorithm, progress was inserted and instances created that have between 4 and 9 nodes; 
* for round based ItaiRodeh with limited number of rounds, two unwound instances with 6 and 9 nodes 
  and a few injected NPcycle were created, either at a shallow or a deeper level. (Other protocols without a counter did not allow to inject NPCs only at a deeper level.)
