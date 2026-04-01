# 31 March 2026 

## The problem setup:

In general, we know that antibiotic use contributes to antibiotic resistance. However, some evidence indicates that rates of antibiotic resistance do not neatly follow antibiotic consumption: for exmaple, for some infections, antibiotic resistance rates are higher in U.S. BIPOC populations than in White populations, despite higher antibiotic use in White individuals. 

The goal of this project is to identify and model the mechanisms that could lead to antibiotic resistance rates that go against the antibiotic use gradient. By modeling these mechanisms, we can potentially determine how much each might contribute to anti-correlated use-resistance relationships, and which mechanisms are the most plausible for specific bug/drug combinations. 

To keep things general, we will consider two populations, differentiated based on their antibiotic use -- we will call them the "high-use" and "low-use" populations. 

Some mechanisms include: 

### Differential infection rates 

If disease transmission rates are higher in the low-use population, we would expect a higher incidence of disease overall. Naively, I expect that we would see higher rates per capita of antibiotic resistance, but the rate of antibiotic resistance per infection should not differ between the two populations. In other words: some proportion $p_{\text{res}}$ of strains are reistant. In both populations, a fraction of $p_{\text{res}}$ infections are resistant: but since the infection rate is higher in the low-use population, we see a higher per capita fraction of resistant infections, because there's simply a higher rate of infections overall. A trivial case. 

### Differential susceptibility to disease 

If the low-use population is more likely to develop disease given infection, then the same logic as in the previous section is in play, even if rates of infection are the same. Again, fairly trivial. 

### Cross-population seeding

Things get more interesting when we consider mechanisms by which the low-use population might have a higher rate *per infection* of resistant infections. I think that if we consider only a single bug/drug combination, we shouldn't be able to get anti-correlated use-resistance relationships. But, if we consider multiple bugs and drugs (maybe two of each), such relationships could in theory arise. Consider a microbe that is commensally carried most of the time and undergoes exposure to antibiotics as a bystander -- *S. pneumoniae* is a good example. The high-use population drives up resistance in *S. pneumoniae*, but also is more likely to get an antibiotic that clears it, whether in response to *S. pneumoniae*-caused disease or due to antibiotic treatment for something else that clears carriage. The resistant microbes make their way into the low-use population, where antibiotic consumption rates are lower, so the infections -- resistant or not -- are less likely to be cleared. In other words, there's a rapid turnover of resistant infections in the high-use population, leading to high incidence of resistance but low prevalence. This high incidence spills over into the low-use population, where lower rates of getting antibiotics and barriers to care allow resistant infections to proliferate at a higher prevalence than in the high-use population.

### Subtherapeutic exposure / quality of use

The low-use population may have lower *measured* use but different *quality* of use -- incomplete courses, shared leftover antibiotics, over-the-counter access in some contexts, or subtherapeutic dosing. Subtherapeutic concentrations are particularly effective at selecting for resistance. So the selection pressure per unit of measured consumption could be higher in the low-use population. This mechanism challenges the measurement itself: the relevant quantity may not be total antibiotic consumption but rather the fraction of exposures that fall in the sub-MIC selection window.

### Environmental reservoirs

The low-use population might have disproportionate exposure to resistant organisms through non-human channels -- proximity to agricultural operations using antibiotics, contaminated water sources, or food supply differences. This would generate resistance independent of human prescribing patterns and could decouple observed resistance from measured clinical antibiotic use.

### Surveillance / ascertainment bias

If the low-use population interacts with healthcare less frequently, cultures may be obtained only for severe or treatment-refractory infections -- which are enriched for resistance. The high-use population may get cultured more routinely (including mild infections), diluting the observed resistance fraction. This is a measurement artifact rather than a biological mechanism, but it is important to address since it could confound the empirical signal.

### Healthcare-associated acquisition

If the low-use population, when it does access healthcare, disproportionately encounters settings with high resistant organism burden (overcrowded emergency departments, under-resourced facilities), healthcare contact itself becomes a source of resistant organism acquisition -- decoupled from that individual's own antibiotic use.

### Co-selection and linked resistance

Resistance to antibiotic A can be genetically linked to resistance to antibiotic B (same plasmid, co-selected loci). If the two populations use different antibiotic classes, resistance patterns could be driven by selection pressures from the *other* population's preferred antibiotic, then transmitted across populations. This operates at the genetic linkage level rather than the organism level.

