# Refsum's Disease — A Mini-Lecture

## 1. Orientation: Why This Disease Deserves Your Attention

Let me start with a confession about why I love teaching Refsum's disease.

Most of the ichthyoses you study are *structural* problems — a faulty keratin, a broken transglutaminase, a lipid transporter that won't do its job. The skin is scaly because a brick or a mortar component is defective. Refsum's disease is different. Here, the skin is scaly because **the patient has been slowly poisoned by their own breakfast.**

That is not hyperbole. Refsum's disease is a **metabolic traffic jam**. A single fatty acid — phytanic acid — that comes *entirely from food* cannot be broken down. It backs up in the plasma, then seeps into every lipid-rich membrane in the body: the retina, the myelin sheaths of peripheral nerves, the cochlea, the heart muscle, and the stratum corneum. Wherever it lodges, it behaves like a structurally "wrong-shaped" molecule jammed into a precision-built membrane, and that tissue begins to fail.

So the disease gives you a beautiful lesson in **one molecule → many organs**, and — most satisfyingly — it is one of the very few ichthyoses where you can treat the patient with a **diet sheet** rather than a tube of cream.

Hold that idea in your head as the organizing principle for everything that follows.

---

## 2. Definition and the Name

**Refsum's disease** (classical or adult Refsum disease, ARD) is an **ultra-rare autosomal recessive neurocutaneous lipid storage disorder** — specifically a **peroxisomal single-enzyme disorder** — caused by failure of **α-oxidation of phytanic acid**, leading to its accumulation in tissues.

Its classical eponym, coined by the Norwegian neurologist **Sigvald Refsum in 1946**, is:

> **Heredopathia atactica polyneuritiformis**

This mouthful is actually a free diagnosis if you dissect it:

| Fragment | Meaning | Clinical translation |
|---|---|---|
| *heredo-pathia* | inherited disease | autosomal recessive |
| *atactica* | ataxic | cerebellar ataxia |
| *polyneuriti-formis* | resembling polyneuritis | peripheral neuropathy |

Notice what the eponym **omits**: the eyes and the skin. Refsum was a neurologist, and he named the disease after what a neurologist sees. The dermatologist and the ophthalmologist must add the other two limbs of the tetrad.

### The Classical Tetrad (memorise this)

1. **Deteriorating vision** — retinitis pigmentosa
2. **Peripheral neuropathy**
3. **Cerebellar ataxia**
4. **Mild ichthyosis**

> **A framing point for exams:** in Refsum's disease the ichthyosis is the *quietest* feature. The neurological and ophthalmological findings dominate. The dermatologist's role is often to be the person who recognises that a "mild ichthyosis vulgaris" in a child who is going blind and deaf is not a coincidence.

---

## 3. The Biochemistry — The Heart of the Lecture

Everything in Refsum's disease flows from one blocked reaction. If you understand this section, you can *derive* the rest of the disease rather than memorise it.

### 3.1 What is phytanic acid, and where does it come from?

**Phytanic acid** is **3,7,11,15-tetramethylhexadecanoic acid** — a 16-carbon fatty acid with **four methyl branches** sticking off its side, including one critically placed at **carbon 3 (the β-carbon)**.

Its origin is **exclusively dietary**. Humans have **no biosynthetic pathway** for it. It derives from **phytol**, the long lipid tail of the **chlorophyll** molecule.

Here is the food chain — and it matters clinically:

> **Chlorophyll in green plants** → eaten by a **ruminant** (cow, sheep, goat) → **rumen bacteria cleave phytol free** from chlorophyll → the ruminant absorbs phytol and oxidises it to phytanic acid → phytanic acid is **stored in the animal's fat and secreted in its milk** → **the human eats the meat, butter, cheese, or milk.**

So the major human dietary sources are:
- **Dairy fat** (butter, cheese, cream, whole milk) — the biggest contributor
- **Ruminant meat and fat** (beef, lamb, mutton)
- **Certain fatty fish** (tuna, cod, haddock, herring) — because the marine food chain begins with chlorophyll-containing phytoplankton

**An important nuance that your textbook compresses:** green vegetables themselves contribute comparatively **little** phytanic acid, because the human gut is poor at liberating phytol from intact chlorophyll — we lack the rumen bacteria that do the work. The phrase "exclude chlorophyll from the diet" is a *simplified shorthand* for "exclude the animal products that concentrate chlorophyll-derived phytanic acid." I will return to this under Treatment.

### 3.2 Why can't phytanic acid simply be β-oxidised like any other fatty acid?

This is the mechanistic crux. Let's walk through **β-oxidation**, the standard fatty-acid disposal line:

1. Attach CoA to the carboxyl end.
2. **Dehydrogenate** between C2 (α) and C3 (β) to make a double bond.
3. **Hydrate** it — put a hydroxyl **on C3 (β)**.
4. **Oxidise that hydroxyl to a ketone** on C3.
5. **Thiolytic cleavage** releases acetyl-CoA; repeat.

Step 4 is the problem. To make a ketone at C3, that carbon **must be able to hold a double bond to oxygen**, which requires it to have hydrogens available. In phytanic acid, **C3 is already occupied by a methyl group**. It is a **quaternary-blocked carbon** — sterically and chemically, the β-oxidation machinery cannot perform its chemistry there.

> **Analogy:** β-oxidation is like a machine that chews a rope two feet at a time, but it must grip the rope at a specific point each cycle. Phytanic acid has a **knot exactly at the gripping point**. The machine stalls. You cannot force it — you must first **shorten the rope by one foot** so the knot falls in a place the machine can tolerate.

### 3.3 Enter α-oxidation — the peroxisomal workaround

Nature's solution is to **remove a single carbon from the carboxyl end** first. This shifts the troublesome methyl branch from **C3 (β, forbidden)** to **C2 (α, tolerated)**. β-oxidation *can* handle an α-methyl branch. This one-carbon shortening is **α-oxidation**, and it happens inside the **peroxisome**.

The pathway, step by step:

| Step | Reaction | Enzyme |
|---|---|---|
| 1 | Phytanic acid → **phytanoyl-CoA** | Very-long-chain acyl-CoA synthetase |
| 2 | Phytanoyl-CoA → **2-hydroxyphytanoyl-CoA** | ⭐ **Phytanoyl-CoA hydroxylase (PhyH)** |
| 3 | Cleavage → **pristanal + formyl-CoA** | 2-hydroxyphytanoyl-CoA lyase |
| 4 | Pristanal → **pristanic acid** | Aldehyde dehydrogenase |
| 5 | Pristanic acid → shortened via **peroxisomal β-oxidation** (3 rounds), then handed to mitochondria for completion | Peroxisomal β-oxidation enzymes |

**Step 2 is the rate-limiting, disease-defining step.** Phytanoyl-CoA hydroxylase (EC 1.14.11.18) is an **iron(II)- and 2-oxoglutarate-dependent dioxygenase** — meaning it needs iron and α-ketoglutarate as co-substrates, and it inserts a hydroxyl at C2.

> **Why the peroxisome?** Peroxisomes are the cell's specialist workshop for awkward lipids — very-long-chain fatty acids, branched-chain fatty acids, plasmalogen synthesis, bile acid intermediates. Think of the mitochondrion as the **high-volume factory floor** handling standard parts, and the peroxisome as the **bespoke machine shop** that pre-processes odd-shaped items until they are standard enough for the factory. Phytanic acid must visit the machine shop first.

---

## 4. The Genetics — Two Ways to Break the Same Step

There are **two genes**, and here is the elegant part: **both disable the same reaction, but at different levels — the worker or the delivery system.**

| Gene | Locus | Protein | How it breaks α-oxidation | Approx. share |
|---|---|---|---|---|
| ***PHYH*** (*PAHX*) | **10p13** | **Phytanoyl-CoA hydroxylase** | The **enzyme itself is deficient/non-functional** — direct catalytic failure | ~90% of cases |
| ***PEX7*** | **6q23** | **Peroxin 7 (PTS2 import receptor)** | The enzyme is made normally but **cannot be imported into the peroxisome**; it is stranded in the cytosol, away from its substrate and co-factors | ~10% of cases |

### The PEX7 story, explained properly

Proteins destined for the peroxisomal matrix carry an address label called a **peroxisomal targeting signal (PTS)**. There are two flavours:
- **PTS1** — recognised by the receptor **PEX5**
- **PTS2** — recognised by the receptor **PEX7**

**Phytanoyl-CoA hydroxylase carries a PTS2 label.** Therefore, if **PEX7** is defective, PhyH never gets through the peroxisomal door.

> **Analogy:** Imagine a skilled surgeon (PhyH) who can only operate inside a secure operating theatre (the peroxisome), and entry requires a badge-reader (PEX7) that reads their specific ID type (PTS2). In *PHYH* disease, the surgeon is incompetent. In *PEX7* disease, the surgeon is perfectly capable but **locked out of the building**. The patient on the table suffers identically either way.

**This is a beautiful exam concept:** *the same clinical phenotype from an enzyme defect or from a protein-trafficking defect.*

### Pathogenesis flowchart (convergent pathways)

```
   Mutation in PHYH (10p13)                  Mutation in PEX7 (6q23)
              │                                        │
   Deficient phytanoyl-CoA                 Defective PTS2 import receptor
        hydroxylase                                    │
              │                            PhyH cannot ENTER the peroxisome
              │                                        │
              └────────────────┬───────────────────────┘
                               ▼
              IMPAIRED α-OXIDATION OF PHYTANIC ACID
                               ▼
        Phytanic acid cannot be shortened → cannot enter β-oxidation
                               ▼
     ACCUMULATION of phytanic acid in plasma, adipose tissue, and
       lipid-rich membranes (retina, myelin, cochlea, myocardium,
                      liver, kidney, stratum corneum)
                               ▼
     Phytanic acid SUBSTITUTES for normal fatty acids in membrane
       phospholipids → altered membrane fluidity, thickness,
        protein function, and lipid-lamellar architecture
                               ▼
           Progressive multi-system dysfunction = REFSUM'S DISEASE
```

### A vital genetic aside — the PEX7 allelic spectrum

*PEX7* mutations exist on a **severity spectrum**:
- **Severe, near-complete loss of PEX7 function** → **Rhizomelic chondrodysplasia punctata type 1 (RCDP1)** — a devastating infantile disease with proximal limb shortening, cataracts, stippled epiphyses, profound developmental delay, and **deficient plasmalogens** (because plasmalogen-synthesising enzymes also use PTS2).
- **Mild, residual-function PEX7 mutations** → an **adult Refsum-like phenotype**.

This explains a practical laboratory point: in *PHYH* disease, **red-cell plasmalogens are normal**; in *PEX7* disease, they may be **mildly reduced**. That is how a biochemistry lab distinguishes the two.

---

## 5. Why *These* Organs? Deriving the Clinical Picture From the Chemistry

Do not memorise the symptom list. **Derive it.** Ask: *which tissues depend most critically on precisely-tuned lipid membranes?*

| Tissue | Why it is lipid-critical | Resulting clinical feature |
|---|---|---|
| **Retinal photoreceptors** | Rod outer-segment discs are the most lipid-dense membranes in the body, rich in DHA, and are continuously renewed; phytanic acid also structurally resembles **phytol/retinoid** molecules and interferes with retinol/retinoid handling in the RPE | **Retinitis pigmentosa** — night blindness → ring scotoma → tunnel vision → blindness |
| **Peripheral nerve myelin** | Myelin is ~70–80% lipid; Schwann cells must maintain enormous, precisely packed membrane spirals | **Hypertrophic demyelinating sensorimotor polyneuropathy** with onion-bulb formation |
| **Cerebellum & its afferents** | Dependent on intact large-fibre proprioceptive input plus intrinsic cell dysfunction | **Cerebellar ataxia** (partly *sensory* ataxia from neuropathy) |
| **Cochlea & olfactory epithelium** | High-turnover neuroepithelia with delicate membrane machinery | **Sensorineural hearing loss with tinnitus; anosmia and impaired taste** |
| **Cardiac myocytes & conduction tissue** | Membrane fluidity governs ion-channel and gap-junction function | **Cardiomyopathy and arrhythmias** — the leading cause of death |
| **Stratum corneum** | The barrier *is* a lipid structure (lamellar bilayers + corneocyte lipid envelope) | **Mild ichthyosis vulgaris–like scaling** |
| **Growing epiphyses** | Chondrocyte/skeletal development is peroxisome-dependent | **Shortened 4th metatarsals**, epiphyseal dysplasia (≈30%) |

> **Key mechanistic sentence to write in an exam:** *"Phytanic acid is a branched-chain fatty acid that, when it accumulates, is esterified into membrane phospholipids in place of normal straight-chain fatty acids; its methyl branches disrupt tight lipid packing, altering membrane fluidity, bilayer thickness, and the function of embedded proteins — hence the preferential involvement of the most lipid-dependent tissues: retina, myelin, cochlea, myocardium, and stratum corneum."*

### A bonus mechanism for the skin

Phytanic acid is a **natural ligand for RXR (retinoid X receptor)** and also activates **PPARα**. Since RXR heterodimerises with RAR and VDR to control keratinocyte proliferation and differentiation, excess phytanic acid may **directly dysregulate the epidermal differentiation programme** — not merely act as a physical contaminant of the barrier. This is a sophisticated point that distinguishes a good answer from an excellent one.

---

## 6. Clinical Features — In Detail

**Onset:** typically **childhood to adolescence** (usually before age 20; occasionally infancy or as late as the 50s). Symptoms are **slowly progressive**, often punctuated by **abrupt deteriorations** during intercurrent illness, fasting, surgery, or pregnancy — episodes that correspond to sudden mobilisation of phytanic acid from fat stores (see Treatment).

### 6.1 Cutaneous

- **Ichthyosis vulgaris–like scaling**: **small, fine, white scales** over the **extremities and trunk**, with **larger, thicker, adherent scales on the legs**
- **Palmoplantar hyperlinearity** and **hyperkeratosis** of palms and soles
- Usually **mild** and may be overlooked; sometimes appears only later, or becomes apparent to the family only in retrospect
- Notably, the ichthyosis is **one of the few features that visibly improves with dietary treatment** — an excellent bedside demonstration of the metabolic mechanism

### 6.2 Ophthalmological — usually the earliest and most disabling

- **Retinitis pigmentosa**: begins as **nyctalopia (night blindness)** because rods fail first → **ring scotoma** → **progressive concentric peripheral field constriction** ("tunnel vision") → eventual blindness
- **Extinguished or grossly reduced electroretinogram (ERG)** — often abnormal before symptoms
- Associated: **miosis with poorly reactive pupils**, **posterior subcapsular cataracts**, **optic atrophy**

### 6.3 Neurological

- **Mixed sensorimotor polyneuropathy**, classified as **HMSN type IV** (hereditary motor and sensory neuropathy type IV = the Refsum variant)
  - **Chronic, progressive, distal, symmetrical**; sensory loss, distal weakness and wasting, areflexia
  - **Palpably hypertrophied (enlarged) peripheral nerves** — a superb clinical sign; the nerve is thickened by repeated demyelination–remyelination producing **onion-bulb formations** on biopsy (pathologically analogous to **CMT1 / Charcot–Marie–Tooth demyelinating neuropathy** and Dejerine–Sottas)
  - **Nerve conduction studies:** marked **slowing of conduction velocity** → a *demyelinating* pattern
  - **Raised CSF protein with normal cell count** = **albuminocytological dissociation** (the same phenomenon you know from Guillain–Barré), reflecting root-level demyelination
- **Cerebellar ataxia** — with gait instability, intention tremor, dysarthria, nystagmus; note that part of the "ataxia" is genuinely **sensory ataxia** from large-fibre loss
- **Anosmia** — nearly universal, and often present very early; frequently the earliest symptom, yet almost never volunteered by the patient unless asked
- **Impaired taste** (largely a consequence of anosmia)
- **Sensorineural hearing loss with tinnitus** — bilateral, progressive
- Variable: nystagmus, pyramidal signs, mild cognitive changes

### 6.4 Cardiac — do not forget this

- **Cardiomyopathy** and, critically, **conduction defects and arrhythmias**
- **This is the commonest cause of sudden death** in Refsum's disease. Every patient needs **ECG and echocardiographic surveillance.** An answer that mentions the cardiac risk demonstrates clinical maturity.

### 6.5 Skeletal

- **Shortened fourth metatarsals and metacarpals** (≈one third of patients), epiphyseal dysplasia, occasionally short stature — a developmental peroxisomal footprint, more prominent in *PEX7*-related disease

> ### 🔑 Clinical Pearl
> **Ichthyosis + retinitis pigmentosa + sensorineural deafness + hypertrophic peripheral neuropathy + anosmia = Refsum's disease.**
> If a patient with "ichthyosis vulgaris" reports **night blindness** or is found to have **anosmia**, send a **plasma phytanic acid level**. It is a cheap test, and the disease is **treatable** — making this one of the most important diagnoses *not* to miss in all of paediatric dermatology.

---

## 7. Histopathology and Ultrastructure

Remember what we are looking for: **stored lipid** and **a broken barrier**.

**Light microscopy (H&E):**
- **Orthohyperkeratosis** — a thickened stratum corneum in which the corneocytes have lost their nuclei normally (i.e., no parakeratosis), consistent with a *retention* hyperkeratosis rather than an inflammatory one
- **Basal cell vacuolation** — the "vacuoles" are the empty spaces left where lipid droplets were dissolved out by routine processing solvents
- Mild hypergranulosis or a normal granular layer; the picture is **non-specific and closely mimics ichthyosis vulgaris** on H&E alone — which is precisely why special stains matter

**Special stain — Oil Red O (the diagnostic clincher):**
- **Numerous fat globules (lipid droplets)** within the **basal keratinocytes** and other keratinocytes
- **Critical technical point:** Oil Red O is a **fat-soluble diazo dye** that must be performed on **frozen (or formalin-fixed, unembedded) sections**. Routine **paraffin processing dissolves the lipid away** with xylene and alcohol, leaving only empty vacuoles. **If you want to see the lipid, you must ask for the right specimen.** Many "negative" biopsies are simply the wrong technique.
- Why does a *fatty acid* storage disorder show *neutral lipid* droplets? Because accumulated phytanic acid is esterified into **triglycerides and cholesteryl esters** and sequestered in cytoplasmic droplets — the cell's standard way of quarantining excess lipid.

**Electron microscopy (ultrastructure):**
- **Detachment or complete absence of the corneocyte lipid envelope (CLE)**

Let me unpack the **CLE**, because it is not a trivial detail. The CLE is a **monolayer of ω-hydroxyceramides covalently bound** to the involucrin/loricrin protein scaffold of the cornified envelope. It is the **primer coat** on the outside of each corneocyte "brick," and the intercellular lamellar lipid "mortar" bonds to it. Lose the CLE and the mortar cannot key onto the bricks → **lamellar disorganisation → barrier failure → compensatory hyperproliferation and retention hyperkeratosis → scale.**

> **Analogy:** The CLE is the **primer on a wall** before you apply tile adhesive. Excess phytanic acid, incorporated into the ω-hydroxyceramide precursors, produces a **defective primer that peels away**. The tiles (corneocytes) will not stay properly bonded, and the wall (barrier) leaks — so the body keeps slapping on more tiles.

**A useful histological contrast:** the *other* dermatological condition with **Oil Red O–positive lipid droplets in keratinocytes** is **Chanarin–Dorfman syndrome** (neutral lipid storage disease with ichthyosis, *ABHD5/CGI-58*), where you also find **lipid vacuoles in circulating leukocytes (Jordans' anomaly)** on a peripheral blood film. Refsum's does *not* show Jordans' anomaly. Knowing both makes you look well-read.

---

## 8. Investigations — and the Reasoning Behind Each

| Investigation | Expected finding | Why you order it |
|---|---|---|
| **1. Plasma phytanic acid** ⭐ | **Markedly elevated, typically >200 μmol/L** (often 100–1500) <br>**Normal <3 μmol/L** (laboratory upper limit of normal quoted up to ~30 μmol/L) | **The single diagnostic test.** Simple, cheap, definitive. Also used to monitor treatment response. |
| **2. Plasma very-long-chain fatty acids (VLCFA)** | **Normal** | Crucial discriminator: VLCFAs are **raised** in Zellweger-spectrum peroxisome *biogenesis* disorders and X-linked adrenoleukodystrophy. Normal VLCFA + high phytanic acid = **isolated α-oxidation defect** = classical Refsum. |
| **3. Red-cell plasmalogens** | **Normal in *PHYH*; reduced in *PEX7*** | Separates the two genotypes biochemically. |
| **4. Molecular genetic testing** | Biallelic *PHYH* (≈90%) or *PEX7* (≈10%) mutations | Confirms diagnosis, permits **carrier testing and genetic counselling** (AR: 25% recurrence risk per pregnancy). |
| **5. Skin biopsy / histopathology** | Orthohyperkeratosis, basal vacuolation, **Oil Red O–positive droplets**, absent CLE on EM | Supportive; particularly useful when dermatology sees the patient first. |
| **6. CSF analysis** | **Raised protein, normal cell count** (albuminocytological dissociation) | Documents the demyelinating radiculoneuropathy. |
| **7. Nerve conduction studies ± nerve biopsy** | Slowed conduction (demyelinating); **onion bulbs**, hypertrophic nerve | Characterises the HMSN IV neuropathy. |
| **8. Ophthalmological assessment** — fundoscopy, visual fields, **ERG** | Retinitis pigmentosa, ring scotoma/constricted fields, **extinguished ERG** | Establishes and stages the retinopathy; ERG is abnormal earliest. |
| **9. Audiometry** | Bilateral SNHL | Baseline and monitoring; enables hearing-aid provision. |
| **10. ECG and echocardiography** ⭐ | Conduction defects, arrhythmias, cardiomyopathy | **Life-saving surveillance** — cardiac events are the main cause of death. |
| **11. Hand/foot radiographs** | Shortened 4th metatarsals, epiphyseal dysplasia | Supportive skeletal clue. |

> ### ⚠️ Critical Unit Correction
> Some texts print the diagnostic threshold as **">200 mmol/L"**. This is a **typographical error and must be read as ">200 μmol/L."**
> Sanity-check it yourself: phytanic acid has a molecular weight of ~312 g/mol, so 200 **mmol/L** would be roughly **62 g of phytanic acid per litre of plasma** — a value physically and physiologically impossible, and instantly fatal. The correct figures are **normal <3 μmol/L; diagnostic >200 μmol/L (= 0.2 mmol/L)**.
> Examiners love unit errors. Always sanity-check a metabolite concentration against plausibility.

---

## 9. Treatment — Where the Mechanism Pays Off

Because phytanic acid is **100% dietary in origin**, Refsum's disease is **the only ichthyosis whose primary treatment is a diet.** That single sentence is worth memorising verbatim.

### 9.1 Dietary restriction of phytanic acid — the cornerstone

- **Target:** phytanic acid intake **<10 mg/day** in most modern references. (Your source text expresses this as *"exclusion of chlorophyll from the diet to <5 mg/day"* — a legitimate older phrasing, since chlorophyll's phytol side-chain is the ultimate precursor. Both statements point to the same intervention; quote your textbook's figure but understand what it means.)
- **Foods to restrict:** **dairy fat** (butter, cheese, cream, whole milk), **ruminant meat and fat** (beef, lamb, mutton), **certain fish** (tuna, cod, haddock, herring)
- **A clarification worth making:** many sources say "avoid green vegetables." In practice, **green vegetables are minor contributors**, because humans poorly liberate phytol from intact chlorophyll (we have no rumen). Unnecessarily banning vegetables harms nutrition without much metabolic benefit. The **animal-fat sources are the real targets.**
- **Must be supervised by a specialist metabolic dietitian** — with attention to calorie adequacy, fat-soluble vitamins, and calcium (since dairy is being removed)

### 9.2 Avoid fasting and rapid weight loss — the paradox you must be able to explain

This is the most commonly misunderstood point in the whole topic, so let's be precise.

Years of accumulation store **large depots of phytanic acid in adipose tissue.** If the patient **fasts, crash-diets, becomes acutely ill, or undergoes surgery**, the body switches to lipolysis and **mobilises adipose triglyceride — dumping stored phytanic acid into the plasma**. Plasma levels can spike several-fold within days.

**Consequence:** acute deterioration — **cardiac arrhythmias, worsening ataxia, acute neuropathy flares, hepatic dysfunction, even death.**

> **Analogy:** The fat tissue is a **warehouse** where the body has been quietly shelving the toxin it cannot destroy. Weight loss is not "getting rid of it" — it is **emptying the warehouse back onto the high street.** The toxin is only truly eliminated slowly, by the trickle of residual metabolism and excretion, not by burning fat.

**Practical management rules:**
- Maintain **stable weight and adequate caloric intake**
- Aggressively treat intercurrent illness; provide **intravenous dextrose during illness, fasting, or perioperative periods** to suppress lipolysis
- **Never prescribe a weight-reduction diet** without metabolic-team input
- Pregnancy and puerperium require vigilant monitoring

### 9.3 Lipid apheresis / plasmapheresis

- **Mechanically removes phytanic acid** (carried on lipoproteins and albumin) from the circulation
- **Indications:** acute crises, rapid clinical deterioration, or dangerously high plasma levels (often quoted **>800–1000 μmol/L**); also used to achieve initial rapid reduction before diet takes over
- It is an **adjunct and a rescue therapy**, not a substitute for diet — because the dietary tap is still running

### 9.4 Cutaneous management

- **Emollients** — the mainstay (urea-, lactic-acid-, or glycerol-containing humectants; occlusive ointments)
- **Mild keratolytics** for palmoplantar hyperkeratosis
- The ichthyosis often **improves substantially on diet**, reinforcing adherence

### 9.5 Supportive and multidisciplinary care

- **Cardiology:** serial ECG/echo, arrhythmia management, pacing if indicated
- **ENT/Audiology:** hearing aids; cochlear implantation in selected cases
- **Ophthalmology:** low-vision aids, mobility training, **dark glasses/UV protection**; counselling about progression
- **Neurology, physiotherapy, occupational therapy:** orthoses, falls prevention, gait training
- **Genetic counselling:** autosomal recessive; 25% recurrence risk; carrier and prenatal testing available
- **Caution with drugs and situations that promote lipolysis or that are cardiotoxic**

### 9.6 Prognosis — set expectations honestly

This is a subtlety that separates a superficial answer from a good one:

| Feature | Response to treatment |
|---|---|
| **Ichthyosis** | **Improves** — often markedly |
| **Peripheral neuropathy** | **Stabilises, may partially improve** |
| **Ataxia** | Often **stabilises** |
| **Retinitis pigmentosa** | **Largely irreversible**; progression may slow but vision is not restored |
| **Sensorineural deafness** | **Largely irreversible** |
| **Anosmia** | Irreversible |

Because **phytanic acid has a very long biological half-life (months)**, plasma levels fall slowly and **clinical benefit may take 1–2 years** to become apparent. Counsel patients accordingly — otherwise they will abandon a difficult diet before it can work. And the message is clear: **early diagnosis matters enormously**, because what you prevent you keep, and what is already lost (retina, cochlea) you do not get back.

---

## 10. Common Misunderstandings — Let's Clear Them Up

**① "Infantile Refsum disease is just early-onset Refsum's disease."**
**False, and this is a favourite trap.** **Infantile Refsum disease (IRD)** is a **peroxisome *biogenesis* disorder** in the **Zellweger spectrum**, caused by *PEX1*, *PEX2*, *PEX6*, *PEX26* and similar mutations. In IRD, **whole peroxisomes fail to assemble**, so *many* pathways fail simultaneously → **raised VLCFAs, low plasmalogens, abnormal bile acids**, plus dysmorphism, severe hypotonia, hepatopathy and profound developmental delay. **Classical (adult) Refsum disease** is an **isolated single-enzyme defect** with **normal VLCFAs**. They share a name for historical reasons only. *Different disease, different prognosis, different biochemistry.*

**② "Phytanic acid builds up because the body makes too much of it."**
No. Humans **cannot synthesise phytanic acid at all.** It is purely dietary. This is precisely why diet works.

**③ "The block is in β-oxidation."**
No. β-oxidation machinery is intact. The block is in **α-oxidation**, the *pre-processing* step. Phytanic acid simply never becomes an acceptable substrate.

**④ "Weight loss will help clear the stored lipid."**
**Dangerously wrong** — it mobilises stored phytanic acid into plasma and can precipitate arrhythmias and neurological crisis. Stable weight; avoid fasting.

**⑤ ">200 mmol/L" is the diagnostic level.**
**Unit error.** It is **>200 μmol/L** (normal <3 μmol/L).

**⑥ "Cut out green vegetables — that's the main source."**
An oversimplification. Chlorophyll is the *ultimate* precursor, but the *practical* dietary sources are **dairy fat, ruminant meat, and certain fish**, because ruminant gut bacteria are what liberate phytol from chlorophyll in the first place.

**⑦ "The ichthyosis is the main problem."**
No. The ichthyosis is mild and treatable; **blindness, deafness and cardiac arrhythmia** define morbidity and mortality. The dermatologist's value here is as **the diagnostician**, not primarily the treater.

**⑧ "An Oil Red O stain on the routine paraffin block will show the lipid."**
It will not. Lipid is **dissolved out during paraffin processing.** Request **frozen sections** if you want to demonstrate lipid droplets.

---

## 11. Differential Diagnosis — Placing Refsum's Among the Syndromic Ichthyoses

Refsum's disease is classified as a **syndromic ichthyosis** in the **2009 Sorèze ichthyosis consensus classification** (specifically, within the neurological group).

| Syndrome | Gene / defect | Ichthyosis + … | Distinguishing hook |
|---|---|---|---|
| **Refsum's disease** | *PHYH* / *PEX7*; phytanic acid α-oxidation | **Retinitis pigmentosa, neuropathy, ataxia, SNHL, anosmia** | **Raised plasma phytanic acid; treated by DIET** |
| **Sjögren–Larsson syndrome** | *ALDH3A2*; fatty aldehyde dehydrogenase | **Spastic diplegia/tetraplegia + intellectual disability** | **Glistening white dots in the macula** (not RP); pruritic, lichenified ichthyosis |
| **Rud syndrome** (contested entity) | heterogeneous | **Epilepsy + hypogonadism + intellectual disability** | Loosely defined; often reclassified |
| **Chanarin–Dorfman syndrome** | *ABHD5* (*CGI-58*) | Hepatosplenomegaly, myopathy, cataracts, SNHL, ataxia | **Jordans' anomaly** — lipid vacuoles in leukocytes; also Oil Red O positive |
| **Multiple sulphatase deficiency** | *SUMF1* | Leukodystrophy, skeletal dysplasia, regression | Multiple sulphatase enzymes deficient |
| **KID syndrome** | *GJB2* (connexin 26) | **Keratitis + SNHL** | Vascularising keratitis, not RP |
| **Netherton syndrome** | *SPINK5* (LEKTI) | Atopy, failure to thrive, ↑IgE | **Ichthyosis linearis circumflexa + trichorrhexis invaginata** |
| **Trichothiodystrophy (IBIDS)** | *ERCC2/3*, *GTF2H5* | Brittle hair, photosensitivity, ID | **Sulphur-deficient hair; "tiger-tail" on polarised microscopy** |
| **CHILD syndrome** | *NSDHL* (X-dominant) | Ipsilateral limb defects | **Strictly unilateral**, sharp midline cut-off |
| **Conradi–Hünermann–Happle (CDPX2)** | *EBP* (X-dominant) | Chondrodysplasia punctata, cataracts | **Blaschkoid ichthyosis, follicular atrophoderma** |

**The two-second discriminator for the exam:** *Ichthyosis + eye + neuro?* → If the eye finding is **retinitis pigmentosa** and the neuro finding is a **peripheral neuropathy with ataxia**, think **Refsum**. If the eye finding is **glistening macular dots** and the neuro finding is **spasticity**, think **Sjögren–Larsson**.

---

## 12. Summary Anchor — The Core Idea in One Picture

> **Refsum's disease is a dietary poison the body cannot destroy.**
>
> **Chlorophyll's phytol tail** → becomes **phytanic acid** in ruminants → **eaten by humans in dairy, ruminant fat and fish**. Phytanic acid has a **methyl group on its β-carbon**, so **β-oxidation cannot grip it**. It must first be shortened by one carbon — **α-oxidation inside the peroxisome**, catalysed by **phytanoyl-CoA hydroxylase**.
>
> Break the **enzyme** (***PHYH***) or break its **delivery receptor into the peroxisome** (***PEX7***) — and the same thing happens: **phytanic acid accumulates and is built into membranes in place of proper fatty acids.**
>
> The **most lipid-dependent tissues fail first**: **retina → retinitis pigmentosa**; **myelin → hypertrophic neuropathy + ataxia**; **cochlea and olfactory epithelium → deafness and anosmia**; **heart → arrhythmia (the killer)**; **stratum corneum → mild ichthyosis with an absent corneocyte lipid envelope**.
>
> **Diagnose it** with a single cheap blood test: **plasma phytanic acid >200 μmol/L (normal <3 μmol/L)**, with **normal VLCFAs** to exclude Zellweger-spectrum disease.
>
> **Treat it by turning off the tap** — **dietary phytanic acid <10 mg/day** — while **never emptying the warehouse too fast** (avoid fasting and rapid weight loss, which mobilise stored phytanic acid and can kill). Use **lipid apheresis** for crises, **emollients** for the skin, and **lifelong cardiac, auditory and ophthalmic surveillance**.
>
> **Skin and nerves improve; retina and hearing do not.** Therefore the **dermatologist who recognises "mild ichthyosis + night blindness + anosmia" can preserve a patient's sight and life.**

---

## 13. Teach-Back Checklist

You genuinely understand this topic if you can answer these without looking:

1. Why can phytanic acid not be β-oxidised directly? *(β-carbon methyl group blocks ketone formation at C3)*
2. What does α-oxidation achieve, and where does it occur? *(removes one carbon so the branch sits at C2; in the peroxisome)*
3. Name both genes and explain how they produce an identical phenotype by different mechanisms. *(*PHYH* = defective enzyme; *PEX7* = PTS2 receptor failure, enzyme locked out of peroxisome)*
4. State the classical tetrad and add four features it omits. *(RP, neuropathy, ataxia, ichthyosis + anosmia, SNHL, cardiomyopathy, short 4th metatarsals)*
5. Which single blood test confirms the diagnosis, and what are the normal and diagnostic values? *(plasma phytanic acid; <3 μmol/L vs >200 μmol/L)*
6. Which additional biochemical test separates this from Zellweger spectrum and X-ALD? *(VLCFA — normal here, raised there)*
7. Why is fasting dangerous? *(lipolysis mobilises adipose phytanic acid → plasma spike → arrhythmia and neurological crisis)*
8. Why must Oil Red O be done on frozen section? *(paraffin processing dissolves the lipid)*
9. What is the corneocyte lipid envelope and why does its loss cause scaling? *(covalently bound ω-hydroxyceramide monolayer = "primer" for intercellular lamellar lipids; loss → barrier failure → retention hyperkeratosis)*
10. Which clinical features improve with diet and which do not? *(skin, neuropathy, ataxia improve; RP, SNHL, anosmia do not)*
11. How does infantile Refsum disease differ from classical Refsum disease? *(peroxisome biogenesis disorder, Zellweger spectrum, raised VLCFA, low plasmalogens, far more severe)*
12. Distinguish Refsum from Sjögren–Larsson in one sentence each.

If you can do all twelve, you can not only answer "write a short note on Refsum's disease" — you can **reason your way through any viva question on it**, which is a considerably more durable achievement.