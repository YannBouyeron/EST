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

Les différentes [simulations](https://ipfs.io/ipfs/QmWuWtjd4XPQ2cN5173UeGAoF5Nbxu2hENXxQ99z3pvhnX) montrent que:

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








### II: L’évolution de la composition génétique des populations.

Une population est un ensemble d’individus appartenant à une même espèce, peuplant un même espace géographique, et ayant tendance à se reproduire davantage entre eux plutôt que avec les individus des autres populations. Les populations comprennent des individus qui diffèrent par leur patrimoine génétique et par leurs caractères. Cette diversité observée ne représente qu'une infime partie de la diversité créée par les mécanismes évoqués précédemment.  


##### L’équilibre de Hardy & Weinberg.

Proposée en 1908 indépendamment par le mathématicien anglais Hardy et le médecin allemand Weinberg, la loi de Hardy-Weinberg se définit ainsi : dans une population de grand effectif, où les unions se font au hasard (= panmixie), où il n’existe ni migration, ni sélection naturelle, et en l’absence de mutations, les fréquences des différents génotypes et les fréquences alléliques restent constantes d’une génération à l’autre. 

<p align=center><i>Soient p la fréquence de l’allèle A et q la fréquence de l’allèle p : p+q =1</i></p>
<p align=center><i>(q est en général utilisé pour désigner l’allèle conférant le caractère récessif).</i></p>

<div align=center><a href="https://ipfs.io/ipfs/QmUEs9XdmoBLw6QbtCwY6GHGJ24SpwXRPZfR1FAVE1MuqK"><img src="https://ipfs.io/ipfs/QmUEs9XdmoBLw6QbtCwY6GHGJ24SpwXRPZfR1FAVE1MuqK" width=60%></a></div>

La structure génétique d’une population est définie alors par la fréquence des allèles et son évolution au cours des générations. Selon le modèle de Hardy-Weinberg, cette structure génétique est stable. Or, dans les populations réelles, différents facteurs empêchent généralement d’atteindre cet équilibre. 

##### Les écarts à l’équilibre de Hardy & Weinberg.

**La dérive génétique** est l'évolution d'une population causée par des phénomènes aléatoires et imprévisibles comme la rencontre aléatoire des gamètes lors de la fécondation. La dérive génétique concerne surtout les allèles neutres c’est-à-dire qui ne confèrent ni avantage ni désavantage sélectif.

Les effets de la dérive génétique sont d'autant plus importants que la population est petite. En effet, le petit nombre de géniteurs et/ou de descendants fait que statistiquement certains allèles ne seront pas transmis, tandis que dans une population de grande dimension (au moins plusieurs milliers d’individus), où les rencontres entre reproducteurs se font au hasard, les fréquences des allèles sont généralement stables.

La dérive génétique conduit donc, de façon aléatoire, à l'augmentation ou à la diminution de la fréquence des différents allèles et ainsi à une diminution de la diversité génétique d'une population.



**La sélection naturelle** est une modification de la fréquence des phénotypes par les conditions du milieu dans lequel vit une population. En fonction d'un contexte écologique précis (pression du milieu, compétition entre êtres vivants...) certains phénotypes peuvent conférer un avantage ou un désavantage: le milieu exerce une sélection des phénotypes.

Dans un contexte donné, les individus possédant un phénotype conférant un avantage sélectif ont plus de chances de survie et se reproduisent davantage que ceux présentant un phénotype conférant un désavantage sélectif.

La conséquence est la variation des fréquences alléliques au sein des populations: un phénotype conférant un avantage, permet une meilleure reproduction et donc une meilleure transmission des allèles favorables dont la fréquence augmente, augmentant ainsi la fréquence du phénotype conférant l'avantage. Et inversement pour les allèles défavorables qui, moins transmis, tendent à être éliminés de la population.

Dans le cas de la séléction naturelle on observe un excès d’individus présentant le (ou les) phénotypes avantageux , et un déficit d’individus présentant le (ou les) phénotypes désavantageux par rapport à l’équilibre de Hardy & Weinberg

**Appariements non aléatoires:**

On appelle ici appariement la rencontre entre deux individus de sexes différents, un mâle et un femelle. Pour que le modèle de Hardy & Weinberg reste valide, il faut que la rencontre entre deux individus mâle et femelle reste aléatoire : on
parle alors d’appariement aléatoire ou panmixie.

Cependant, il peut y avoir au sein des populations des appariements non aléatoires. C’est le cas par exemple lorsque :

- les individus ont tendance à choisir des individus géographiquement plus proches : dans de nombreuses populations les accouplements avec des individus proches sont plus fréquents qu’avec des individus plus éloignés. 

- un choix du partenaire s’effectue en fonction du phénotype ou encore chez certaines espèces animales, seuls quelques mâles ont accès aux femelles.

- la fécondation croisée ne peut avoir lieu et l’autofécondation s’effectue : c’est le cas par exemple chez certaines plantes, les deux partenaires sont alors génétiquement identiques.

- deux individus proches parents s’accouplent, dans ce cas les deux partenaires sont plus similaires génétiquement que deux individus choisis au hasard.

**Les mutations:**

Certaines mutations génétiques, affectant les cellules de la lignée germinale peuvent introduire de nouveaux allèles dans la population et se transmettre ainsi à la descendance. La mutation d’un gène au sein d’une population modifie alors la fréquence des allèles existant et ainsi la fréquence des génotypes.

**Les migrations:**

Dans la plupart des situations réelles la migration d’individus peut faire entrer de nouveaux allèles au sein d’une population. De même, le départ d’individus peut modifier la structure génétique de la population dont ils sont issus. Les migrations ont donc pour conséquence des flux de gènes entre différentes populations et entraînent des modifications des fréquences alléliques.

La formation et le devenir d’une petite population de migrants fait intervenir deux phénomènes: lorsqu’une petite population est issue d’une population plus grande, elle ne possède pas la diversité génotypique ni allélique de la grande population. C’est ce qu’on appelle **l’effet fondateur**. Les fréquences alléliques sont donc modifiées. Ensuite, au sein de la petite population migrante, la dérive génétique modifie encore davantage les fréquences alléliques, ce qui produit des éliminations (fréquence de l’allèle = 0%) et des fixations (fréquence de l’allèle = 100%) d’allèles. 

*⚠️ Les migrations saisonnières (d’une aire d’hivernage vers une aire de reproduction ou inversement) n’ont pas d’impacts sur la composition génétique de la population.*
