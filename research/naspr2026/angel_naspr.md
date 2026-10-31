---
layout: default
title: "Angel's Poster"
permalink: /research/naspr2026/angel_naspr.md/
---

<h1>{% include icon.html icon="fa-solid fa-feather-pointed" %} Angel's Poster</h1>

## The Relationship Between a Decrease in Technical Disruptions and an Increase in Therapeutic Alliance

by **Yongxue Wei**¹˒²˒³, **Jimmy Pengyu Chen**¹˒²˒³, **Hanjiang Xu**¹˒²˒³, **Lilian Guo**¹˒²˒³, **Madison Wakely**¹, & **Sarah Bloch-Elkouby**²˒³

¹ Teachers College, Columbia University, New York, NY, USA  
² Ferkauf Graduate School of Psychology, Yeshiva University, New York, NY, USA  
³ Icahn School of Medicine at Mount Sinai, New York, NY, USA

<div style="width: 100%; margin: 20px 0;">
  <iframe
    src="{{ '/research/naspr2026/Angel_NASPR.pdf' | relative_url }}"
    width="100%"
    height="900px"
    style="border: 1px solid #ddd;"
    title="Angel's 2026 NASPR Poster">
  </iframe>
</div>

### Background

AI-powered virtual patients (VPs) offer scalable, low-risk practice for clinical training in suicide risk assessment.

Technical errors can still produce nonsensical or off-topic VP responses, which can break immersion and make it harder for trainees to build a therapeutic alliance.

Prior work from our lab found no association between technical disruptions and working alliance or ruptures (Chen et al., 2025), suggesting minimal impact under current technology.

Adding ChatGPT to a DialogFlow VP offered a natural test: if errors matter, a VP that makes fewer of them should yield a stronger alliance.

### Present Study

**Aim:** Determine whether a systematic decrease in technical disruptions is associated with an increase in therapeutic alliance.

**Hypotheses:** Compared with the DialogFlow VP, the ChatGPT-enhanced VP would show:

- **H1:** Fewer objective and perceived technical disruptions.
- **H2:** Higher Rupture Resolution Rating System (3RS) working together scores.
- **H3:** Lower rupture impact scores.
- **H4:** Fewer technical disruptions would predict better alliance outcomes.

### Methods

**Participants:** N = 101 doctoral student clinicians.

- DialogFlow VP (previous study): n = 69
- DialogFlow + ChatGPT VP (ongoing pilot): n = 32

**Procedure:** Participants completed a diagnostic interview via Zoom with a teenage virtual patient presenting with suicidal ideation, followed by post-session ratings.

**Measures:**

- **Objective disruption:** Percentage of VP responses coded as No Match (input did not match any DialogFlow intent, triggering a fallback reply) or Nonsensical (input matched to the wrong intent, producing an irrelevant reply).
- **Perceived disruption:** Single-item ratings (0 to 6) of platform disruption (e.g., Zoom, audio) and VP language disruption.
- **Alliance and rupture (3RS):** Working together (5 items, 1 to 7, α = .83); impact of internal, confrontation, and withdrawal ruptures (1 to 7).

**Analyses (R):** Welch's t tests with Cohen's d; simultaneous OLS regression (collinearity checked via VIF) with best subset selection by BIC; bootstrap indirect effect (5,000 resamples).

### Results

**H1: Fewer disruptions with ChatGPT**

- Objective disruption rate decreased from 29.6% to 17.3% (p < .001).
- Perceived language disruption was lower in the ChatGPT condition, t(48.0) = −2.12, p = .040.
- Perceived technical disruption showed no difference (p = .591).

**H2 and H3: Alliance and rupture outcomes**

- Working together scores were 3.89 versus 3.99 (p = .639), showing no significant difference.
- Internal rupture impact decreased from 4.47 to 3.59 (p = .005).
- H2 was not supported; H3 was partially supported, with a decrease in internal rupture impact only.

**H4: Perceived disruption predicted alliance**

Perceived language disruption, but not the objective error rate, predicted both alliance outcomes.

The lower internal rupture impact in the ChatGPT condition was not explained by fewer objective errors (indirect effect ab = −0.10, 95% bootstrap CI [−0.48, 0.32], n = 100).

### Discussion

The ChatGPT-enhanced VP was associated with about 40% fewer disruptions and less negative internal reactions, yet working alliance did not improve, echoing our earlier findings (Chen et al., 2025).

Perceived language disruption predicted both alliance outcomes: how natural the VP sounds may matter more than how often it fails.

### Key Takeaway

The ChatGPT-enhanced VP made fewer errors and elicited less negative internal reactions, but alliance tracked how disruptive trainees perceived the VP's language, not how many errors actually occurred.

### Limitations

- Nonrandomized cohorts.
- Smaller ChatGPT sample.
- Perceived disruption and alliance were both self-reported at the same time, creating potential shared method variance.
- Multiple tests were conducted without correction.

### Future Directions

Conduct a randomized comparison of VP versions and develop coding schemes that capture ChatGPT-specific problems, such as inauthentic responses.

### References

Chen, J., Wei, J., Datta, S., Shi, R., & Bloch-Elkouby, S. (2025, June). *How much do inappropriate responses impede clinicians’ engagement and therapeutic alliance with a virtual patient?* [Poster presentation].

Eubanks, C. F., Lubitz, J., Muran, J. C., & Safran, J. D. (2019). Rupture Resolution Rating System (3RS): Development and validation. *Psychotherapy Research, 29*(3), 306–319. https://doi.org/10.1080/10503307.2018.1552034
