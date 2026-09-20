# 🩺 Biologics in Psoriasis — A Mini-Lecture

*(Chapter: Disorders of Keratinization | Rook's, Bolognia, Andrews')*

---

## Part 1 — The Big Picture: Why This Topic Exists at All

Let me start by framing why this question matters so much, because if you understand *why* biologics were invented, the entire pharmacology becomes almost self-evident.

For most of the twentieth century, we treated psoriasis as though it were a **disease of the skin cell**. The visible abnormality is a keratinocyte behaving badly — dividing too fast, maturing incorrectly, piling up as silvery scale. So naturally, our drugs attacked dividing cells: **methotrexate** (antifolate, stops DNA synthesis), **retinoids** (force normal differentiation), **PUVA** (DNA crosslinking by psoralen + UVA), **cyclosporine** (broad calcineurin blockade). These work — genuinely well — but they share a fatal design flaw: they are **blunt instruments**. Methotrexate does not know the difference between a psoriatic keratinocyte and a hepatocyte or a bone marrow progenitor. Cyclosporine does not know the difference between a pathogenic T cell and a renal afferent arteriole. Cumulative toxicity is therefore inevitable — hepatic fibrosis, nephrotoxicity, hypertension, photocarcinogenesis, teratogenicity. You cannot use these drugs for forty years in a twenty-year-old patient, and psoriasis is a **lifelong** disease.

Then came the pathogenic revelation: **psoriasis is not primarily a keratinocyte disease at all — it is an immune-mediated disease in which the keratinocyte is the victim, not the villain.** The skin thickening is a *downstream consequence* of a specific, identifiable conversation between dendritic cells, T cells, and cytokines.

Once you know the exact molecules carrying that conversation, you can do something extraordinary: you can build a drug that **silences one sentence of the conversation and leaves the rest of the immune system talking normally**. That is what a biologic is.

> **Analogy:** Classical systemics are like turning off the main circuit breaker of a house because one room's music is too loud — effective, but now the refrigerator, the lights, and the ventilator are also off. A biologic is like walking into that one room and unplugging that one speaker.

---

## Part 2 — The Pathway You Must Own Before the Drugs Make Sense

Every single biologic in the summary table is simply a **specific interruption point on one pathway**. Let me walk the pathway end to end, because the drug names then arrange themselves automatically.

**Step 1 — The trigger.** Injury, infection (streptococcal pharyngitis), drugs (lithium, beta-blockers, antimalarials), or stress cause keratinocytes to release antimicrobial peptides, most importantly **LL-37 (cathelicidin)**. LL-37 binds the patient's own DNA/RNA fragments and turns self-nucleic acid into an immunogenic complex.

**Step 2 — Plasmacytoid dendritic cell activation.** These LL-37/DNA complexes stimulate TLR7/9 on plasmacytoid dendritic cells, which pour out **type I interferon (IFN-α)**. This is the "ignition" phase.

**Step 3 — Myeloid dendritic cell activation — the pivotal step.** IFN-α matures dermal myeloid dendritic cells, which then secrete the two cytokines that define psoriasis: **IL-12** and **IL-23**, together with **TNF-α**.

**Step 4 — T-cell polarization.**
- **IL-12** (composed of subunits **p35 + p40**) drives naïve T cells toward **Th1** → they make IFN-γ and TNF-α.
- **IL-23** (composed of subunits **p19 + p40**) is the *survival and maintenance factor* for **Th17/Th22** cells. Notice carefully: **both cytokines share the p40 subunit.** Remember this — it is the single most examinable molecular fact in this entire answer.

**Step 5 — The effector cytokine.** Th17 cells (and innate sources: γδ T cells, ILC3s, mast cells, neutrophils) release **IL-17A** (plus IL-17F, IL-22, TNF-α).

**Step 6 — The keratinocyte responds.** IL-17A is the molecule the keratinocyte actually "hears." Upon IL-17 receptor engagement, the keratinocyte:
- proliferates rapidly (acanthosis, and because transit time falls from ~28 days to ~4 days, it cannot mature → **parakeratosis**, loss of granular layer)
- releases **CXCL1/CXCL8 (IL-8)** → neutrophil chemotaxis → **Munro's microabscesses** and **spongiform pustules of Kogoj**
- releases **VEGF** → the dilated, tortuous dermal papillary capillaries that give you **Auspitz sign**
- releases more **LL-37, IL-1, IL-6, TNF-α** → which re-stimulate the dendritic cells

**Step 7 — The feed-forward loop.** Step 6 regenerates Step 1. This is why psoriasis is *chronic and self-sustaining*: it is a closed circuit. **TNF-α is the amplifier that runs through every single loop of that circuit** — it acts on dendritic cells, T cells, endothelium, and keratinocytes simultaneously.

**Now the drug classes write themselves:**

| Where you cut the circuit | Drug class |
|---|---|
| The amplifier running through the whole loop | **TNF-α inhibitors** |
| The shared p40 subunit → kills *both* Th1 and Th17 arms | **Ustekinumab (IL-12/23)** |
| The p19 subunit → kills *only* the Th17 arm at its upstream master switch | **IL-23 inhibitors** |
| The final effector cytokine the skin cell hears | **IL-17 inhibitors** |
| The T cell itself (activation/adhesion) | **Alefacept, Efalizumab** (historical) |

This is the "one picture" of the answer. Everything below is detail hanging on this skeleton.

---

## Part 3 — What Exactly *Is* a Biologic? (Definition, unpacked)

**Source definition:** *Biologics are targeted therapies utilizing proteins or antibodies designed to block specific molecular targets important in the pathogenesis of psoriasis.*

Let me expand every word of that.

- **"Proteins or antibodies"** — these are *large* molecules (~150 kDa, versus methotrexate at 454 Da). Consequences you must be able to reason out:
  - They **cannot be given orally** (they'd be digested) → hence **subcutaneous or intravenous** only. This is why every drug in the table is SC or IV, never a tablet.
  - They **cannot cross cell membranes** → so they can only hit **extracellular** targets (a cytokine floating in the interstitium, or a receptor on the cell surface). They can never inhibit an intracellular enzyme. *That* is the niche filled by the newer **small molecules** — apremilast (PDE4 inhibitor), tofacitinib/deucravacitinib (JAK/TYK2) — which are pills, not biologics.
  - They are cleared by **reticuloendothelial proteolysis**, not by liver CYP enzymes or kidney → hence **no dose adjustment for renal/hepatic function and almost no drug–drug interactions.** A huge practical advantage over methotrexate and cyclosporine.
  - Their half-lives are long (days to weeks) → hence dosing intervals of **weeks to months**, not daily.
- **"Targeted"** — high affinity for one epitope. This gives the **wide therapeutic index** and the ability to use them for decades.

### The immunogenicity story (the source's two bullet points, explained)

The source says early biologics were **murine-derived and short-acting because antimurine antibodies formed**, whereas current agents are **chimeric, humanized, or fully human**.

Here is the mechanism. If you inject a *mouse* protein into a *human*, the human immune system correctly identifies it as foreign and mounts an antibody response — **human anti-mouse antibodies (HAMA)**, or more generally **anti-drug antibodies (ADAs)**. These do two harmful things:
1. **Neutralise** the drug → loss of efficacy over time (clinically: "secondary failure" or loss of response)
2. **Form immune complexes** → infusion reactions, serum sickness, injection-site reactions

The engineering solution was progressive "de-mousing," and the **suffix of the drug name tells you exactly how far that process went** — an enormously useful exam tool:

| Suffix | Meaning | Example |
|---|---|---|
| **-omab** | fully **mo**use (murine) | (obsolete; most immunogenic) |
| **-ximab** | **chi**meric (≈25% mouse constant-region swap; variable region murine) | **Infliximab** |
| **-zumab** | **hu**manized (only the CDR loops are murine) | **Ustekinumab, Ixekizumab, Tildrakizumab, Risankizumab, Efalizumab** |
| **-umab** | fully **hu**man | **Adalimumab, Guselkumab, Secukinumab, Brodalumab** |
| **-cept** | **recept**or fusion protein (not an antibody at all!) | **Etanercept, Alefacept** |

> **Why this pays off:** You can now *predict* that **infliximab** (the only "-ximab") will be the most immunogenic, will most often cause **infusion reactions**, will most often show **loss of response**, and is the one agent for which we classically **co-prescribe low-dose methotrexate** to suppress ADA formation. You did not memorise that — you derived it.

---

## Part 4 — Classification: Reconciling the "Two Main Classes" Problem

The source states there are **"two main classes: TNF-α inhibitors and T-cell/APC-targeting agents,"** and then proceeds to discuss five categories. I want you to understand this apparent contradiction rather than be confused by it, because it is a fossil of medical history.

Around 2003–2005, there really were only two kinds of biologic for psoriasis:
1. Cytokine blockers → the **anti-TNF** agents
2. Cell-directed agents → **alefacept** and **efalizumab**, which attacked the T cell itself

That binary was accurate *then*. But efalizumab was withdrawn in 2009 and alefacept in 2011, while ustekinumab (2009), the IL-17 blockers (2015–2017), and the IL-23 blockers (2017–2019) arrived. So the "two main classes" line is **legacy text**, and modern references (Rook's 9e, Bolognia 4e, AAD–NPF 2019 guidelines) recognise **five categories**:

1. **TNF-α inhibitors** — etanercept, infliximab, adalimumab *(also certolizumab pegol, golimumab)*
2. **IL-12/23 (p40) inhibitor** — ustekinumab
3. **IL-23 (p19) inhibitors** — guselkumab, tildrakizumab, risankizumab
4. **IL-17 inhibitors** — secukinumab, ixekizumab, brodalumab *(also bimekizumab, anti-IL-17A/F)*
5. **T-cell/APC-targeting agents** — alefacept, efalizumab *(both withdrawn — historical only)*

> **Exam strategy:** Write the source's "two main classes" if you are answering from that text, but add one line: *"this reflects the early-biologic-era classification; contemporary practice recognises five classes."* That single sentence signals maturity of understanding rather than rote reproduction.

---

## Part 5 — Who Gets a Biologic? (Indications, with the reasoning behind each)

The source lists four indications. Let me make each one clinically meaningful.

**1. Moderate-to-severe psoriasis — PASI > 10, BSA > 10%**

This is the "**rule of tens**": disease is moderate-to-severe if **BSA > 10%**, *or* **PASI > 10**, *or* **DLQI > 10**.
- **BSA** — body surface area; one patient palm-plus-fingers ≈ 1%.
- **PASI** — Psoriasis Area and Severity Index (0–72). It scores **erythema, induration (thickness), and desquamation (scale)** on a 0–4 scale in each of four body regions, weighted by the area involved in that region. It is the standard trial endpoint: **PASI 75** means a 75% reduction from baseline. Note the shifting goalposts — with anti-TNF agents we celebrated PASI 75; with IL-17 and IL-23 agents the realistic target is now **PASI 90 or PASI 100 (complete clearance)**.

**2. Impaired quality of life (DLQI)**

This is not a soft endpoint — it is a *legitimate independent indication*. A patient with only 3% BSA involvement can be severely disabled if that 3% is on the **palms, soles, scalp, face, nails, or genitalia**. Palmoplantar disease destroys the ability to walk or work; genital disease destroys intimacy. This is why guidelines recognise **"special site" or "high-impact site" disease** as an indication for systemic therapy regardless of BSA. Psoriasis also carries real psychiatric burden — depression, anxiety, suicidal ideation — and independent cardiometabolic risk (the "**psoriatic march**": chronic systemic inflammation → insulin resistance → endothelial dysfunction → atherosclerosis → myocardial infarction). Treating the inflammation is therefore arguably treating the cardiovascular risk too.

**3. Patients who cannot receive conventional systemics** (methotrexate, cyclosporine, acitretin, PUVA)

"Cannot" covers: **contraindication** (MTX in liver disease, alcoholism, cytopenias, pregnancy; cyclosporine in hypertension or renal impairment; acitretin in women of childbearing potential — teratogenic with 3-year contraception requirement; PUVA in prior skin cancer or photosensitivity), **intolerance** (MTX nausea, cyclosporine tremor/gingival hyperplasia), or **cumulative dose ceiling reached** (cyclosporine >1–2 years risks irreversible nephropathy; PUVA >200 sessions risks SCC).

**4. Reasonable therapeutic options depleted**

This is the **step-therapy or "failure" criterion** most health systems (NICE, BAD, most insurers) impose — typically failure of at least two conventional systemics and/or phototherapy. You should understand this is as much an **economic** gate as a medical one. Biologics cost orders of magnitude more than methotrexate. The field is now moving toward **earlier intervention** — the "window of opportunity" hypothesis — arguing that early cytokine blockade may prevent progression to psoriatic arthritis and blunt the psoriatic march.

**5. Additional indications worth knowing (beyond the source list)**
- **Psoriatic arthritis (PsA)**, especially with axial or erosive disease — here biologics are *disease-modifying*, and **methotrexate is poorly effective for axial disease**. The presence of PsA often decides *which* biologic: anti-TNF and anti-IL-17 have strong joint data; **IL-23 inhibitors work for peripheral PsA but have failed in ankylosing spondylitis trials**.
- **Unstable, erythrodermic, or generalised pustular psoriasis** — here the *speed* of the intravenous agent matters, and **infliximab** is the classic rescue choice.

---

## Part 6 — The Prerequisite: Pre-Biologic Screening (and *why* each item exists)

The source's checklist looks like a list to memorise. It is actually a chain of logical consequences of one fact: **you are about to remove a specific arm of immune surveillance for months or years.**

| Requirement (source) | The mechanistic reason |
|---|---|
| **Age-appropriate history, physical exam, updated medication list** | You are screening for the four things biologics unmask: latent infection, occult malignancy, demyelinating disease, and heart failure. The medication list matters for overlap immunosuppression (e.g., thiopurine + infliximab → hepatosplenic T-cell lymphoma risk). |
| **Baseline investigations** | In practice: **CBC** (baseline for cytopenias), **LFT** (baseline for hepatotoxicity, esp. infliximab), **renal function**, **latent TB screening — Mantoux and/or IGRA (QuantiFERON/T-SPOT) plus chest radiograph**, **HBsAg / anti-HBc / anti-HCV**, **HIV serology**, **ANA** (baseline before a drug that can cause drug-induced lupus), **pregnancy test**, and a **lipid profile/metabolic panel** given the comorbidity burden. |
| **Periodic re-evaluation for malignancy and infection** | Because risk is *cumulative over exposure time*, not a one-time event. Practically: annual TB re-screening in endemic areas, age-appropriate cancer screening, and **full-skin examination** (relevant because these patients often have prior PUVA/ciclosporin exposure — a photocarcinogenesis history). |
| **Safer to avoid in pregnancy and children** | Standard textbook caution. But understand the nuance: IgG crosses the placenta **actively via the FcRn receptor**, mostly in the **second and third trimesters**. Therefore **certolizumab pegol**, which is a **pegylated Fab′ fragment lacking an Fc portion**, shows minimal placental transfer and is the preferred anti-TNF if a biologic is truly needed in pregnancy. Also: infants exposed *in utero* to full IgG biologics should **not receive live vaccines (e.g., BCG, rotavirus) for ~6 months** after birth. For children, note that **etanercept is the agent with the explicit paediatric psoriasis indication (4–17 years)** in this source — a high-yield discriminator. |
| **Contraindicated in serious active infection** | Absolute. Active TB, sepsis, deep fungal infection, untreated hepatitis B — treat these first. Anti-TNF agents given during active TB can cause fulminant, disseminated disease. |
| **Give killed/inactivated vaccines — hepatitis B, influenza, DPT. Do NOT give live vaccines** | This is the key safety principle, and here is *why*: a **killed or subunit vaccine** cannot replicate, so it is harmless — the only risk is a slightly blunted antibody response, which is why you vaccinate **≥2 weeks *before*** starting (ideally 4 weeks). A **live attenuated vaccine** — MMR, varicella, zoster (live Zostavax), oral polio, yellow fever, BCG, oral typhoid, intranasal influenza — *does* replicate, and in an immunomodulated host it can cause **disseminated vaccine-strain disease**. Give live vaccines **≥4 weeks before** starting, or defer. Note that the newer **recombinant zoster vaccine (Shingrix) is non-live and therefore permitted**. Add **pneumococcal** and **SARS-CoV-2** vaccines to the source's list in modern practice. |

> **Common misunderstanding to correct:** Students often say "biologics are safer than methotrexate, so screening doesn't matter." The opposite framing is correct: biologics are safer *for organs* (no liver, kidney, or marrow toxicity) but carry **specific immunological risks** that *only* appear if you fail to screen for them. The screening is precisely what makes them safe.

---

## Part 7 — Class 1: TNF-α Inhibitors

### Why TNF-α is a target

TNF-α (tumour necrosis factor alpha) is the prototypical pro-inflammatory cytokine, made by macrophages, dendritic cells, T cells, mast cells, and keratinocytes. In psoriasis, **TNF-α levels in lesional skin and serum correlate with disease severity**, as the source notes. It exists in **two forms** — soluble (cleaved by TACE/ADAM17) and **transmembrane** — and this distinction turns out to be the key to understanding the differences between the three drugs. TNF-α signals through **TNFR1 (p55)** and **TNFR2 (p75)**, activating **NF-κB** to switch on adhesion molecules, chemokines, and further cytokines. It is the *amplifier* of the psoriatic circuit, which is why blocking it improves skin, joints, gut, and eye inflammation simultaneously.

The source notes these agents are **used as monotherapy** in psoriasis — unlike in rheumatoid arthritis, where co-prescription of methotrexate is standard (in RA, MTX both adds efficacy and suppresses anti-drug antibodies; in psoriasis, MTX is still often combined with **infliximab** specifically, for the immunogenicity reason above).

### Class-wide adverse effects — reasoned out, not memorised

| Adverse effect (source) | The mechanism |
|---|---|
| **Opportunistic infection — TB reactivation, histoplasmosis, candidiasis, listeriosis, coccidioidomycosis** | This is the single most important class effect. **TNF-α is indispensable for granuloma formation and maintenance.** Granulomas are the walls that imprison dormant *M. tuberculosis*. Remove TNF-α and the walls dissolve → reactivation, often **extrapulmonary or disseminated (miliary)** and paucisymptomatic. This is why TB screening is mandatory and why **monoclonal antibodies (infliximab, adalimumab) carry higher TB risk than etanercept** — the antibodies bind transmembrane TNF on macrophages and lyse them, whereas etanercept only mops up soluble TNF. |
| **Neurological — new or worsened demyelinating disease (multiple sclerosis, optic neuritis)** | Paradoxical but reproducible. TNF-α blockade in MS trials worsened disease, likely because peripheral TNF blockade shifts the CNS cytokine environment and impairs regulatory mechanisms/remyelination. **Practical rule: a personal or strong family history of MS is a contraindication.** |
| **Autoimmunity — drug-induced SLE, positive ANA/anti-dsDNA** | Anti-TNF therapy shifts the balance toward **type I interferon** signalling and impairs clearance of apoptotic debris → exposure of nucleosomal self-antigen → autoantibody formation. Most patients seroconvert (ANA+) without disease; a minority develop cutaneous or systemic lupus-like illness, which resolves on withdrawal. |
| **Haematological — aplastic anaemia, leukopenia, thrombocytopenia** | Rare, idiosyncratic marrow suppression. Justifies periodic CBC. |
| **Hepatic — hepatic failure (source specifically bolds *infliximab*)** | Idiosyncratic autoimmune-type hepatitis; **infliximab is the strongest offender among anti-TNFs** — a deliberately emphasised exam pearl. Separately and critically: **all anti-TNF agents can reactivate hepatitis B**, which is why HBsAg *and* anti-HBc must be checked, with antiviral prophylaxis for carriers. |
| **Malignancy — lymphoma, melanoma and non-melanoma skin cancer** | Biologically plausible (TNF-α participates in tumour immunosurveillance) but the *attributable* risk is debated, because psoriasis itself, plus prior PUVA, cyclosporine, and methotrexate exposure, independently raise these risks. Consensus: **NMSC risk is modestly real** (do annual skin checks); lymphoma risk is small and largely confounded by underlying disease. **Caution with a history of melanoma or recent malignancy.** |
| **Cardiovascular — caution in NYHA Class III/IV congestive heart failure** | Derived from the **ATTACH trial**, where high-dose infliximab worsened outcomes in advanced heart failure. (Note the formatting: **NYHA Class III/IV**, capitalised Roman numerals — the source's lowercase "iii/iv" is a typographical slip.) |
| **Paradoxical psoriasis** *(not in source, but classic)* | Anti-TNF therapy can *induce* new psoriasis — often **palmoplantar pustular** — because removing TNF de-represses plasmacytoid dendritic cell IFN-α production. A beautiful illustration that cytokine networks are not linear. |

---

### 1️⃣ Etanercept

**What it is:** *Not an antibody.* Etanercept is a **dimeric fusion protein** — two copies of the **extracellular ligand-binding domain of human TNF receptor 2 (TNFR2/p75)** stitched to the **Fc portion of human IgG1**. The "-cept" suffix tells you this.

**How it works:** It functions as a **soluble decoy receptor**. It floats in the circulation and interstitium and **binds both soluble and membrane-bound TNF-α**, preventing them from reaching genuine cell-surface receptors. (It also binds lymphotoxin-α/TNF-β — a minor additional effect.)

> **Analogy:** Etanercept is a fleet of fake letterboxes scattered across the street. The letters (TNF-α) get posted into them and never arrive at the real house.

**Why this architecture matters clinically:** Because etanercept *binds* transmembrane TNF but binds it with **lower avidity and does not trigger complement-dependent or antibody-dependent cell killing** of TNF-expressing cells. Two consequences you can now predict:
- It has the **lowest TB reactivation risk** of the three anti-TNFs.
- It is **ineffective in Crohn's disease** — where killing the TNF-bearing gut mucosal cell appears to be necessary. *This is the classic exam discriminator: etanercept has no role in Crohn's; infliximab and adalimumab do.*

**Indications:** Moderate-to-severe plaque psoriasis · psoriatic arthritis · rheumatoid arthritis · ankylosing spondylitis/JIA · **paediatric psoriasis, ages 4–17** *(the source's stand-out paediatric agent)*.

**Dose:** **50 mg SC twice weekly × 12 weeks → then 50 mg SC once weekly.** (The 12-week induction front-loads drug exposure to achieve clearance, then steps down to a maintenance dose.)

**Characteristic adverse effect:** **Injection-site pruritus and reactions** — the most common complaint, typically mild, self-limited, and *not* a reason to stop. Efficacy is the most modest of the modern biologics (PASI 75 ≈ 45–50% at 12 weeks), but **its safety record is the longest and cleanest**, which is precisely why it retains a place in paediatrics.

---

### 2️⃣ Infliximab

**What it is:** A **human–murine chimeric IgG1κ monoclonal antibody** (≈75% human constant regions, ≈25% murine variable regions). The only "-ximab" on the list.

**How it works — a *dual* mechanism, which the source hints at:**
1. It **binds and neutralises soluble TNF-α**, preventing receptor activation.
2. Because it is an intact IgG1 with a functional Fc, it also binds **transmembrane TNF-α** and then **"destroys TNF-α-producing cells"** — the source's phrase, which specifically means **complement-dependent cytotoxicity (CDC)** and **antibody-dependent cellular cytotoxicity (ADCC)**, plus induction of apoptosis and reverse signalling in those cells.

> **Analogy:** Where etanercept mops up the spilled water, infliximab mops the water *and* smashes the tap. That extra destructive capacity explains both its greater potency and its greater infectious risk.

**Indications:** **Severe** plaque psoriasis (including erythrodermic and generalised pustular psoriasis, off-label but classic) · moderate-to-severe **psoriatic arthritis** · also RA, Crohn's disease, ulcerative colitis, ankylosing spondylitis.

**Dose:** **5 mg/kg by intravenous infusion at Weeks 0, 2, and 6, then every 6–8 weeks.** Note it is **weight-based** (the only one) and **intravenous** (the only one) — hence it requires a day-care facility, but delivers the **fastest onset of any anti-TNF**, often visible improvement within 1–2 weeks. That speed is exactly why it is the rescue drug for unstable, erythrodermic, or pustular psoriasis.

**Adverse effects:**
- **Infusion reactions** — acute (during/within 1 hour: flushing, urticaria, dyspnoea, hypotension) or delayed (3–12 days: serum-sickness-like arthralgia, myalgia, rash). Driven by **immunogenicity** — the direct consequence of being chimeric. Managed with slower infusion rates, premedication (antihistamine, paracetamol, steroid), and **concomitant low-dose methotrexate to suppress anti-drug antibodies**.
- **TB reactivation** — the highest risk of the class (transmembrane TNF binding + macrophage lysis).
- **Hepatotoxicity / hepatic failure** — the source bolds infliximab here.
- **Hepatosplenic T-cell lymphoma in children** — a rare, aggressive, usually fatal lymphoma carrying an **FDA black-box warning**, reported predominantly in **adolescent and young adult males with inflammatory bowel disease receiving infliximab together with a thiopurine (azathioprine/6-MP)**. The source's parenthetical "(children)" is therefore appropriate and important.
- **Loss of response over time** — again, immunogenicity.

---

### 3️⃣ Adalimumab

**What it is:** The first **fully human IgG1 monoclonal antibody** ("-umab"), produced by phage display.

**How it works:** Binds TNF-α with high affinity and **blocks its interaction with TNFR1 and TNFR2**. Being an intact IgG1, it also engages transmembrane TNF with CDC/ADCC capability — mechanistically closer to infliximab than to etanercept.

**Why "fully human" matters:** Markedly **lower immunogenicity than infliximab** (though anti-adalimumab antibodies still occur and still cause loss of response), and it is **subcutaneous**, so the patient self-injects at home. This combination of infliximab-like potency with etanercept-like convenience made it, for a decade, the most-used biologic in dermatology.

**Indications:** Moderate-to-severe plaque psoriasis · psoriatic arthritis · rheumatoid arthritis · **Crohn's disease** (and UC, AS, JIA, hidradenitis suppurativa, uveitis). *Note the Crohn's indication — the point of contrast with etanercept.*

**Dose — read this carefully, because the source's phrasing is ambiguous:**
The source says *"80 mg SC every week (loading), thereafter 40 mg every other week."* The approved regimen is:
> **80 mg SC as a *single* loading dose at Week 0 → 40 mg SC at Week 1 → then 40 mg SC every other week (every 2 weeks).**

The 80 mg is a **one-time loading dose**, not a weekly dose. The purpose of loading is to reach steady-state serum concentration rapidly rather than waiting 4–5 half-lives. (In Crohn's disease the loading dose is higher still — 160 mg then 80 mg.)

**Adverse effects:** Injection-site reactions · **lupus-like syndrome** · **demyelination/multiple sclerosis** · **congestive heart failure** · **tuberculosis**. The source re-lists the class effects under adalimumab specifically — treat that as deliberate emphasis for recall, not as a claim that these are unique to adalimumab.

---

## Part 8 — Class 2: The IL-12/23 Inhibitor — Ustekinumab

**The target — and the elegant trick.** Recall from Part 2 that **IL-12 = p35 + p40** and **IL-23 = p19 + p40**. Ustekinumab is a **fully human IgG1κ monoclonal antibody directed against the shared p40 subunit**. By binding p40, it prevents *either* cytokine from engaging its receptor (specifically the shared **IL-12Rβ1** chain). With one antibody you therefore silence **both the Th1 axis (via IL-12) and the Th17 axis (via IL-23)**.

> **Analogy:** IL-12 and IL-23 are two different keys that happen to share an identical *handle* (p40). Ustekinumab is a glove that grips that handle — so neither key can be turned, without you needing to know anything about the blades.

**Why it was a paradigm shift:** Blocking a **proximal, upstream** cytokine rather than a downstream amplifier produced deeper, more durable responses — and, because IL-23 is the *survival* factor for pathogenic Th17 cells, response persists long after drug levels fall. Hence the extraordinary dosing interval.

**Dose (weight-banded — a favourite exam detail):**
- **< 100 kg → 45 mg SC**
- **> 100 kg → 90 mg SC**
- **Both given at Week 0 and Week 4, then every 12 weeks.**

Four injections per year. Consider what that does for adherence in a lifelong disease — this is arguably the single greatest practical advantage of the drug. (Weight banding exists because these are large molecules distributed in plasma volume; heavier patients dilute a fixed dose below the therapeutic threshold. The same principle explains reduced efficacy of most biologics in obesity.)

**Adverse effects (source):** upper respiratory tract infection · headache · injection-site reactions · infections generally · **herpes simplex reactivation** · arthralgia (joint pain) · **NVD**.

> **A note on "NVD":** In this dermatological context, **NVD = nausea, vomiting, diarrhoea** (gastrointestinal upset). Do *not* confuse it with the obstetric abbreviation "normal vaginal delivery" — a genuine source of confusion in Indian examination notes. Always expand abbreviations in your written answer.

**Safety profile in perspective:** Ustekinumab has proved remarkably safe over a decade-plus of registry data, with **notably lower TB and serious-infection signal than anti-TNF agents** (IL-12/23 blockade impairs granuloma maintenance less than TNF blockade does, though TB screening is still mandatory). One theoretical caution: because IL-12/IFN-γ signalling contributes to tumour surveillance and because p40 blockade touches the Th1 arm, a cardiovascular/major-adverse-event signal was investigated early on and **not confirmed**.

---

## Part 9 — Class 3: The IL-23 (p19) Inhibitors

### The conceptual leap

If ustekinumab taught us that upstream blockade is powerful, the obvious next question was: *do we need to block IL-12 at all?* Blocking IL-12 removes Th1/IFN-γ responses, which are **useful** — they defend against intracellular organisms and contribute to tumour surveillance. Meanwhile the *pathogenic* signal in psoriasis is IL-23 driving Th17.

Solution: build antibodies against the **p19 subunit**, which is **unique to IL-23**. The result is **selective IL-23 blockade with IL-12 left completely intact** — greater precision, arguably better safety, and (because you are hitting the *master regulator* that maintains the pathogenic Th17 population) the **most durable responses and longest dosing intervals of any class**. IL-23 blockade appears to reduce the pool of **tissue-resident memory T cells** in the skin, which is why some patients maintain clearance for many months after stopping.

> **Analogy:** Ustekinumab cuts the trunk of a tree with two main branches (Th1 and Th17). The p19 inhibitors saw off *only* the diseased branch, leaving the healthy one to keep working.

| Drug | Antibody type | Target | Dose |
|---|---|---|---|
| **Guselkumab** | Fully human **IgG1λ** | IL-23 **p19** | **100 mg SC at W0, W4 → then every 8 weeks** |
| **Tildrakizumab** | Humanized **IgG1κ** | IL-23 **p19** | **100 mg SC at W0, W4 → then every 12 weeks** |
| **Risankizumab** | Humanized **IgG1** | IL-23 **p19** | **150 mg SC at W0, W4 → then every 12 weeks** |

**Important completeness point:** The source lists risankizumab simply as *"SC 150 mg every 12 weeks"* and **omits the loading doses**. The approved regimen includes **150 mg at Week 0 and Week 4** before shifting to the 12-weekly schedule — the same loading logic as every other agent. Do not reproduce the omission.

**Also note:** the source says tildrakizumab's "MOA is similar to guselkumab" — mechanistically true (both anti-p19). But they are *not* interchangeable: they differ in antibody backbone (IgG1λ vs IgG1κ), affinity, and pharmacokinetics, which is why **guselkumab is 8-weekly and tildrakizumab is 12-weekly**. Mechanism identical; pharmacokinetics distinct.

**Adverse effects:** Strikingly bland — **upper respiratory tract infections and injection-site reactions**, with headache and arthralgia. No candidiasis signal (contrast IL-17 blockers), no demyelination signal, no heart-failure signal, low TB signal. In efficacy terms this class delivers among the highest **PASI 90/100 rates** with among the **fewest injections per year** — which is why, in 2024 practice, IL-23 inhibitors have become the default first-line biologic for uncomplicated plaque psoriasis.

**Practical caveat:** IL-23 inhibitors are excellent for skin and effective for **peripheral** psoriatic arthritis, but have **failed in axial spondyloarthritis/ankylosing spondylitis trials**. If your patient has inflammatory back pain, choose an anti-TNF or an IL-17 inhibitor instead. This is a genuinely high-yield clinical decision point.

---

## Part 10 — Class 4: The IL-17 Inhibitors

### Why this class feels different in the clinic

IL-17A is the **final effector cytokine** — the very molecule the keratinocyte receptor detects. Block it and you interrupt the pathway at its last step, which is why the source's statement is correct and important:

> **"IL-17 inhibitors induce faster reduction in PASI than TNF-α inhibitors."**

This is not a soft claim; it comes from **head-to-head randomised trials** (e.g., **FIXTURE** and **ERASURE** for secukinumab, **UNCOVER-2/-3** and **IXORA-S** for ixekizumab) in which IL-17 blockers **beat etanercept and ustekinumab** on PASI 75/90 at Week 12, often with visible improvement within **1–2 weeks**. Mechanistically: blocking the last messenger produces an immediate effect, whereas blocking an upstream survival factor (IL-23) must wait for the existing Th17 population to decay.

> **Analogy:** Blocking IL-23 is cutting the factory's power supply — production stops, but the goods already on the conveyor belt still arrive. Blocking IL-17A is intercepting the delivery truck at the door — nothing gets through today.

### The three agents (note the crucial difference in the third)

| Drug | Molecular identity | Target | Dosing |
|---|---|---|---|
| **Secukinumab** | Fully **human IgG1κ** | **IL-17A** (the cytokine) | 300 mg SC at W0, 1, 2, 3, 4 → then **300 mg monthly** |
| **Ixekizumab** | **Humanized IgG4** | **IL-17A** (the cytokine) | **160 mg (2 × 80 mg) at W0 → 80 mg q2wk to W12 → then 80 mg monthly** |
| **Brodalumab** | Fully **human IgG2** | **IL-17 receptor A (IL-17RA)** | 210 mg SC at W0, 1, 2 → then **210 mg q2wk** |

The source gives details only for **ixekizumab**, listing **secukinumab and brodalumab under "Others"** — signalling awareness-level knowledge. But you must know the mechanistic distinction:

- **Secukinumab and ixekizumab neutralise the ligand IL-17A** — one specific cytokine.
- **Brodalumab blocks the receptor subunit IL-17RA** — and because IL-17RA is a shared component used by **IL-17A, IL-17A/F heterodimer, IL-17F, IL-17C, and IL-17E (IL-25)**, brodalumab achieves the **broadest IL-17 pathway blockade** of any agent. Greater breadth, greater potency — and the reason it carries a distinct safety profile.

**Ixekizumab, per the source:** a **humanized IgG4 monoclonal antibody that selectively binds IL-17A and neutralises it**, inhibiting the downstream inflammatory response. The source lists identical regimens for plaque psoriasis and PsA (**160 mg at Week 0, then 80 mg monthly**) — as the margin note observes, this probably reflects the two separate regulatory indications being quoted rather than a genuine difference. (In the official label, the *psoriasis* regimen has an extra every-2-week phase through Week 12, then monthly; the PsA regimen goes 160 mg → 80 mg every 4 weeks from the start. Worth knowing but not worth losing marks over.)

### Adverse effects of IL-17 inhibitors — every one of them mechanistically predictable

| Adverse effect | Why it happens |
|---|---|
| **Mucocutaneous candidiasis** (oral, oesophageal, vulvovaginal) | **This is the signature class effect, and it is beautiful immunology.** IL-17 is the principal cytokine defending *mucosal surfaces* against *Candida* — it recruits neutrophils and induces epithelial antimicrobial peptides. The natural experiment that proves it: patients with **autosomal dominant hyper-IgE syndrome (STAT3 deficiency)**, **IL-17F/IL-17RA mutations**, or **APECED with anti-IL-17 autoantibodies** all present with **chronic mucocutaneous candidiasis**. Block IL-17 pharmacologically and you reproduce a mild, iatrogenic version of that phenotype. Reassuringly, it is almost always **superficial and topically treatable (fluconazole/nystatin)**, not invasive — because *systemic* antifungal defence depends on other pathways. |
| **Mild injection-site reactions** | Standard for SC biologics. |
| **Transient neutropenia** | Usually Grade 1–2, asymptomatic, self-limiting; IL-17 drives G-CSF and neutrophil granulopoiesis, so blocking it modestly lowers counts. Rarely clinically significant. |
| **New onset or exacerbation of inflammatory bowel disease** *(not in source — but essential)* | Another mirror-image of physiology: in the **gut**, IL-17 is **protective**, maintaining tight junctions and epithelial barrier integrity. Remove it and colitis can flare. **Practical rule: IL-17 inhibitors are relatively contraindicated in a patient with psoriasis plus Crohn's disease or UC — choose an anti-TNF or anti-IL-23 instead.** (Note the perfect exam symmetry: etanercept fails in IBD; IL-17 blockers can *worsen* IBD; infliximab/adalimumab/ustekinumab/risankizumab *treat* IBD.) |
| **Brodalumab-specific: suicidal ideation and behaviour** *(not in source)* | Cases during trials led to an **FDA black-box warning and a REMS programme**, and brodalumab was consequently never launched in some markets. Causality remains unproven (psoriasis itself carries high depression prevalence), but you must **screen for depression and suicidality before and during brodalumab therapy**. This explains why the source relegates brodalumab to "Others." |
| **Upper respiratory infections** | Modest, mucosal-immunity-related. |

**Where IL-17 inhibitors shine clinically:** rapid clearance, excellent for **psoriatic arthritis including axial disease**, and the class of choice for **generalised pustular** and **erythrodermic** presentations (given IL-17's role in neutrophil recruitment) and for patients needing fast results (weddings, examinations, severe QoL impact).

---

## Part 11 — Class 5: T-Cell/APC-Targeting Agents (Historical, but Examinable)

These two are gone from the market, yet they remain in every syllabus — partly for history, partly because the *reasons* they disappeared teach permanent lessons.

### Alefacept

- **Structure:** A **dimeric fusion protein** ("-cept") — the first extracellular domain of **LFA-3 (CD58)** fused to the **Fc of human IgG1**.
- **Mechanism:** It binds **CD2** on T cells. This does two things: it **competitively blocks the LFA-3/CD2 costimulatory interaction**, inhibiting T-cell activation; and via its Fc it engages NK-cell FcγRIII, triggering **apoptosis of CD2-high cells** — which happen to be **memory-effector (CD45RO⁺) T cells**, precisely the pathogenic population. Hence the source's wording: *"inhibits T-cell activation and reduces memory effector T cells by binding CD2."*
- **Distinctive feature:** It produced **remissions that outlasted therapy** — because it physically depleted the memory T-cell pool. Efficacy, however, was modest and slow (12-week courses), and it required **CD4 count monitoring** (dose withheld if CD4 < 250).
- **Why withdrawn:** **Voluntarily withdrawn from the US market in 2011 by Astellas for commercial reasons — not for safety.** That nuance is worth a mark.

### Efalizumab

- **Structure:** A **humanized IgG1 monoclonal antibody** ("-zumab") against **CD11a**, the α-subunit of **LFA-1 (CD11a/CD18)**.
- **Mechanism:** By binding CD11a, it blocks the **LFA-1 ↔ ICAM-1** interaction. This has three effects: it prevents T-cell **activation** (LFA-1 is a costimulatory molecule at the APC interface), prevents **adhesion to endothelium and transmigration into skin**, and prevents T-cell **retention within the dermis**. So it works by **keeping T cells out of the skin**.
- **Why withdrawn — and this is the vital lesson:** **Withdrawn worldwide in 2009 because of four cases of progressive multifocal leukoencephalopathy (PML)** — a fatal demyelinating brain infection caused by reactivation of the **JC polyomavirus**. Mechanistically inevitable in hindsight: the drug blocked **lymphocyte trafficking into tissues, including the CNS**, thereby abolishing the immune surveillance that keeps JC virus latent. (The identical problem afflicts **natalizumab**, an anti-α4-integrin agent used in MS — same trafficking mechanism, same complication.)
- Efalizumab also suffered **rebound flares — often erythrodermic or pustular — on abrupt withdrawal**, another practical reason for its disappearance.

> **The permanent lesson:** *Targeting a cell's ability to travel is riskier than targeting a single cytokine it secretes.* Cytokine networks are redundant; trafficking is not. This is why the entire field moved decisively from **cell-directed** to **cytokine-directed** therapy — and why every successful modern biologic in psoriasis is an anti-cytokine agent.

---

## Part 12 — Putting It Together: The Comparative Master Table

| Class | Drug | Molecular nature | Target | Route | Dosing | Signature adverse effects |
|---|---|---|---|---|---|---|
| **Anti-TNF-α** | **Etanercept** | Dimeric TNFR2–IgG1 **fusion protein** | Soluble + membrane TNF-α (decoy receptor) | SC | 50 mg **twice weekly × 12 wk** → 50 mg weekly | Injection-site reactions; lowest TB risk; **paediatric-approved 4–17 y**; **ineffective in Crohn's** |
| | **Infliximab** | **Chimeric** IgG1κ mAb | TNF-α (neutralises + **CDC/ADCC kills TNF-producing cells**) | **IV infusion** | **5 mg/kg at W0, 2, 6 → q6–8 wk** | **Infusion reactions, TB reactivation, hepatic failure, hepatosplenic T-cell lymphoma (children on thiopurines)**; fastest onset → rescue drug |
| | **Adalimumab** | **Fully human** IgG1 mAb | TNF-α | SC | **80 mg loading at W0 → 40 mg q2wk** | Injection-site reactions, **lupus-like syndrome, demyelination/MS, CHF, TB**; approved in Crohn's |
| **Anti-IL-12/23** | **Ustekinumab** | Fully human IgG1κ mAb | **p40** (shared by IL-12 **and** IL-23) | SC | **45 mg (<100 kg) / 90 mg (>100 kg) at W0, W4 → q12wk** | URTI, headache, injection-site reactions, **HSV reactivation**, arthralgia, **nausea/vomiting/diarrhoea**; only 4 doses/year |
| **Anti-IL-23** | **Guselkumab** | Fully human IgG1**λ** | **p19** (IL-23 only) | SC | **100 mg at W0, W4 → q8wk** | URTI, injection-site reactions |
| | **Tildrakizumab** | Humanized IgG1**κ** | **p19** | SC | **100 mg at W0, W4 → q12wk** | URTI, injection-site reactions |
| | **Risankizumab** | Humanized IgG1 | **p19** | SC | **150 mg at W0, W4*** → q12wk | URTI, injection-site reactions |
| **Anti-IL-17** | **Ixekizumab** | **Humanized IgG4** | **IL-17A** | SC | **160 mg (80 × 2) at W0 → 80 mg monthly** | **Mucocutaneous candidiasis**, transient neutropenia, injection-site reactions, ?IBD flare |
| | **Secukinumab** | Fully human IgG1κ | **IL-17A** | SC | 300 mg W0–4 weekly → monthly | As above |
| | **Brodalumab** | Fully human IgG2 | **IL-17 receptor A** (blocks IL-17A, F, A/F, C, E) | SC | 210 mg W0, 1, 2 → q2wk | Candidiasis; **black-box: suicidal ideation** |
| **T-cell targeting** *(withdrawn)* | **Alefacept** | LFA-3–IgG1 fusion protein | **CD2** → blocks activation + depletes memory-effector T cells | IM/IV | — | **Withdrawn 2011 — commercial, not safety** |
| | **Efalizumab** | Humanized IgG1 mAb | **CD11a (LFA-1)** → blocks T-cell adhesion/trafficking | SC | — | **Withdrawn 2009 — fatal PML (JC virus)**; rebound flares |

\* *Loading doses at W0 and W4 are omitted in the source text for risankizumab — include them.*

---

## Part 13 — Common Misunderstandings (Please Do Not Make These)

1. **"Etanercept is a monoclonal antibody."** No. It is a **receptor–Fc fusion protein**. The suffix **-cept** always means fusion protein. This is why it lacks the cell-lytic capacity of true antibodies and why it fails in Crohn's disease.

2. **"p40 and p19 are interchangeable terms."** Emphatically not. **p40 is *shared* by IL-12 and IL-23** → ustekinumab blocks both. **p19 is *unique* to IL-23** → guselkumab/tildrakizumab/risankizumab block only IL-23, sparing IL-12/Th1 immunity. One subunit; two entirely different immunological consequences.

3. **"IL-17 inhibitors all work the same way."** Secukinumab and ixekizumab neutralise the **cytokine IL-17A**. Brodalumab blocks the **receptor IL-17RA**, therefore blocking *multiple* IL-17 family members. Broader blockade, different safety profile.

4. **"Faster is better, so always choose an IL-17 inhibitor."** Speed is one variable. **Durability, injection frequency, comorbidity, and safety** are equally important. In a patient with coexisting **Crohn's disease**, an IL-17 inhibitor is the *wrong* choice despite its speed. In a patient with **latent TB and heart failure**, an anti-TNF is the wrong choice. **Comorbidity, not potency, should drive selection** — and that is the mark of a clinician rather than a prescriber.

5. **"Withdrawn means dangerous."** Not necessarily. **Efalizumab** was withdrawn for a fatal safety reason (PML). **Alefacept** was withdrawn purely for **commercial** reasons. Stating this distinction demonstrates real knowledge.

6. **"Biologic and biosimilar are the same thing."** A **biosimilar** is a highly similar — not identical — version of an approved reference biologic, manufactured by a different company after patent expiry (e.g., etanercept and adalimumab biosimilars are now widespread and have dramatically improved global access). Because they are large proteins made in living cells, they can never be "generic" in the chemical sense; they require comparative clinical trials.

7. **"Biologics cure psoriasis."** They **control** it. Psoriasis reflects a genetically determined immune architecture (**HLA-Cw6/PSORS1**, *IL23R*, *IL12B*, *TNIP1*, *CARD14* variants). Withdraw the drug and, in most patients, disease returns — though IL-23 inhibitors come closest to producing prolonged drug-free remission, plausibly by depleting cutaneous tissue-resident memory T cells.

8. **"Live vaccines are just less effective in these patients."** No — they are **contraindicated**, because attenuated organisms can **replicate and disseminate**. Killed/subunit vaccines are merely *less immunogenic*, and are actively recommended. Get all vaccines in **before** you start.

---

## Part 14 — Summary Anchor: The Core Idea in One Picture

Hold this single mental image, and you can reconstruct the whole answer:

> **Picture the psoriatic pathway as a relay race with a loudspeaker.**
>
> The **dendritic cell** starts the race by handing over **IL-12** (→ Th1) and **IL-23** (→ Th17). The **Th17 cell** carries the baton and hands the final message, **IL-17A**, to the **keratinocyte**, which responds by proliferating, summoning neutrophils, and calling in new blood vessels — producing the red, thick, scaly plaque. And running over the whole stadium is the **TNF-α loudspeaker**, amplifying every hand-off and feeding the message back to the start, which is why the race never ends.
>
> Every biologic is simply a hand placed at one point on that track:
> - **Silence the loudspeaker** → **anti-TNF** (etanercept, infliximab, adalimumab) — broad, effective, oldest, but you lose granuloma integrity (**TB**), risk demyelination, lupus, and CHF.
> - **Grab the shared handle of both starting batons (p40)** → **ustekinumab** — blocks Th1 *and* Th17, only four injections a year.
> - **Grab only the diseased baton (p19)** → **IL-23 inhibitors** — the most selective and most durable; upstream master-switch blockade; excellent safety, but weak in **axial** arthritis.
> - **Intercept the final hand-off (IL-17A or its receptor)** → **IL-17 inhibitors** — the **fastest** clearance of all, but because IL-17 also guards mucosa and gut, you inherit **candidiasis** and possible **IBD flare**.
> - **Remove the runner itself** → **alefacept (CD2), efalizumab (CD11a)** — logical, but blocking cell *trafficking* cost us immune surveillance and gave us **PML**. Both withdrawn; the field learned to target **cytokines, not cells**.
>
> And wrapping all of it: **screen before you start** (TB, hepatitis B/C, HIV, malignancy, heart failure, demyelination, pregnancy), **vaccinate before you start — killed yes, live never**, and **choose the agent by the patient's comorbidities, not by the drug's PASI score.**

If you can draw that relay race on a page and hang the eleven drug names on it with their doses, you have answered this question completely — and, more importantly, you will be able to *choose* a biologic for a real patient, which is the point of learning it at all.