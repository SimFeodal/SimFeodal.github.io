# SimFeodal
## Agent-based modelling to explore the combined effects of social and demographic changes on rural settlement patterns in North-Western Europe during the Middle Ages (800 CE to 1200 CE)

**The agent-based model SimFeodal simulates the emergence of enduring population clusters located around the castles and the churches in a rural region during the Middle Ages.**  In the course of time, population clusters (hamlets, villages, small towns) become more numerous; many of them grow (i. e. their number of peasant households increases) but some clusters grow more than others.


### Historical context

Around the year 800 CE, the Carolingian Empire reached its greatest territorial extent, covering a large swathe of Europe from the Ebro to the Elbe. Regionally, settlement patterns were a mix of small scattered villages (loose clusters of a few houses) and isolated farmsteads. Villages and farms were impermanent and their location often shifted by a few tens of metres to several hundred metres every one or two centuries. In this period, towns were civitas capitals inherited from Antiquity. Some served a central function as episcopal sees but their economic and administrative role was minor.

By about the year 1200 CE, the piecemeal dismantling of the Carolingian Empire was complete. Regional settlement patterns were by then composed of more permanent population clusters around castles and churches. Population clusters (hamlets, villages and towns) were more numerous and more stable than in 800 CE. The towns that had existed in 800 CE had grown much larger having developed productive and commercial activities and new nuclei had formed around suburban monasteries. Many small towns had emerged around castles or rural monasteries ringed by their own precinct walls.

Thus what had been a dispersed regional settlement pattern in 800 CE had become much more concentrated and hierarchical by 1200 CE. This phenomenon occurred throughout North-Western Europe but the degree of concentration and hierarchy differed markedly. A combination of several processes can explain this major transition.
    • The dismantling of the Carolingian Empire and the dissipation of power induced struggles among lords and so an upsurge of violence. This produced a spate of castle-building and an increased need of protection for peasant households.
    • The militarisation of society heightened the lords’ needs for both money and fighting men. This initiated the “feudal revolution” of the eleventh century, when ever lesser lords appropriated various administrative, fiscal and judicial rights for themselves and their vassals with an ensuing surge in usage fees and rents paid by peasant households to their lords.
    • Peasant households organised themselves into village communities so as to boost their productivity and counterbalance the power of their lords.
    • Religious control over society strengthened considerably, especially as a result of the Gregorian Reform. This led to the development of pastoral care, more parish churches and higher usage fees and rents paid by peasant households to the Church.


### Modelled entities

| Name  | Description | Level |
| ------------- | ------------- | ------------- |
| Peasant households | Most of them can move locally and at long distances but others are so dependent on their lord that they cannot leave his estates (serfs, slaves)| Micro-geographic |
| Lords  | Overlords (princes, counts) and small lords (castellans, knights, etc.) do not have the same behaviour rules | Micro-geographic |
| Tax areas  | Each tax area refers to one type of rights: rents, high justice rights, other rights (low justice rights, usage rights) | Micro-geographic |
| Attractive points  | Parish churches, castles, village communities  |  Micro-geographic |
| Population clusters  | Aggregation of neighbouring peasant households and attractive points |  Meso-geographic |
| Attraction centres  | Aggregation of neighbouring attractive points |  Meso-geographic |

### Relocation process of a peasant household in SimFeodal

![Relocation process of a peasant household](PH-movingrules.png)

### Authorship
- Robin Cura (research laboratory Géographie-cités, Paris, France)
- Cécile Tannier (research laboratory ThéMA, Besançon, France)
- Samuel Leturcq (research laboratory CITERES, Tours, France)
- Elisabeth Zadora-Rio (research laboratory CITERES, Tours, France)
- Xavier Rodier (research laboratory CITERES, Tours, France)
- Elisabeth Lorans (research laboratory CITERES, Tours, France)

SimFeodal has been created as part of both the research projet TransMonDyn (2011-2014) and the PhD thesis of Robin Cura.
