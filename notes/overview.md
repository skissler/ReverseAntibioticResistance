# 31 March 2026 

## Literature review: evidence for anti-correlated use/resistance relationships

### Antibiotic use disparities by race/ethnicity in the US

Olesen et al. (2018, *Emerging Infectious Diseases*; https://wwwnc.cdc.gov/eid/article/24/11/18-0762_article) used the Medical Expenditure Panel Survey (MEPS) to show that White persons reported approximately twice as many antimicrobial prescription fills per capita as non-White persons in 2014-2015. This is the key paper establishing the use side of the paradox in the US context.

### Resistance disparities: per capita incidence

The strongest evidence for anti-correlated use/resistance comes from MRSA. Petit et al. (2018, *Clinical Infectious Diseases*; https://pmc.ncbi.nlm.nih.gov/articles/PMC6232852/) found that Black persons had 3.57x higher per capita incidence of invasive MRSA than White persons (2005-2014 EIP data). The disparity held across all epidemiologic classes: hospital-onset (RR 3.20), healthcare-associated community-onset (RR 3.84), and community-associated (RR 2.78). Despite overall MRSA rates declining substantially over the study period, the racial gap did not narrow. Critically, these are reported as **per capita incidence rates** (cases per 100,000 population).

For *S. pneumoniae*, Nkwata et al. (2024, *Clinical Infectious Diseases*; https://academic.oup.com/cid/article/79/2/305/7628878) found that higher social vulnerability (measured by the CDC's Social Vulnerability Index) was associated with increased antimicrobial resistance, with socioeconomic status and household characteristics being the most closely associated SVI themes.

### Resistance disparities: per-infection resistance fraction

The disparities literature and the resistance surveillance literature exist largely in parallel. Surveillance systems like ABCs collect both race/ethnicity data and resistance proportions, and hospital antibiograms routinely report % resistant isolates — but these two data streams are almost never cross-tabulated by race/ethnicity. The disparities literature reports per capita incidence of resistant infections by race; the microbiology surveillance literature reports resistance proportions by geography or time. The result is that the question most relevant to our mechanism taxonomy — does the resistance *fraction* differ between populations? — is rarely directly addressed, even though the data to answer it likely exist within systems like ABCs/EIP.

That said, where resistance fractions *have* been reported alongside demographic data, the results are informative:

**S. pneumoniae — the resistance fraction went in the *expected* direction.** Talbot et al. (2004, *Pediatrics*; https://pubmed.ncbi.nlm.nih.gov/15295222/) found that before PCV7, **a higher percentage of pneumococcal isolates from White patients were antibiotic-nonsusceptible** than from Black patients. By 2002 (post-PCV7), resistance proportions converged across races. This means the per capita anti-correlation for pneumococcus — more resistant IPD per 100,000 in Black populations — was entirely driven by higher overall IPD rates (the "trivial" differential infection rate mechanism), not by a higher resistance fraction. The resistance fraction actually went in the direction predicted by antibiotic use patterns.

**S. aureus — hints of a higher MRSA fraction in Black populations, but from carriage data.** NHANES 2001-2004 data (https://pmc.ncbi.nlm.nih.gov/articles/PMC1467003/) showed overall *S. aureus* nasal carriage was lower in Black individuals (~25%) than White individuals (~33%), but MRSA carriage was roughly similar (~1.1% vs ~0.9% in 2001-02; both 1.6% in 2003-04). This means the MRSA fraction *among S. aureus carriers* was modestly higher in Black individuals (~4.4% vs ~2.7% in 2001-02), though the absolute MRSA carriage rates were close and converged at the later time point. These are colonization data, not invasive infection data, so the relevance to clinical resistance fractions is uncertain. Critically, I could not find a published analysis of total invasive *S. aureus* (MRSA + MSSA) incidence by race from the EIP data — computing the invasive MRSA fraction by race from the Petit et al. MRSA incidence data would require a denominator of total *S. aureus* invasive disease by race, which does not appear to have been reported in the same cross-tabulated form.

See et al. (2017, *Clinical Infectious Diseases*; https://academic.oup.com/cid/article/64/5/597/3002713) found that **91% of the racial disparity in CA-MRSA per capita rates was explained by census tract-level socioeconomic factors** (medically underserved area designation, education, income, housing value, rural status). This is compatible with the interpretation that higher overall infection burden — driven by crowding, poverty, and healthcare access barriers — accounts for most of the per capita disparity, without necessarily requiring a higher resistance fraction per infection. However, the socioeconomic mediators identified (crowding, underserved areas) could plausibly affect both total infection burden *and* the resistance fraction (e.g., through healthcare-associated acquisition or transmission intensity), so this finding alone does not resolve the question.

### Use-resistance associations across bug/drug combinations

Olesen et al. (2018, *eLife*; https://elifesciences.org/articles/39435) examined the association between antibiotic use patterns and resistance across 72 pathogen-antibiotic combinations in the US. Correlation coefficients ranged from -32% to +64%, meaning some bug/drug pairs showed negative associations between use and resistance. They also found that broadly distributed low-intensity use had a stronger association with resistance than concentrated repeated use — relevant to the subtherapeutic exposure mechanism.

### International patterns

At the country level, LMICs have lower per capita antibiotic consumption but bear a disproportionate share of AMR mortality. However, this is heavily confounded by sanitation infrastructure, infection control capacity, diagnostic access, and treatment quality, making it difficult to isolate a clean use-resistance paradox.

### Measurement framework

A 2024 Lancet Infectious Diseases commentary (https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(24)00485-7/abstract) argues that resistance reported as proportions vs. incidence tells fundamentally different stories, and that presenting them in isolation is misleading. This directly supports the need to distinguish per capita from per-infection metrics in our framework.

### Summary and implications for this project

The empirical evidence for anti-correlated use/resistance relationships is real but underspecified. The per capita pattern (lower use, higher resistant infection rates) is well-documented for MRSA and emerging for *S. pneumoniae*. But the field has not cleanly separated this into two components: (1) differential total infection burden, and (2) differential resistance fraction per infection. Determining which mechanisms are in play — and whether non-trivial mechanisms are needed at all — depends critically on this distinction.

Where the resistance fraction has been examined, the results are organism-specific:

- For *S. pneumoniae*, the anti-correlation in per capita rates is fully explained by differential infection rates (the "trivial" mechanism). The resistance fraction was actually higher in the high-use (White) population, consistent with the standard use→resistance model.
- For *S. aureus*/MRSA, the question is genuinely open. The per capita disparity is large (RR ~3.5) and mostly explained by socioeconomic factors (See et al.), consistent with a trivial mechanism. But NHANES carriage data hint at a modestly higher MRSA fraction among Black *S. aureus* carriers, which would implicate non-trivial mechanisms. The data to definitively answer this — total invasive *S. aureus* incidence by race alongside MRSA incidence — likely exist within ABCs/EIP but have not been published in the necessary cross-tabulation.

A key structural observation is that resistance surveillance systems routinely collect both resistance proportions and demographic data, but these are almost never cross-tabulated. The disparities literature and the resistance surveillance literature run in parallel without addressing the question most relevant to mechanism identification. Pointing out this gap — and that existing data could close it — is itself a contribution of this project.

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

### Intensive vs. extensive use 

If the balance of intensive vs. extensive use differs between populations in ways that go against the overall volume of antibiotic consumption, then we might expect anti-correlated use/resistance relationships. In other words, if the high-use population mainly has consumption concentrated in a few individual, while the low-use population has consumption scattered across many, this could drive higher resistance rates in the low-use population. 

### Reverse causation 

Maybe antibiotic use is caused by resistance -- but resistance (and infections overall) is under-treated in the low-use group. 

# 1 Apr 2026

An alternative framing: **when does the use-resistance relationship break down**? 

Instead of "what explains anti-correlated use/resistance?", the question becomes: "under what conditions should we expect antibiotic use and resistance to be correlated, uncorrelated, or anti-correlated across populations?" That's defensible regardless of whether the specific US racial disparity case turns out to involve a true resistance-fraction anti-correlation. The Olesen eLife paper already showed correlation coefficients ranging from -32% to +64% across bug/drug pairs — so negative ecological associations do exist for some combinations,  even if not stratified by race. Your mechanism taxonomy would predict which conditions flip the sign, and you'd be building general theory rather than explaining one possibly-artifactual observation.

Alternatively: an empric-first approach: 

The cross-tabulation that's missing — resistance fractions by race from ABCs/EIP data — is not a heroic data collection effort. It's a question that existing surveillance data can likely answer. If you can get access to ABCs data (or collaborate with someone at CDC/EIP who has it), you could compute the MRSA fraction of invasive S.  aureus by race, and the nonsusceptible fraction of S. pneumoniae by race in the post-PCV13 era. That empirical finding paired with the theoretical framework is a much stronger paper than either alone. If the resistance fraction is anti-correlated, you have a phenomenon and a set of candidate mechanisms. If it isn't, you've shown that the paradox dissolves under the right metric — which is also a publishable and useful result, and your mechanism taxonomy explains why it dissolves. Look for information in the ABCs/EIP data from CDC, or hospital-level information. 









