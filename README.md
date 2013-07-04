ethnic-surnames
===============

American Surnames by Country of Origin


[Census 2000 Genealogy Data: Frequently Occurring Surnames from Census 2000](http://www.census.gov/genealogy/www/data/2000surnames/index.html) 150K names with percentage white, black, asian, hispanic, two-race.

Useful links: http://www.archives.gov/research/alic/reference/ethnic-heritage.html

42K Surnames http://en.wikipedia.org/wiki/Category:Surnames

Useful links http://en.wikipedia.org/wiki/List_of_the_most_common_surnames_in_Europe

Ancestry http://factfinder2.census.gov/bkmk/table/1.0/en/ACS/11_5YR/B04001/0500000US17031.14000

If we assume that the conditional probability of a last name given a race or ethnicity is constant across the nation then

<a href="http://www.codecogs.com/eqnedit.php?latex=\begin{array}{rcl}&space;\Pr(\text{Black}&space;\mid&space;\text{Name},&space;\text{Chicago})&space;&=&&space;\frac{\Pr(\text{Black},&space;\text{Name},&space;\text{Chicago})}&space;{\Pr(\text{Black},&space;\text{Name},&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Black'},&space;\text{Name},&space;\text{Chicago})}\\&space;&=&&space;\frac{\Pr(\text{Name}&space;\mid&space;\text{Black},&space;\text{Chicago})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})}&space;{\Pr(\text{Name}&space;\mid&space;\text{Black},&space;\text{Chicago})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Name}&space;\mid&space;\text{Black'},&space;\text{Chicago})&space;\Pr(\text{Black'}&space;\mid&space;\text{Chicago})}\\&space;&=&&space;\frac{\Pr(\text{Name}&space;\mid&space;\text{Black})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})}&space;{\Pr(\text{Name}&space;\mid&space;\text{Black})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Name}&space;\mid&space;\text{Black'})&space;\Pr(\text{Black'}&space;\mid&space;\text{Chicago})}\\&space;\end{array}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\begin{array}{rcl}&space;\Pr(\text{Black}&space;\mid&space;\text{Name},&space;\text{Chicago})&space;&=&&space;\frac{\Pr(\text{Black},&space;\text{Name},&space;\text{Chicago})}&space;{\Pr(\text{Black},&space;\text{Name},&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Black'},&space;\text{Name},&space;\text{Chicago})}\\&space;&=&&space;\frac{\Pr(\text{Name}&space;\mid&space;\text{Black},&space;\text{Chicago})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})}&space;{\Pr(\text{Name}&space;\mid&space;\text{Black},&space;\text{Chicago})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Name}&space;\mid&space;\text{Black'},&space;\text{Chicago})&space;\Pr(\text{Black'}&space;\mid&space;\text{Chicago})}\\&space;&=&&space;\frac{\Pr(\text{Name}&space;\mid&space;\text{Black})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})}&space;{\Pr(\text{Name}&space;\mid&space;\text{Black})&space;\Pr(\text{Black}&space;\mid&space;\text{Chicago})&space;&plus;&space;\Pr(\text{Name}&space;\mid&space;\text{Black'})&space;\Pr(\text{Black'}&space;\mid&space;\text{Chicago})}\\&space;\end{array}" title="\begin{array}{rcl} \Pr(\text{Black} \mid \text{Name}, \text{Chicago}) &=& \frac{\Pr(\text{Black}, \text{Name}, \text{Chicago})} {\Pr(\text{Black}, \text{Name}, \text{Chicago}) + \Pr(\text{Black'}, \text{Name}, \text{Chicago})}\\ &=& \frac{\Pr(\text{Name} \mid \text{Black}, \text{Chicago}) \Pr(\text{Black} \mid \text{Chicago})} {\Pr(\text{Name} \mid \text{Black}, \text{Chicago}) \Pr(\text{Black} \mid \text{Chicago}) + \Pr(\text{Name} \mid \text{Black'}, \text{Chicago}) \Pr(\text{Black'} \mid \text{Chicago})}\\ &=& \frac{\Pr(\text{Name} \mid \text{Black}) \Pr(\text{Black} \mid \text{Chicago})} {\Pr(\text{Name} \mid \text{Black}) \Pr(\text{Black} \mid \text{Chicago}) + \Pr(\text{Name} \mid \text{Black'}) \Pr(\text{Black'} \mid \text{Chicago})}\\ \end{array}" /></a>

where 

<a href="http://www.codecogs.com/eqnedit.php?latex=\Pr(\text{Name}&space;\mid&space;\text{Black})&space;=&space;\frac{\Pr(\text{Black}&space;\mid&space;\text{Name})\Pr(\text{Name})}{\Pr(\text{Black})}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\Pr(\text{Name}&space;\mid&space;\text{Black})&space;=&space;\frac{\Pr(\text{Black}&space;\mid&space;\text{Name})\Pr(\text{Name})}{\Pr(\text{Black})}" title="\Pr(\text{Name} \mid \text{Black}) = \frac{\Pr(\text{Black} \mid \text{Name})\Pr(\text{Name})}{\Pr(\text{Black})}" /></a>

* Can we get org-chart info added to budget positions? https://data.cityofchicago.org/Administration-Finance/Budget-2012-Budget-Ordinance-Positions-and-Salarie/4n2t-us8h?
* Can we get race/ethnic estimates for all employees

Previous literature
http://www.aaai.org/ocs/index.php/ICWSM/ICWSM10/paper/viewFile/1534/1828
http://www.publicprofiler.org/contact.php
http://www.cs.sunysb.edu/~skiena/lydia/names.pdf with working code http://www.textmap.com/ethnicity

http://www.personal.psu.edu/users/p/x/pxt162/papers/treeratpituk-aaai12.pdf
