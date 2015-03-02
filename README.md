Prostate cancer screening with prostate-specific antigen
=================================

A data-only living systematic review

**Clinical summary:** This meta-analysis suggests that clinical intervention *is* effective. Metaregression indicates a correlation between the benefit of screening and the intensity of testing with the prostate-specific antigen. In the trial with the most intensive testing, the number need to screen to prevent one death from prostate cancer was 194. 

**Methods overview:** This repository is an [openMetaAnalysis](https://openmetaanalysis.github.io/) that updates a previously published meta-analysis.(1) Newer studies included are listed in the references below. Rationale for newer trials excluded may be listed at the end of the references. 

This repository is a limited review and contains outcomes data only without PICO and Risk of Bias Tables.  This review does not include a GRADE Profile or Summary of Findings Table.

See [methods](http://openmetaanalysis.github.io/methods.html) for details.

Calculation of PSA test intensity.
 * Test intensity = A * 1/B * (C - D)
  * A = years of testing in the trial
  * B = years between tests
  * C = rate of testing in the screening group
  * D = rate of testing in the control group


| Trial               | A  | B |  C  |  D | Intensity
| ------------------- |:--:|:-:|:---:|:---:|:---
| PLCO                |  4 | 1 | 85% | 50% | 1.4 (estimtated with formula above)
| ERSPC - not Göteborg| 13 | 4 | 60% | ?   | 2.1 (ERSPC. 2014. Reported in Table 1.<br>Assumes rate = 0% in controls)
| ERSPC - Göteborg    | 13 | 2 | 55% | ?   | 3.4 (ERSPC. 2014. Reported in Table 1.<br>Assumes rate = 0% in controls)
  

**Results:** Details of the studies included are in the:
* [Explanation of Göteborg data](../../issues/1)
* [Forest plots](../../tree/master/forest-plots) ([source data](../../tree/master/data))

The forest plot for the primary outcome is below. Additional [forest plots](../../tree/master/forest-plots) of secondary analyses may be available. 
![Principle results](https://raw.githubusercontent.com/openMetaAnalysis/Prostate-cancer-screening-with-prostate-specific-antigen/master/forest-plots/Outcome-Primary.png "Principle results - forest plot")

The metaregression for the primary outcome is below. Additional [metaregression plots](../../tree/master/metaregression) may be available.
![Principle results](https://raw.githubusercontent.com/openMetaAnalysis/Prostate-cancer-screening-with-prostate-specific-antigen/master/metaregression/Outcome-Primary.png "Principle results - metaregression")

References:
----------------------------------

### Systematic review(s)
####Most recent review at time of last revision of this repository
1. Qaseem A, Barry MJ, Denberg TD, Owens DK, Shekelle P; Clinical Guidelines Committee of the American College of Physicians. Screening for prostate cancer: a guidance statement from the Clinical Guidelines Committee of the American College of Physicians. Ann Intern Med. 2013 May 21;158(10):761-9. doi: 10.7326/0003-4819-158-10-201305210-00633. PMID: [23567643](http://pubmed.gov/23567643).
2. Chou R, Croswell JM, Dana T, Bougatsos C, Blazina I, Fu R, Gleitsmann K, Koenig HC, Lam C, Maltz A, Rugge JB, Lin K. Screening for prostate cancer: a review of the evidence for the U.S. Preventive Services Task Force. Ann Intern Med. 2011 Dec 6;155(11):762-71. doi: 10.7326/0003-4819-155-11-201112060-00375. PMID: [21984740](http://pubmed.gov/21984740).


### Randomized controlled trials
#### New trial(s) *not* included in the most recent review above
None

#### Trials included in the review above
1. Schröder FH, Hugosson J, Roobol MJ, Tammela TL, Zappa M, Nelen V, Kwiatkowski M, Lujan M, Määttänen L, Lilja H, Denis LJ, Recker F, Paez A, Bangma CH, Carlsson S, Puliti D, Villers A, Rebillard X, Hakama M, Stenman UH, Kujala P, Taari K, Aus G, Huber A, van der Kwast TH, van Schaik RH, de Koning HJ, Moss SM, Auvinen A; ERSPC Investigators. Screening and prostate cancer mortality: results of the European Randomised Study of Screening for Prostate Cancer (ERSPC) at 13 years of follow-up. Lancet. 2014 Dec 6;384(9959):2027-35. doi: [10.1016/S0140-6736(14)60525-0](http://dx.doio.org/10.1016/S0140-6736(14)60525-0). PMID: [25108889](http://pubmed.gov/25108889).
2. Hugosson J, Carlsson S, Aus G, Bergdahl S, Khatami A, Lodding P, Pihl CG, Stranne J, Holmberg E, Lilja H. Mortality results from the Göteborg randomised population-based prostate-cancer screening trial. Lancet Oncol. 2010 Aug;11(8):725-32. doi: [10.1016/S1470-2045(10)70146-7](http://dx.doio.org/10.1016/S1470-2045(10)70146-7). PMID: [20598634](http://pubmed.gov/20598634); PMCID: [PMC4089887](http://pubmedcentral.gov/PMC4089887).
3. Schröder FH, Hugosson J, Roobol MJ, Tammela TL, Ciatto S, Nelen V, Kwiatkowski M, Lujan M, Lilja H, Zappa M, Denis LJ, Recker F, Berenguer A, Määttänen L, Bangma CH, Aus G, Villers A, Rebillard X, van der Kwast T, Blijenberg BG, Moss SM, de Koning HJ, Auvinen A; ERSPC Investigators. Screening and prostate-cancer mortality in a randomized European study. N Engl J Med. 2009 Mar 26;360(13):1320-8. doi: [10.1056/NEJMoa0810084](http://dx.doio.org/10.1056/NEJMoa0810084). PMID: [19297566](http://pubmed.gov/19297566)
4. Andriole GL, Crawford ED, Grubb RL 3rd, Buys SS, Chia D, Church TR, Fouad MN, Gelmann EP, Kvale PA, Reding DJ, Weissfeld JL, Yokochi LA, O'Brien B, Clapp JD, Rathmell JM, Riley TL, Hayes RB, Kramer BS, Izmirlian G, Miller AB, Pinsky PF, Prorok PC, Gohagan JK, Berg CD; PLCO Project Team. Mortality results from a randomized prostate-cancer screening trial. N Engl J Med. 2009 Mar 26;360(13):1310-9. doi: [10.1056/NEJMoa0810696](http://dx.doio.org/10.1056/NEJMoa0810696). PMID: [19297565](http://pubmed.gov/19297565); PMCID: [PMC2944770](http://pubmedcentral.gov/PMC2944770).

-------------------------------
[Cite and use this content](https://github.com/openMetaAnalysis/openMetaAnalysis.github.io/blob/master/reusing.MD)  - [Edit this page](../../edit/master/README.md) - [History](../../commits/master/README.md)  - 
[Issues and comments](../../issues?q=is%3Aboth+is%3Aissue)
