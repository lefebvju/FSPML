# Ouverture à la recherche
Auteur : LEFEBVRE Julien, MERCIER LORIS  
## **SUJET** : FSPML -> Sélection de variables pour l'approche **Partial Multi-Label**
>La sélection de variables est une tâche primordiale dans les 
processus d’apprentissage automatique et de data mining. Elle 
consiste à « nettoyer » l’espace de description des données en 
vue d’améliorer la performance des algorithmes 
d’apprentissage.  
Cette tâche est relativement, très répandue en mode supervisé, 
encore moins en mode non-supervisé et demeure défiante en 
mode semi-supervisé. Le challenge est de satisfaire le 
compromis entre la structure géométrique de la partie non-étiquetée des données et le peu de supervision opéré dans leur 
partie étiquetée. D’autre part, traiter cette tâche dans un cadre 
multi-labels (plusieurs cibles à la fois) avec un étiquetage 
incertain suscite une investigation plus approfondie sur le 
domaine.  
Le travail consistera à dresser un état de l’art de premier plan 
sur la problématique abordée, et faire une étude comparative 
significative (en Python) des approches investiguées avec des 
tests statistiques à l’appui.


## Rapport d'avancement
Problématique d'étude très récente, la sélection de variables appliquées au multi-label partiel n'en ai pour l'heure qu'au stade embryonnaire des recherches. 

Afin d'aborder en profondeur les différentes notions rattachées à ce sujet FSPML, nous avons fait le choix en concertation avec nos encadrants de projet de traduire ce sujet en trois états de l'art :
- Sélection de variables supervisée mono-label
- Sélection de variables semi-supervisée mono-label
- Sélection de variables appliquée à l'univers multi-label et multi-label partiel (PML)

Ces 3 parties ont l'avantage d'être progressive.   
**Tout d'abord**, notre premier état de l'art présente les différentes catégories de sélection de variables en se basant sur le mode d'apprentissage le plus répandu : Supervisé, mono-label. Nous introduisons ainsi les trois grandes approches de sélection de variables que sont les filtres, les wrappers et les méthodes embedded.
**Nous** appliquons ensuite un focus sur l'approche semi-supervisée dépendant à la fois de l'approche supervisée et non-supervisée.    
**Enfin**, nous appliquons les connaissances précédemment étudiées à l'univers multi-label. Ici chaque instance initiale est rattachée à plusieurs labels en sortie. Cette partie est l'occasion pour nous d'étudier en détail la sélection de variables en mode multi-label partiel, point d'orgue de nos 6 mois de travail.


## Nos productions
Nos 3 états de l'art sont à retrouver dans les fichiers PDF de ce dépôt.  

La vidéo de vulgarisation est disponible ici : https://youtu.be/NsH3ifd8bCo

Les références de nos différents articles sont disponibles ci-dessous. (Pour le troisième état de l'art, toutes les références sont à retrouver directement dans le document)

### Etat de l'art 1 : Sélection de variables pour l'approche supervisée
[1] Battiti, R. (1994).  Using Mutual Information for Selecting Features in Supervised Neural Net Learning.  
*IEEE Trans*. Neural Netw. 5, 537–550.    

[2] Ben Brahim, A., Jerbi, W., and Nadia, E. (2017). A Hybrid Embedded-Filter Method for Improving Feature 
Selection Stability of Random Forests, *Advances in Intelligent Systems and Computing* 552:370-379.  

[3] Bolón-Canedo, V., Sánchez-Maroño, N., and Alonso-Betanzos, A. (2013). A Review of Feature Selection 
Methods on Synthetic Data. *Knowl. Inf. Syst. 34*, 483–519  

[4] Breiman, L., Friedman, J. H., Olshen, R. A., and Stone, C. J. (1984). Classification and Regression Trees. 
*Chapman and Hall/CRC*.  

[5] Breiman, L. (2001). Random Forests. *Mach. Learn*. 45, 5–32. 

[6] Caruana, R., and Niculescu-Mizil, A. (2006). An empirical comparison of supervised learning algorithms, 
in *23rd International Conference on Machine Learning*, (Pittsburgh, PA: ACM Press), 161–168.  

[7] Fisher,R (1935). Statistical Methods for Research Workers, *Oliver and Boyd*, p200.   

[8] González, J., Ortega, J., Damas, M., Martín-Smith, P., & Gan, J. Q.  (2019). A new multi-objective wrapper 
method for feature  selection–Accuracy and stability analysis for BCI. *Neurocomputing*, 333, 407-418.   

[9]  Goudey,  B.,  Rawlinson,  D.,  Wang,  Q.  et  al.  (2013).  GWIS  -  model-free,  fast and  exhaustive search  for 
epistatic interactions in case-control GWAS. *BMC Genomics 14* (Suppl 3).

[10] Greene, C. S., Penrod, N. M., Kiralis, J., and Moore, J. H. (2009). Spatially Uniform ReliefF (SURF) for 
Computationally-Efficient Filtering of Gene-Gene Interactions. *BioData Min*   

[11] Guyon,I. and Elisseeff,A. (2003). An introduction to variable and feature selection. *J. Mach Learn Res.*, 
3, 1157–1182.  

[12] Guyon, I., Gunn, S., Nikravesh, M., and Zadeh, L. (2006). Feature Extraction: Foundations and 
Applications, *Berlin: Springer*, 207 

[13] John, G. H., Kohavi, R., and Pfleger, K. (1994). Irrelevant Features and the Subset Selection Problem, 
*Machine Learning Proceedings* 1994 (Burlington, MA: Morgan Kaufmann Publishers), 121–129, 121–129.   

[14]  Kassahun  Azezew  Ayidagn,  prof.  Shilpa  Gite  (2017)  Analysis  of  Feature  Selection  Algorithms  and  a 
Comparative study on Heterogeneous Classifier for High Dimensional Data survey, *International Journal of 
Engineering Trends and Technology* (IJETT), V53(2),59-63.  

[15]  Kira,  K.,  and  Rendell,  L.  A.  (1992).  Feature  Selection  Problem:  Traditional  Methods  and  a  New 
Algorithm, *Proceedings Tenth National Conference on Artificial Intelligence 2*, 129–134.   

[16] Kohavi, R., and John, G. H. (1997). Wrappers for Feature Subset Selection. *Artif. Intell. 97*, 273–324. 

[17]  Kononenko,  I.  (1994).  Estimating  Attributes:  Analysis  and  Extensions  of  RELIEF,  Lecture  Notes  in 
*Computer  Science*  (Including  Subseries  Lecture  Notes  in  Artificial  Intelligence  and  Lecture  Notes  in 
Bioinformatics) (Berlin, Heidelberg: Springer), 784, 171–182  

[18] Mao, Y., & Yang, Y. (2019). A wrapper feature subset selection method based on randomized search and 
multilayer structure. *BioMed research international*.   
 
[19] Mnich, K., & Rudnicki, W. R. (2020). All-relevant feature selection using multidimensional filters with 
exhaustive search. *Information Sciences*, 524, 277-297.   

[20]  Nguyen,  B. &  Xue,  B.  &  Liu,  I. &  Zhang,  M..  (2014).  Filter  based backward  elimination  in  wrapper 
based PSO for feature selection in classification. *Proceedings of the 2014 IEEE Congress  on Evolutionary 
Computation*, CEC 2014.   

[21]  Lunetta,  K.  L.,  Hayward,  L.  B.,  Segal,  J.,  and  van  Eerdewegh,  P.  (2004).  Screening  Large-Scale 
Association Study Data: Exploiting Interactions Using Random Forests. *BMC Genet. 5*, 32.   

[22]  Peng,  H.,  Long,  F.,  and  Ding,  C.  (2005).  Feature  Selection  Based  on Mutual  Information:  Criteria  of 
Max-Dependency, Max-Relevance, and Min-Redundancy. *IEEE Trans. Pattern Anal. Mach. Intell. 27*, 1226–1238.  
   
[23] Quinlan, J.R. (1986). Induction of decision trees. *Mach Learn 1*, 81–106.   

[24] Quinlan, J.R. (1992). C4.5 Programs for Machine Learning, *Morgan Kaufmann*, San Mateo.

[25] Reif, M., & Shafait, F. (2014). Efficient feature size reduction via predictive forward selection. *Pattern 
Recognition*, 47(4), 1664-1673. 

[26] Saeys, Y., Inza, I., and Larrañaga, P. (2007). A Review of Feature Selection Techniques in Bioinformatics. 
*Bioinformatics 23*, 2507–2517  

[27] Schlittgen, R. (2011). A Weighted Least-Squares Approach to Clusterwise Regression. *AStA Adv. Stat. 
Anal. 95*, 205–217.   

[28] Schwarz, D. F., König, I. R., and Ziegler, A. (2010). On Safari to Random Jungle: a Fast Implementation 
of Random Forests for High-Dimensional Data. *Bioinformatics 26*, 1752–1758.   

[29]  Stracuzzi,  D.  J.,  &  Utgoff,  P.  E.  (2004).  Randomized  variable  elimination.  *The  Journal  of  Machine 
Learning Research*, 5, 1331-1362. 

[30] Tibshirani, R. (1996), Regression Shrinkage and Selection Via the Lasso. Journal of the Royal Statistical 
*Society: Series B (Methodological)*, 58: 267-288. 

[31] Winham, S. J., Colby, C. L., Freimuth, R. R., Wang, X., de Andrade, M., Huebner, M., et al. (2012). SNP 
Interaction Detection with Random Forests in High-Dimensional Genetic Data. *BMC Bioinforma. 13*, 164. 

[32] Yang, H., and John Moody (1999). Feature selection based on joint mutual information. *Proceedings of 
international ICSC symposium on advances in intelligent data analysis.* Vol. 23. Rochester, NY: Citeseer. 

[33]  Yu,  L.,  and  Liu,  H.  (2004).  Efficient  Feature  Selection  via  Analysis  of  Relevance  and  Redundancy.               
*J. Mach. Learn.* Res. 5, 1205–1224. 

[34] Ziegler, A., DeStefano, A. L., König, I. R., & Group 6. (2007). Data mining, neural nets, trees—problems 
2 and 3 of genetic analysis workshop 15. *Genetic epidemiology*, 31(S1), S51-S60.

### Etat de l'art 2 : Sélection de variables pour l'approche semi-supervisée
[1]  Ang,  J.  C.,  Haron,  H.,  &  Hamed,  H.  N.  A.  (2015,  May).  Semi-supervised  SVM-based  feature 
selection  for  cancer  classification  using  microarray  gene  expression  data.  *In Current  Approaches  in 
Applied  Artificial  Intelligence:  28th  International  Conference  on  Industrial,  Engineering  and  Other 
Applications  of  Applied  Intelligent  Systems,  IEA/AIE  2015*,  Seoul,  South  Korea,  June  10-12,  2015, 
Proceedings (pp. 468-477). Cham: Springer International Publishing. 

[2]  Barkia,  H.,  Elghazel,  H.,  &  Aussem,  A.  (2011,  December).  Semi-supervised  feature  importance 
evaluation with ensemble learning. *2011 IEEE 11th International Conference on Data Mining (pp. 31-
40). IEEE. *

[3] Belkin, M., Niyogi, P., Sindhwani, V. (2006) Manifold regularization: A geometric framework for 
learning from labeled and unlabeled examples. *Journal of Machine Learning Research*, 7:2399–2434. 

[4]  Bellal,  F.,  Elghazel,  H.,  &  Aussem,  A.  (2012).  A  semi-supervised  feature  ranking  method  with 
ensemble learning. *Pattern Recognition Letters*, 33(10), 1426-1433. 

[5] Breiman, L. (2001). Random forests. *Machine learning*, 45, 5-32. 

[6]  Cheng, H., Deng,  W., Fu, C., Wang, Y., & Qin, Z. (2011).  Graph-based semi-supervised  feature 
selection with application to automatic spam image identification, *Computer Science for Environmental 
Engineering and EcoInformatics: International Workshop, CSEEE 2011*, Kunming, China, July 29-31, 
2011, *Proceedings, Part II (pp. 259-264). Springer Berlin Heidelberg.* 

[7] He, X., Cai, D., Niyogi, P. , (2005). Laplacian score for feature selection, *Proceedings of the 18th 
International Conference on Neural Information Processing Systems (NIPS'05)*. *MIT Press*, Cambridge, 
MA, USA, 507–514. 

[8] Han, Y., Park, K., & Lee, Y. K. (2011). Confident wrapper-type semi-supervised feature selection 
using an ensemble classifier. *2011 2nd International Conference on Artificial Intelligence, Management 
Science and Electronic Commerce (AIMSEC) (pp. 4581-4586). IEEE*. 

[9] Kalakech, M., Biela, P., Macaire, L., & Hamad, D. (2011). Constraint scores for semi-supervised 
feature selection:A comparative study. *Pattern Recognition Letters*, 32(5), 656-665. 

[10] Ren, J., Qiu, Z., Fan, W., Cheng, H., & Yu, P. S. (2008). Forward semi-supervised feature selection. 
*Advances  in  Knowledge  Discovery  and  Data  Mining:  12th  Pacific-Asia  Conference,  PAKDD  2008 
Osaka, Japan, May 20-23, 2008 Proceedings 12 (pp. 970-976). Springer Berlin Heidelberg. *

[11] Xu, Z., King, I., Lyu, M. R. T., & Jin, R. (2010). Discriminative semi-supervised feature selection 
via manifold regularization. *IEEE Transactions on Neural networks*, 21(7), 1033-1047. 

[12] Yang, M., Chen, Y. J., Ji, G. L. (2010). Semi_Fisher Score: A semi-supervised method for feature 
selection. *2010 International Conference on Machine Learning and Cybernetics (Vol. 1, pp. 527-532). 
IEEE. *

[13] Zhao, Z., Liu, H. (2007). Semi-supervised feature selection via spectral analysis, *Proceedings of 
the  2007  SIAM  international  conference  on  data  mining (pp.  641-646).  Society  for  Industrial  and 
Applied Mathematics. *

[14] Zhao, J., Lu, K., & He, X. (2008). Locality sensitive semi-supervised feature lection. 
*Neurocomputing*, 71(10-12), 1842-1849. 

[15] Zhang, D., Chen, S., & Zhou, Z. H. (2008). Constraint score: A new filter method for feature 
selection with pairwise constraints, *Pattern Recognition*, 41(5), 1440-1451.

### Etat de l'art 3 : Sélection de variable pour le multi-label & multi-label partiel
Voir Etat de l'art (C). 
