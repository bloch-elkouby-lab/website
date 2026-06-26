---
title: "SPR2026 - Chen"
permalink: /posters/spr2026_chen/
---
## {% include icon.html icon="fa-solid fa-feather-pointed" %} Jimmy P. Chen's Poster

## Disproportionate Impact of Technological Disruptions on Suicide Risk Assessment in Black Virtual Patients ##

by **Jimmy P. Chen**<sup>1,2</sup>, Lilian Guo<sup>1,2,3</sup>, Yongxue Wei<sup>1,2,3</sup>, Aditya Bhise<sup>1,2</sup>, Jingyi Yang<sup>1,2</sup>,& Sarah Bloch-Elkouby <sup>1,2</sup>

1 Icahn School of Medicine at Mount Sinai in New York City
2 Ferkauf Graduate School of Psychology, Yeshiva University
3 Teachers College, Columbia University in the City of New York

{% include figure.html
   image="research/spr2026/spr2026_chen.jpg"
%}

### Background: ###

The disproportionate under- and mis-diagnoses of suicide risk in Black populations have been well documented. However, few studies have investigated how race impacts the diagnostic interview process, which is the gateway to most diagnoses, and renders the clinical judgement inaccurate. 

To close the gap, the current study leverages AI-powered virtual patient (VP) system, which <span style="font-size: 150%;">**a novel tool for psychotherapy research and clinician training**</span>, more powerful than vignettes to demonstrate psychotherapy process in vivo and equally faithful as standardized patients (Bloch-Elkouby et al., 2026). 

Despite many advantages, the intent-matching based VP system supported by Google DialogFlow exhibits technological disruptions, including **intent mismatches** that result in **nonsense responses** and **intent no matches** that output a **fallback request to rephrase**. Previous research established that disruptions negatively impacted clinicians’ facial affective behaviors and therapeutic alliance (Gomes de Siqueira et al., 2021, 2024). 

Provided the disproportionate impact of race on suicide-related clinical judgements, the current study hypothesize that this disproportionate impact of race will extend to the perception of technological disruptions.


### Hypothesis: ###
<span style="font-size: 150%;">H1: Technical disruptions significantly predict clinician’s perception of suicide ideation (H1a), suicide crisis (H1b), and overall suicide risk (H1c).
H2: The relationship between technical disruptions and suicide ideation (H2a), suicide crisis (H2b), and overall suicide risk (H2c) is moderated by virtual patient’s race. </span>

### Method: ###

176 upcoming and licensed clinicians each completed one diagnostic interview with the VP. Immediately after the interview, clinicians provided their assessment of the VP on suicidal ideation (C-SSRS; Posner et al., 2011), suicide crisis (Suicide Crisis Syndrome-Checklist, SCS-C; Bloch-Elkouby et al., 2026), and overall suicidal risk (Clinician Prediction Scale, CPS; Nock et al., 2010). Technological disruptions were measured by three subjective survey questions---the **a. number of inappropriate responses**, **b. disruptive impact of technical issues** (1 Not at all &ndash 6 Very), and **c. disruptive impact of language issues** (1 Not at all &ndash 6 Very)---and the absolute number and percentage of intent no match and mismatch, obtained by an analysis on the interaction transcript. Four versions of the intent no match and mismatch are attempted (V1. **Percentage of intent no match and mismatch**; V2. **Percentage of total mismatch and no match**; V3. **Intent no match and mismatch by number**; V4. **Total number of no match and mismatch**). Twelve regression analyses (3 outcome variables x 4 versions of predictors) analyzed the impact of disruptions and moderation by VP race. 

<table>
  <tr>
    <th colspan="2">Participant: mostly upcoming<br>and few licensed clinicians</th>
    <th colspan="2">Interview goal: Overall risk<br>assessment and diagnosis</th>
    <th>Setting: Zoom</th>
  </tr>
  <tr>
    <th>Recruited</th>
    <th>Excluded</th>
    <th>Total N</th>
    <th>Male</th>
    <th>Female</th>
  </tr>
  <tr>
    <td>193</td>
    <td>17</td>
    <td>176</td>
    <td>31</td>
    <td>134</td>
  </tr>
  <tr>
    <th>Non-binary</th>
    <th>White</th>
    <th>Black</th>
    <th>Other Race</th>
    <th>Noah B / W</th>
  </tr>
  <tr>
    <td>11</td>
    <td>120</td>
    <td>12</td>
    <td>44</td>
    <td>95 / 81</td>
  </tr>
</table>

### Results: ###

| Outcome | Model | Significant Predictors | Model Fit |
|---|---|---|---|
| SCS | V1 | b × VP Race (.035) | R² = .111, p = .135 |
| SCS | V2 | b × VP Race (.032) | R² = .105, p = .082 |
| SCS | V3 | Intent mismatch (.038), b × VP Race (.017), a × VP Race (.029) | R² = .131, p = .057 |
| SCS | V4 | Total technological disruptions (.021), b × VP Race (.015), a × VP Race (.024) | R² = .119, p = .042 |
| CSSRS | V1 | b (.028), a (.043), Intent no match % (.032), b × VP Race (.002) | R² = .139, p = .042 |
| CSSRS | V2 | b (.027), a (.041), Total technological disruptions % (.013), b × VP Race (.001) | R² = .136, p = .018 |
| CSSRS | V3 | b (.026), a (.035), Intent no match (.045), b × VP Race (< .001) | R² = .137, p = .046 |
| CSSRS | V4 | b (.031), a (.035), Total technological disruptions × VP Race (.034), b × VP Race (.001) | R² = .124, p = .034 |
| CPS | V1 | b × VP Race (.026) | R² = .102, p = .223 |
| CPS | V2 | b × VP Race (.022) | R² = .098, p = .136 |
| CPS | V3 | b × VP Race (.012) | R² = .127, p = .086 |
| CPS | V4 | b × VP Race (.012) | R² = .123, p = .043 |
|

### Discussion: ###

First, among all interactions in a transcript (one user input plus one virtual patient response), 27% of interactions on average are marked as either mismatch or no match, indicating substantial room for improvement with AI powered by LLM in addition to the intent-matching system. 

Technological disruptions demonstrated the strongest and most consistent effects on clinicians’ ratings of suicidal ideation (C-SSRS), whereas effects on suicide crisis (SCS) and overall suicide risk (CPS) were less robust. Predictor b, disruptive impact of technical issues, emerged to be the most prominent predictor across all outcome measures and contributed to higher level of perceived risk. Objective coding demonstrated mixed contributions (higher suicide crisis but lower suicide ideation).

Although the analysis has very limited support for H1, that suicide risk assessments will be impacted by technical disruptions, H2 are consistently supported. Specifically, the interactions indicate that experiencing more technical disruptions while interviewing the Black virtual patient led to more perceived suicide ideation (CSSRS) and overall risk (CPS) but less suicide crisis (SCS-C). 

### References: ###

Bloch-Elkouby, S., El-Hayek, R., Cohen, L., Chen, J. P., Gorman, B., Apter, Y., Wheeler, E., Park, B., Prekas, A. S., & Galynker, I. (2026). The clinician rated suicide crisis syndrome checklist (SCS-C): Structure, reliability, and concurrent validity among adult psychiatric inpatients. Journal of Affective Disorders, 402, 121341. [https://doi.org/10.1016/j.jad.2026.121341](https://doi.org/10.1016/j.jad.2026.121341)
Bloch-Elkouby, S., Johnson, B. N., Chen, J. P., Shi, R., Goncearenco, I., Khaikin, S., Wei, Y., Xu, H., Gomes De Siqueira, A., Yao, H., Lok, B., Cohen, L., Apter-Levi, Y., Shimon Raz, O., Williams, M. T., & Galynker, I. (2026). Race, Bias, and Suicide Risk Assessment in Adolescents: An Experimental Virtual Patient Study [Manuscript submitted for publication]. Icahn School of Medicine at Mount Sinai.
Gomes de Siqueira, A., Yao, H., Bafna, A., Bloch-Elkouby, S., Richards, J., Lloveras, L. B., Feeney, K., Morris, S., Musser, E., Lok, B., & Galynker, I. (2021, December). Investigating the effects of virtual patients’ nonsensical responses on users’ facial expressions in mental health training scenarios. In Proceedings of the 27th ACM Symposium on Virtual Reality Software and Technology (pp. 1&ndash;10). [https://doi.org/10.1145/3489849.3489864](https://doi.org/10.1145/3489849.3489864)
Gomes de Siqueira, A., Yao, H., Bloch-Elkouby, S., Rogers, M. L., Lawrence, O. C., Peterkin, D., Zheng, S., Feeney, K., Musser, E. D., Galynker, I., & Lok, B. (2024). Effects of nonsensical responses in virtual human simulations on clinicians’ empathic communication and emotional responses. Journal of the Brazilian Computer Society, 30(1), 554&ndash;568. [https://doi.org/10.5753/jbcs.2024.4665](https://doi.org/10.5753/jbcs.2024.4665)
Nock, M. K., Park, J. M., Finn, C. T., Deliberto, T. L., Dour, H. J., & Banaji, M. R. (2010). Measuring the Suicidal Mind: Implicit Cognition Predicts Suicidal Behavior. Psychological Science, 21(4), 511&ndash;517. [https://doi.org/10.1177/0956797610364762](https://doi.org/10.1177/0956797610364762) 
Posner, K., Brown, G. K., Stanley, B., Brent, D. A., Yershova, K. V., Oquendo, M. A., Currier, G. W., Melvin, G. A., Greenhill, L., Shen, S., & Mann, J. J. (2011). The Columbia&ndash;Suicide Severity Rating Scale: Initial Validity and Internal Consistency Findings From Three Multisite Studies With Adolescents and Adults. American Journal of Psychiatry, 168(12), 1266&ndash;1277. [https://doi.org/10.1176/appi.ajp.2011.10111704](https://doi.org/10.1176/appi.ajp.2011.10111704) 
