# Electoral Systems

Fields to define the parameters of the electoral system that you want to
analyse.
Note that System 2 will be disabled if the metric chosen above isn't meant to
compare two different systems.

Every electoral system is composed of the three following fields, to be
specified in the same order as below:

### Method

Given a region with an associated number of electoral seats or representatives
to be elected, a set of parties and a distribution of votes, the method
determines how the votes are distributed.
The following methods are currently supported:

- [d'Hondt method](https://en.wikipedia.org/wiki/D%27Hondt_method)

- [Sainte-Lague method](https://en.wikipedia.org/wiki/Webster/Sainte-Lagu%C3%AB_method)

- [LRM method (Hare quota)](https://en.wikipedia.org/wiki/Hare_quota)

- [LRM method (Droop quota)](https://en.wikipedia.org/wiki/Droop_quota)

- [LRM method (Hagenbach-Bischoff quota)](https://en.wikipedia.org/wiki/Hagenbach-Bischoff_quota)

- [LRM method (Imperiali quota)](https://en.wikipedia.org/wiki/Imperiali_quota)


### Region Level

The [administrative division level](https://en.wikipedia.org/wiki/Administrative_division)
of the electoral regions, with 0 representing country level.
You can find details about the administrative division levels of every country
[here](https://en.wikipedia.org/wiki/List_of_administrative_divisions_by_country).


### Threshold

Given an electoral region, the threshold determines the minimum percentage of
votes that a party needs to acquire in order to obtain seats in that particular
region. If you want the threshold to be applied at a country level instead of
a regional level, you need to toggle the 'Country' switch on.


## Electoral Systems by Country

- Costa Rica
  - Method: LRM (Hare Quota)
  - Level: 1
  - Threshold: n/2s (region level)

- Spain
  - Method: d'Hondt
  - Level: 2
  - Threshold: 3% (region level)

- USA
  - Method: Winner Takes All (1 rep/district)
  - Level: 2
  - Threshold: None
