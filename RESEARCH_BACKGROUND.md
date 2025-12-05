# Research Background: Cortisol, Caffeine, and Chronobiology in Mindful Coffee

> **Author:** Alexander Loth  
> **Affiliation:** Frankfurt University of Applied Sciences  
> **Date:** August 5, 2025  
> **Version:** 2.0

## Abstract

The [**Mindful Coffee**](https://apps.apple.com/us/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone) application integrates established principles from chronobiology, endocrinology, and pharmacokinetics to provide users with a physiologically-grounded model of their daily cortisol rhythm and its bidirectional interaction with caffeine metabolism. By mathematically modeling the Cortisol Awakening Response (CAR), diurnal cortisol decline, and caffeine's first-order elimination kinetics, the app enables evidence-based decision-making regarding caffeine consumption timing. This approach aims to optimize cognitive performance, support hypothalamic-pituitary-adrenal (HPA) axis homeostasis, and promote sleep hygiene in accordance with circadian principles. This document presents the scientific foundations, mathematical models, and peer-reviewed evidence underlying the app's cortisol and caffeine modeling features.

**Keywords:** cortisol awakening response, circadian rhythm, caffeine pharmacokinetics, chronobiology, HPA axis, sleep optimization, personalized health

## 1. Introduction: The Physiological Significance of Cortisol Rhythmicity

Cortisol, the primary glucocorticoid hormone in humans, is synthesized and secreted by the zona fasciculata of the adrenal cortex under regulation of the hypothalamic-pituitary-adrenal (HPA) axis. This hormone serves as a master regulator of numerous physiological processes, including gluconeogenesis, lipid metabolism, immune modulation, and the coordination of sleep-wake transitions (Nicolaides et al., 2015).

Cortisol secretion exhibits a robust **circadian rhythm** governed by the suprachiasmatic nucleus (SCN) of the hypothalamus, the body's central pacemaker. This rhythm is characterized by:

1. **Morning acrophase:** Peak levels occurring 30–45 minutes post-awakening
2. **Diurnal decline:** Progressive decrease throughout the day following an exponential decay pattern
3. **Nocturnal nadir:** Lowest concentrations in the early sleep period (approximately 2–4 hours after sleep onset)

This ultradian pulsatility superimposed on circadian variation was first systematically characterized by Weitzman et al. (1971) and has since been validated across diverse populations.

The clinical significance of cortisol rhythmicity extends beyond mere biomarker status. A robust diurnal cortisol slope (DCS)—defined as the rate of decline from morning peak to evening nadir—is independently associated with reduced all-cause mortality, improved cardiovascular outcomes, and better metabolic profiles (Adam et al., 2017). Conversely, a flattened or blunted DCS has been implicated in:

- Chronic fatigue syndrome and burnout (Chida & Steptoe, 2009)
- Metabolic syndrome and visceral adiposity (Champaneri et al., 2013)
- Impaired cognitive function and memory consolidation (Lupien et al., 2005)
- Increased inflammatory markers (C-reactive protein, IL-6) (Miller et al., 2007)

The Mindful Coffee application translates this complex neuroendocrine physiology into an actionable visual interface, enabling users to understand and work with their innate biological rhythms.

## 2. The Cortisol Awakening Response (CAR): Mechanisms and Modeling

### 2.1 Physiological Basis

The **Cortisol Awakening Response (CAR)** represents a distinct neuroendocrine phenomenon superimposed upon the circadian cortisol rhythm. It is characterized by a marked surge in cortisol secretion during the first 30–45 minutes following morning awakening, typically resulting in a 50–75% increase from pre-awakening baseline levels (Clow et al., 2004; Pruessner et al., 1997).

The CAR is regulated by a complex interplay between:

- **The suprachiasmatic nucleus (SCN):** Provides the temporal signal for awakening
- **The hippocampus:** Integrates contextual and anticipatory information
- **The HPA axis:** Executes the hormonal response via CRH → ACTH → cortisol cascade

Functionally, the CAR is hypothesized to serve multiple adaptive purposes (Fries et al., 2009):

1. **Metabolic preparation:** Mobilizing glucose stores for anticipated activity
2. **Cognitive priming:** Enhancing memory retrieval and executive function
3. **Immune modulation:** Transitioning from nocturnal Th1 to diurnal Th2 immune balance

### 2.2 Clinical Significance

Individual differences in CAR magnitude carry clinical significance. Meta-analytic evidence indicates that:

- **Elevated CAR** is associated with job stress, anticipatory anxiety, and chronic life stress (Chida & Steptoe, 2009)
- **Blunted CAR** correlates with burnout, fatigue, post-traumatic stress disorder, and poorer health outcomes (Stalder et al., 2016)
- **CAR area under the curve (AUC)** serves as a biomarker of HPA axis reactivity and stress resilience (Pruessner et al., 2003)

### 2.3 Mathematical Representation

In Mindful Coffee, the CAR and subsequent diurnal decline are modeled using a bi-exponential function that captures both the rapid rise and gradual decay:

$$C(t) = C_{baseline} + A_{CAR} \cdot e^{-\lambda_{rise} \cdot t} \cdot (1 - e^{-\lambda_{decay} \cdot t})$$

Where:
- $C(t)$ = cortisol level at time $t$ post-awakening
- $C_{baseline}$ = individual baseline cortisol (user-configurable)
- $A_{CAR}$ = CAR amplitude parameter
- $\lambda_{rise}$ = rate constant for the ascending limb
- $\lambda_{decay}$ = rate constant for diurnal decline

This provides users with a physiologically plausible visual representation of their expected cortisol trajectory throughout the day.

## 3. Caffeine Pharmacology and HPA Axis Modulation

### 3.1 Mechanism of Action

Caffeine (1,3,7-trimethylxanthine) is the most widely consumed psychoactive substance globally, with an estimated 80% of the world's population consuming caffeine daily (Nehlig, 2018). Its primary mechanism involves competitive antagonism of adenosine A₁ and A₂ₐ receptors in the central nervous system, thereby blocking adenosine's inhibitory effects on neuronal activity (Fredholm et al., 1999).

Beyond adenosinergic effects, caffeine exerts significant influence on the HPA axis through multiple pathways:

1. **Direct HPA stimulation:** Caffeine administration acutely elevates plasma cortisol and ACTH levels in a dose-dependent manner (Lovallo et al., 2005)
2. **Catecholamine release:** Enhanced norepinephrine and epinephrine secretion amplifies stress-axis activation (Robertson et al., 1978)
3. **CRH modulation:** Caffeine may potentiate corticotropin-releasing hormone (CRH) signaling in the hypothalamus (Spindel et al., 1983)

### 3.2 Caffeine-Cortisol Interactions

The temporal relationship between caffeine consumption and endogenous cortisol rhythm has important physiological implications:

**Morning consumption during CAR peak:**
- Lovallo et al. (2005) demonstrated that caffeine consumed during the natural morning cortisol peak produces additive or synergistic cortisol elevations
- This may lead to supraphysiological cortisol spikes, potentially contributing to tolerance development
- Habitual morning caffeine consumption has been associated with blunted CAR magnitude over time (James, 2014)

**Consumption during cortisol trough:**
- Late-day caffeine intake coincides with naturally declining cortisol, potentially disrupting the nadir essential for sleep initiation
- Evening caffeine can elevate cortisol during the period when the HPA axis should be quiescent (Drake et al., 2013)

### 3.3 Caffeine Pharmacokinetics

Caffeine elimination follows **first-order kinetics** with considerable inter-individual variability:

$$C_{caffeine}(t) = C_0 \cdot e^{-\frac{\ln(2)}{t_{1/2}} \cdot t}$$

Where:
- $C_0$ = initial caffeine concentration post-absorption
- $t_{1/2}$ = elimination half-life (population mean: 5–6 hours; range: 1.5–9.5 hours)

Key factors influencing half-life include:
- **CYP1A2 genetic polymorphisms:** "Fast" vs. "slow" metabolizer phenotypes (Sachse et al., 1999)
- **Pregnancy:** Half-life extends to 10–20 hours in third trimester (Knutti et al., 1981)
- **Smoking:** Induces CYP1A2, reducing half-life by up to 50% (Parsons & Neims, 1978)
- **Oral contraceptives:** Inhibit CYP1A2, approximately doubling half-life (Abernethy & Todd, 1985)

### 3.4 Emerging Research: Caffeine and Cellular Longevity

Recent investigations have revealed potential mechanisms by which moderate caffeine consumption may influence cellular aging pathways:

- **AMPK activation:** Caffeine has been shown to activate AMP-activated protein kinase (AMPK), a key cellular energy sensor implicated in longevity pathways (Mathew et al., 2014)
- **Autophagy induction:** AMPK activation promotes autophagy, the cellular "housekeeping" process that removes damaged organelles and proteins (Pietrocola et al., 2014)
- **Neuroprotection:** Epidemiological studies consistently associate moderate caffeine intake with reduced risk of Parkinson's and Alzheimer's diseases (Nehlig, 2016)

The app models caffeine-cortisol interactions by superimposing pharmacokinetically-derived caffeine decay curves onto the baseline cortisol rhythm, accounting for the acute cortisol-stimulating effect of each logged beverage.

## 4. Chronobiology, HPA Axis Integrity, and Longevity

### 4.1 Circadian Disruption as a Hallmark of Aging

The maintenance of robust biological rhythms is increasingly recognized as a fundamental determinant of healthspan and longevity. The circadian system undergoes progressive deterioration with age, manifesting as:

- Reduced SCN neuronal activity and output amplitude (Nakamura et al., 2011)
- Blunted hormonal rhythms, including cortisol and melatonin (Van Cauter et al., 1996)
- Fragmented sleep-wake patterns and reduced sleep consolidation (Dijk et al., 2000)

López-Otín et al. (2023) have proposed circadian dysregulation as one of the emerging hallmarks of aging, alongside established hallmarks such as genomic instability, telomere attrition, and cellular senescence.

### 4.2 HPA Axis Dysregulation and Aging Phenotypes

Age-related HPA axis changes contribute to multiple aging phenotypes:

**Glucocorticoid Cascade Hypothesis (Sapolsky et al., 1986):**
This foundational hypothesis posits that cumulative glucocorticoid exposure leads to hippocampal neuronal damage, which in turn impairs HPA negative feedback, creating a feed-forward cycle of cortisol elevation and brain aging.

**Inflammaging:**
Chronic low-grade inflammation, termed "inflammaging" by Franceschi et al. (2000), is exacerbated by:
- Elevated basal cortisol impairing immune regulation
- Circadian disruption increasing pro-inflammatory cytokine production (Castanon-Cervantes et al., 2010)
- Dysregulated HPA feedback leading to sustained inflammatory signaling

**Telomere Dynamics:**
Telomeres, the protective nucleoprotein structures capping chromosome ends, serve as biomarkers of cellular aging. Emerging evidence links cortisol dysregulation to accelerated telomere attrition:
- A blunted CAR is associated with shorter leukocyte telomere length (Thomas et al., 2022)
- Chronic stress-induced hypercortisolism correlates with increased telomere shortening rate (Epel et al., 2004)
- Mindfulness interventions that normalize cortisol rhythms may preserve telomere maintenance (Epel et al., 2009)

### 4.3 Practical Chronobiology: Timing Caffeine for Circadian Health

Based on the evidence reviewed, strategic caffeine timing recommendations emerge:

| Time Period | Cortisol Status | Caffeine Recommendation |
|-------------|-----------------|-------------------------|
| 0–90 min post-waking | CAR peak | Delay consumption to avoid synergistic elevation |
| 90 min – 12:00 | Post-CAR plateau | Optimal window for caffeine if desired |
| 12:00 – 14:00 | Early afternoon dip | Secondary window; may enhance alertness |
| After 14:00 | Progressive decline | Caution: may impair sleep onset |
| Evening | Approaching nadir | Avoid: disrupts circadian melatonin release |

These evidence-based guidelines are operationalized in Mindful Coffee's visual interface, allowing users to see their personalized caffeine "cutoff time" based on their individual metabolism and target sleep time.

By helping users visualize and align their caffeine intake with natural cortisol rhythms, the app provides a tool for practical chronobiology—supporting HPA axis homeostasis and potentially mitigating age-related circadian deterioration.

## 5. Sleep Architecture and Caffeine's Disruptive Effects

### 5.1 Sleep Physiology Overview

Human sleep follows a structured architecture of alternating NREM (Non-Rapid Eye Movement) and REM (Rapid Eye Movement) cycles, each lasting approximately 90 minutes. Optimal sleep requires:

- **Low cortisol levels:** The nocturnal nadir facilitates sleep onset and maintenance
- **Rising melatonin:** Secreted by the pineal gland in response to darkness
- **Reduced adenosine antagonism:** Accumulated adenosine promotes sleep pressure

### 5.2 Caffeine's Impact on Sleep Parameters

Even when caffeine is consumed several hours before bedtime, residual effects can significantly impair sleep quality. Drake et al. (2013) demonstrated that 400mg of caffeine consumed 6 hours before bedtime:

- Reduced total sleep time by more than 1 hour
- Increased sleep onset latency
- Decreased sleep efficiency
- Reduced time in restorative slow-wave sleep

Importantly, subjects often underestimated these effects, highlighting the need for objective tracking.

### 5.3 The Sleep Prediction Model

Mindful Coffee calculates a personalized "sleep-ready time" by integrating:

1. Individual caffeine half-life (user-configurable based on metabolism quiz)
2. Personal caffeine sensitivity threshold (mg at which sleep is impaired)
3. Cumulative caffeine from all logged beverages

$$t_{sleep-ready} = t_{last-dose} + t_{1/2} \cdot \log_2\left(\frac{C_{current}}{C_{threshold}}\right)$$

This provides users with a data-driven estimate of when their caffeine levels will decline sufficiently to permit quality sleep.

## 6. Individual Variability and Personalization

### 6.1 Sources of Inter-Individual Variation

The app's personalization features acknowledge substantial biological variability in both cortisol rhythms and caffeine metabolism:

**Genetic factors:**
- CYP1A2 polymorphisms create "fast" and "slow" caffeine metabolizer phenotypes (Cornelis et al., 2006)
- ADORA2A polymorphisms influence caffeine sensitivity and sleep disruption susceptibility (Rétey et al., 2007)

**Lifestyle factors:**
- Shift work disrupts circadian cortisol patterns (Boivin & Boudreau, 2014)
- Chronic stress alters HPA axis responsivity and CAR magnitude
- Age-related changes in both caffeine metabolism and cortisol rhythmicity

**Physiological states:**
- Pregnancy dramatically extends caffeine half-life
- Hepatic function influences both cortisol and caffeine metabolism

### 6.2 The Metabolism Quiz

To address this variability, Mindful Coffee includes a guided assessment that helps users calibrate:

- **Caffeine half-life:** Based on age, sex, smoking status, and medication use
- **Sensitivity threshold:** Informed by self-reported sleep disturbance patterns
- **CAR parameters:** Wake time and subjective energy patterns

This personalized approach aligns with precision medicine principles, moving beyond population averages to individual-level recommendations.

## 7. Conclusion

The cortisol and caffeine modeling features in Mindful Coffee represent a translational application of established chronobiological, endocrinological, and pharmacological principles. By synthesizing peer-reviewed evidence on:

1. Circadian cortisol rhythmicity and the CAR
2. Caffeine's pharmacokinetics and HPA axis effects
3. The interplay between timing, metabolism, and sleep quality
4. Individual variability in caffeine sensitivity and metabolism

—the app provides users with a scientifically-grounded tool for optimizing their caffeine consumption patterns. This approach supports immediate goals (enhanced alertness, improved sleep) while potentially contributing to long-term health outcomes through preservation of circadian and HPA axis integrity.

The implementation of these models can be explored in the [**Mindful Coffee app on the App Store**](https://apps.apple.com/us/app/mindful-coffee-tracks-caffeine/id6742878005?platform=iphone). For technical documentation and community contributions, please visit the project's [**GitHub repository**](https://github.com/aloth/mindful-coffee).

## 8. Citation

If you use the concepts, models, or findings described in this document for academic or research purposes, please cite as follows:

Loth, A. (2025). *Research Background: Cortisol, Caffeine, and Chronobiology in Mindful Coffee* (Version 2.0). Frankfurt University of Applied Sciences. https://github.com/aloth/mindful-coffee/blob/main/RESEARCH_BACKGROUND.md

### BibTeX

```bibtex
@techreport{Loth2025MindfulCoffeeCortisol,
  author       = {Loth, Alexander},
  title        = {Research Background: Cortisol, Caffeine, and Chronobiology in Mindful Coffee},
  year         = {2025},
  month        = {August},
  institution  = {Frankfurt University of Applied Sciences},
  type         = {Technical Report},
  version      = {2.0},
  url          = {https://github.com/aloth/mindful-coffee/blob/main/RESEARCH_BACKGROUND.md},
  note         = {Accessed: YYYY-MM-DD}
}
```

### APA Format

Loth, A. (2025). *Research background: Cortisol, caffeine, and chronobiology in Mindful Coffee* (Version 2.0) [Technical report]. Frankfurt University of Applied Sciences. https://github.com/aloth/mindful-coffee/blob/main/RESEARCH_BACKGROUND.md

## References

Abernethy, D. R., & Todd, E. L. (1985). Impairment of caffeine clearance by chronic use of low-dose oestrogen-containing oral contraceptives. *European Journal of Clinical Pharmacology*, 28(4), 425–428. https://doi.org/10.1007/BF00544361

Adam, E. K., Quinn, M. E., Tavernier, R., McQuillan, M. T., Dahlke, K. A., & Gilbert, K. E. (2017). Diurnal cortisol slopes and mental and physical health outcomes: A systematic review and meta-analysis. *Psychoneuroendocrinology*, 83, 25–41. https://doi.org/10.1016/j.psyneuen.2017.05.018

Boivin, D. B., & Boudreau, P. (2014). Impacts of shift work on sleep and circadian rhythms. *Pathologie Biologie*, 62(5), 292–301. https://doi.org/10.1016/j.patbio.2014.08.001

Castanon-Cervantes, O., Wu, M., Ehlen, J. C., Paul, K., Gamble, K. L., Johnson, R. L., ... & Davidson, A. J. (2010). Dysregulation of inflammatory responses by chronic circadian disruption. *The Journal of Immunology*, 185(10), 5796–5805. https://doi.org/10.4049/jimmunol.1001026

Champaneri, S., Xu, X., Carnethon, M. R., Bertoni, A. G., Seeman, T., DeSantis, A. S., ... & Golden, S. H. (2013). Diurnal salivary cortisol is associated with body mass index and waist circumference: The Multiethnic Study of Atherosclerosis. *Obesity*, 21(1), E56–E63. https://doi.org/10.1002/oby.20047

Chellappa, S. L., Vujovic, N., Williams, J. S., & Scheer, F. A. J. L. (2021). Impact of circadian disruption on cardiovascular function and disease. *Trends in Endocrinology & Metabolism*, 30(10), 767–779. https://doi.org/10.1016/j.tem.2019.07.008

Chida, Y., & Steptoe, A. (2009). Cortisol awakening response and psychosocial factors: A systematic review and meta-analysis. *Biological Psychology*, 80(3), 265–278. https://doi.org/10.1016/j.biopsycho.2008.10.004

Clow, A., Thorn, L., Evans, P., & Hucklebridge, F. (2004). The awakening cortisol response: Methodological issues and significance. *Stress*, 7(1), 29–37. https://doi.org/10.1080/10253890410001667205

Cornelis, M. C., El-Sohemy, A., Kabagambe, E. K., & Campos, H. (2006). Coffee, CYP1A2 genotype, and risk of myocardial infarction. *JAMA*, 295(10), 1135–1141. https://doi.org/10.1001/jama.295.10.1135

Dijk, D. J., Duffy, J. F., Riel, E., Shanahan, T. L., & Czeisler, C. A. (2000). Ageing and the circadian and homeostatic regulation of human sleep during forced desynchrony of rest, melatonin and temperature rhythms. *The Journal of Physiology*, 516(2), 611–627. https://doi.org/10.1111/j.1469-7793.1999.0611v.x

Drake, C., Roehrs, T., Shambroom, J., & Roth, T. (2013). Caffeine effects on sleep taken 0, 3, or 6 hours before going to bed. *Journal of Clinical Sleep Medicine*, 9(11), 1195–1200. https://doi.org/10.5664/jcsm.3170

Epel, E. S., Blackburn, E. H., Lin, J., Dhabhar, F. S., Adler, N. E., Morrow, J. D., & Cawthon, R. M. (2004). Accelerated telomere shortening in response to life stress. *Proceedings of the National Academy of Sciences*, 101(49), 17312–17315. https://doi.org/10.1073/pnas.0407162101

Epel, E., Daubenmier, J., Moskowitz, J. T., Folkman, S., & Blackburn, E. (2009). Can meditation slow rate of cellular aging? Cognitive stress, mindfulness, and telomeres. *Annals of the New York Academy of Sciences*, 1172(1), 34–53. https://doi.org/10.1111/j.1749-6632.2009.04414.x

Fogelman, N., & Bhattacharya, B. S. (2022). Diurnal cortisol slope, health, and longevity: A systematic review and meta-analysis. *Psychoneuroendocrinology*, 146, 105943. https://doi.org/10.1016/j.psyneuen.2022.105943

Franceschi, C., Bonafè, M., Valensin, S., Olivieri, F., De Luca, M., Ottaviani, E., & De Benedictis, G. (2000). Inflamm-aging: An evolutionary perspective on immunosenescence. *Annals of the New York Academy of Sciences*, 908(1), 244–254. https://doi.org/10.1111/j.1749-6632.2000.tb06651.x

Fredholm, B. B., Bättig, K., Holmén, J., Nehlig, A., & Zvartau, E. E. (1999). Actions of caffeine in the brain with special reference to factors that contribute to its widespread use. *Pharmacological Reviews*, 51(1), 83–133.

Fries, E., Dettenborn, L., & Kirschbaum, C. (2009). The cortisol awakening response (CAR): Facts and future directions. *International Journal of Psychophysiology*, 72(1), 67–73. https://doi.org/10.1016/j.ijpsycho.2008.03.014

James, J. E. (2014). Caffeine and cognitive performance: Persistent methodological challenges in caffeine research. *Pharmacology Biochemistry and Behavior*, 124, 117–122. https://doi.org/10.1016/j.pbb.2014.05.019

Knutti, R., Rothweiler, H., & Schlatter, C. (1981). Effect of pregnancy on the pharmacokinetics of caffeine. *European Journal of Clinical Pharmacology*, 21(2), 121–126. https://doi.org/10.1007/BF00637512

López-Otín, C., Blasco, M. A., Partridge, L., Serrano, M., & Kroemer, G. (2023). Hallmarks of aging: An expanding universe. *Cell*, 186(2), 243–278. https://doi.org/10.1016/j.cell.2022.11.001

Lovallo, W. R., Whitsett, T. L., al'Absi, M., Sung, B. H., Vincent, A. S., & Wilson, M. F. (2005). Caffeine stimulation of cortisol secretion across the waking hours in relation to caffeine intake levels. *Psychosomatic Medicine*, 67(5), 734–739. https://doi.org/10.1097/01.psy.0000181270.20036.06

Lupien, S. J., Fiocco, A., Wan, N., Maheu, F., Lord, C., Schramek, T., & Tu, M. T. (2005). Stress hormones and human memory function across the lifespan. *Psychoneuroendocrinology*, 30(3), 225–242. https://doi.org/10.1016/j.psyneuen.2004.08.003

Mathew, T. S., Ferris, R. K., Downs, R. M., Kinber, S. T., & Artinian, M. L. (2014). Caffeine promotes autophagy in skeletal muscle cells by increasing the calcium-dependent activation of AMP-activated protein kinase. *Biochemical and Biophysical Research Communications*, 453(3), 411–418. https://doi.org/10.1016/j.bbrc.2014.09.094

Miller, G. E., Chen, E., & Zhou, E. S. (2007). If it goes up, must it come down? Chronic stress and the hypothalamic-pituitary-adrenocortical axis in humans. *Psychological Bulletin*, 133(1), 25–45. https://doi.org/10.1037/0033-2909.133.1.25

Nakamura, T. J., Nakamura, W., Yamazaki, S., Kudo, T., Cutler, T., Colwell, C. S., & Block, G. D. (2011). Age-related decline in circadian output. *Journal of Neuroscience*, 31(28), 10201–10205. https://doi.org/10.1523/JNEUROSCI.0451-11.2011

Nehlig, A. (2016). Effects of coffee/caffeine on brain health and disease: What should I tell my patients? *Practical Neurology*, 16(2), 89–95. https://doi.org/10.1136/practneurol-2015-001162

Nehlig, A. (2018). Interindividual differences in caffeine metabolism and factors driving caffeine consumption. *Pharmacological Reviews*, 70(2), 384–411. https://doi.org/10.1124/pr.117.014407

Nicolaides, N. C., Charmandari, E., Chrousos, G. P., & Kino, T. (2015). Circadian endocrine rhythms: The hypothalamic–pituitary–adrenal axis and its actions. *Annals of the New York Academy of Sciences*, 1318(1), 71–80. https://doi.org/10.1111/nyas.12464

Parsons, W. D., & Neims, A. H. (1978). Effect of smoking on caffeine clearance. *Clinical Pharmacology & Therapeutics*, 24(1), 40–45. https://doi.org/10.1002/cpt197824140

Pietrocola, F., Malik, S. A., Mariño, G., Vacchelli, E., Senovilla, L., Chaba, K., ... & Kroemer, G. (2014). Coffee induces autophagy in vivo. *Cell Cycle*, 13(12), 1987–1994. https://doi.org/10.4161/cc.28929

Pruessner, J. C., Wolf, O. T., Hellhammer, D. H., Buske-Kirschbaum, A., Von Auer, K., Jobst, S., ... & Kirschbaum, C. (1997). Free cortisol levels after awakening: A reliable biological marker for the assessment of adrenocortical activity. *Life Sciences*, 61(26), 2539–2549. https://doi.org/10.1016/S0024-3205(97)01008-4

Pruessner, J. C., Kirschbaum, C., Meinlschmid, G., & Hellhammer, D. H. (2003). Two formulas for computation of the area under the curve represent measures of total hormone concentration versus time-dependent change. *Psychoneuroendocrinology*, 28(7), 916–931. https://doi.org/10.1016/S0306-4530(02)00108-7

Rétey, J. V., Adam, M., Khatami, R., Luhmann, U. F., Jung, H. H., Berger, W., & Landolt, H. P. (2007). A genetic variation in the adenosine A2A receptor gene (ADORA2A) contributes to individual sensitivity to caffeine effects on sleep. *Clinical Pharmacology & Therapeutics*, 81(5), 692–698. https://doi.org/10.1038/sj.clpt.6100102

Robertson, D., Frölich, J. C., Carr, R. K., Watson, J. T., Hollifield, J. W., Shand, D. G., & Oates, J. A. (1978). Effects of caffeine on plasma renin activity, catecholamines and blood pressure. *New England Journal of Medicine*, 298(4), 181–186. https://doi.org/10.1056/NEJM197801262980403

Sachse, C., Brockmöller, J., Bauer, S., & Roots, I. (1999). Functional significance of a C→A polymorphism in intron 1 of the cytochrome P450 CYP1A2 gene tested with caffeine. *British Journal of Clinical Pharmacology*, 47(4), 445–449. https://doi.org/10.1046/j.1365-2125.1999.00898.x

Sapolsky, R. M., Krey, L. C., & McEwen, B. S. (1986). The neuroendocrinology of stress and aging: The glucocorticoid cascade hypothesis. *Endocrine Reviews*, 7(3), 284–301. https://doi.org/10.1210/edrv-7-3-284

Spindel, E. R., Wurtman, R. J., McCall, A., Carr, D., Conlay, L., Griffith, L., & Arnold, M. (1983). Neuroendocrine effects of caffeine in normal subjects. *Clinical Pharmacology & Therapeutics*, 34(1), 74–82. https://doi.org/10.1038/clpt.1983.131

Stalder, T., Kirschbaum, C., Kudielka, B. M., Adam, E. K., Pruessner, J. C., Wüst, S., ... & Clow, A. (2016). Assessment of the cortisol awakening response: Expert consensus guidelines. *Psychoneuroendocrinology*, 63, 414–432. https://doi.org/10.1016/j.psyneuen.2015.10.010

Thomas, K. N., Badal, T. S., Morrison-Sherwood, C. L., Nguyen, P. T., Gagner, C., Bhagchandani, H., ... & Price, L. H. (2022). Influence of cortisol awakening response on telomere length: Trends for males and females. *European Journal of Neuroscience*, 56(4), 4635–4650. https://doi.org/10.1111/ejn.15775

Van Cauter, E., Leproult, R., & Kupfer, D. J. (1996). Effects of gender and age on the levels and circadian rhythmicity of plasma cortisol. *The Journal of Clinical Endocrinology & Metabolism*, 81(7), 2468–2473. https://doi.org/10.1210/jcem.81.7.8675562

Weitzman, E. D., Fukushima, D., Nogeire, C., Roffwarg, H., Gallagher, T. F., & Hellman, L. (1971). Twenty-four hour pattern of the episodic secretion of cortisol in normal subjects. *The Journal of Clinical Endocrinology & Metabolism*, 33(1), 14–22. https://doi.org/10.1210/jcem-33-1-14

---

*Last updated: December 2025*
