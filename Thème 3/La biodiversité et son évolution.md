# La biodiversité et son évolution.


### I : Estimer la biodiversité d’un milieu.

La biodiversité est la diversité du vivant. Elle peut se définir à différentes [échelles](https://github.com/YannBouyeron/SVT2/blob/master/Thème-1/Biodiversité%2C%20résultat%20et%20étape%20de%20l'évolution.md):


La biodiversité englobe différentes composantes mesurables:

- La **richesse spécifique** représente le nombre d’espèces dans un milieu. Elle peut être estimée par des techniques d’échantillonnages: observations, écoutes, piégeages, prélèvements d’ADN environnemental.

- **L’équitabilité** estime si l’abondance entre chaque espèce est équilibrée.

- **L’abondance** représente le nombre d’individus d’une espèce donnée dans une population. 


L’abondance peut être mesurée par des observations directes ou indirectes pour les gros animaux, ou par la méthode de **capture-marquage-recapture** pour les espèces plus difficiles à compter.

La méthode de **capture-marquage-recapture** est une méthode permettant d’estimer un effectif à partir d’échantillons. Si on suppose que la proportion d’individus marqués est identique dans l’échantillon de recapture et dans la population totale, l’effectif de la population peut alors être calculé par proportionnalité: **N = M x C / R**

*(N: effectif de la population, M: nombre d’individus marqués, C: nombre d’individus recapturés, R: nombre d’individus marqués recapturés)*

La taille limitée des échantillons induit cependant une **fluctutation d’échantillonnage** (l’échantillon recapturé n’est pas toujours représentatif de la population) d’autant plus marquée que l’échantillon est petit. Cette fluctuation peut être mesurée par **l’écart type** qui permet de calculer **l’intervalle de confiance** au sein duquel on espère que l’effectif de la population se trouve.

**L’écart type** S d’une proportion P d’un caractère donné dans un échantillon de taille finie C est donné par la formule suivante: **S = (P * (1 - P) / C)<sup>0,5</sup>**

Les différentes [simulations](https://ipfs.io/ipfs/QmcSCvBgH72LB3HpfgdE3tasbTRaVPXbYJ7BoJthkUwxGL) montrent que:

- Plus la taille des échantillons est faible, plus l’écart type est grand (et inversement).
- Plus le nombre d’échantillons étudiés est grand plus l’écart type mesuré se rapproche de l’écart type théorique donné par la formule précédente.

La proportion P du caractère et l’écart type S permettent de construire un **intervalle de confiance** qui inclut la proportion P ou l’effectif N avec un **niveau de confiance** (probabilité que P ou N soient inclus dans l’intervalle) donné.

Ainsi, pour un **niveau de confiance** de 95%, **l’intrevalle de confiance de P** (P = la proportion du caractère) est: [P - 2 * S , P + 2 * S], et **l’intervalle de confiance de N** (N = l’effectif estimé de la population) est [M / (P + 2 * S) , M / (P - 2 * S)].
 


<p align=center><strong>Application aux anophèles burkinabés (<a href="https://ipfs.io/ipfs/QmPRwbpbQu818JUHNqrqP4djSCysDeAZkprNy2K9bNgoJU">document 3 page 196</a>)</strong></p>
<div align=center><table width=100%>
<tr><th></th><th>Saison humide</th><th>Saison sèche</th></tr>
<tr><th>M</th><td>3407</td><td>5267</td></tr>
<tr><th>C</th><td>5843+44</td><td>363+49</td></tr>
<tr><th>R</th><td>44</td><td>49</td></tr>
<tr><th>P = R/C</th><td>0.007474</td><td>0.121890</td></tr>
<tr><th>S = (P * (1-P)/C)**0.5</th><td>0.001122</td><td>0.016317</td></tr>
<tr><th>IC de P à 95%</br>[P - 2 * S , P + 2 * S]</th><td>[0.005229, 0.009719]</td><td>[0.089256, 0.154524]</td></tr>
<tr><th>IC de N à 95%</br>[M / (P + 2 * S) , M / (P - 2 * S)]</th><td>[350543, 651557]</td><td>[34085, 59009]</td></tr>
</table></div>
