**Laser Lithography to Generate Antigens for Autologous Cancer Vaccination**

Jeremy Stubbs MD<sup>1</sup>

<sup>1</sup>Independent Researcher, United States of America

<jeremyb.stubbs@gmail.com>

**Keywords**

Immunotherapy, Antibody, Granulocytes, Eosinophils, Neutrophils, NK cells, T-cells, Crispr

**Introduction**  
Cancer immunotherapy has revolutionized oncology, yet challenges remain in the development of effective, personalized vaccines. This proposal explores the use of lithography technology to generate tumor cell fragments from pathology slices. Lithography is the use of collimated light i.e. lasers with a photomask to etch a pattern on a substrate. Chemically optimized and purified fragments would be injected with adjuvants. The photomask grid pattern dictates fragment size whose optimal dimensions can be determined empirically. Precise molecular disruption exposes native tumor antigens that retain all post-translational modifications unlike another leading cancer vaccine approach - mRNA. Furthermore, if feasible the strategy would be cheap and scalable. Existing technology allows for UV, X-ray, and possibly IR systems to be evaluated.

**Background and Rationale**

In situ vaccination following radiation therapy represents a promising therapeutic strategy that has demonstrated encouraging clinical outcomes. However, this uncontrolled degradation may result in unpredictable tumor-associated antigen (TAA) size. In addition, the highly inflammatory state post-radiation rich in neutrophils which release digestive enzymes may compromise the chemical integrity of fragments, limiting the precision of the immune response

An alternative approach involves excision of the tumor tissue, subjecting it to controlled irradiation ex vivo, followed by purification and chemical treatment of the resulting antigenic debris. This refined material can then be reintroduced into the patient alongside appropriate immunologic adjuvants, enabling greater control over antigen integrity and immunogenicity. The main differences are location of light exposure (inside vs outside the patient) and frequency of light (UV vs Ionizing radiation). Compared to in situ vaccination following radiation therapy the possible advantages are: greater control over antigen size, the option to filter unwanted material, the option to chemically optimize the fragments (optimize immunogenicity, optimize stability of fragments), and the ability to better avoid inflammatory degradation either by chemical optimization (adducts, liposomes, hydrogels) or ex-vivo priming of antigen presenting cells (APCs).

Past attempts for antigen preparation for autologous cancer vaccines have relied on enzymatic digestion or mechanical disruption (sonication) of the cells, which by comparison lack the ability to make precise sized fragments that maintain the native form of macromolecules.

UV laser lithography is widely used in semiconductor fabrication to achieve nanoscale precision (currently the smallest transistor is 2nm which is much smaller than a 20-30 nm ribosome). The same principles can be applied to fragment tumor-associated antigens in a controlled manner, ensuring the generation of appropriately sized glycopeptides that antigen presenting cells (APC) can process and present on major histocompatibility complexes (MHC).

Ultraviolet frequency is extremely well suited for breaking organic C-C and C-N bonds. In fact, “laser capture microdissection” is a known method of using UV lasers to dissect individual cells. Because of the nice cuts they make, fluorine-based excimer lasers that operate in the UV-C range (around 193 nm) are also used in eye surgery. Deep UV (200–300 nm) can interact with proteins and DNA without massive heat buildup, making it ideal for precise cellular fragmentation. Femtosecond (fs) or picosecond (ps) pulsed UV lasers are especially good at breaking bonds and not disrupting surrounding tissue.

X-rays are another excellent frequency candidate. In fact, x ray photomasks exist, and lithography systems can achieve nearly the same precision as those that employ UV light. X-rays have significantly more energy than UV light. The cell membrane is approximately 10nm thick. Approximately 20-40% of known tumor-associated antigens (TAA) are membrane bound so it is safe to use the outermost portion as the initial target. As a safety margin, let’s examine the penetration of UV and X rays of 10 nm of tightly wound keratin. By some estimates, the UV (300–350 nm) transmission is ~30–40%, and X-ray (1-10 keV) transmission 99%. Less x-rays will be absorbed, but they are higher energy and break bonds much more effectively when they are absorbed.

A comparison of UV vs X rays:

|     | **UV Light** | **X-rays** |
| --- | --- | --- |
| **Tissue Penetration** | Poor (microns at most) | Excellent (millimeters to cm) |
| **Precision/Control** | High with lasers | Lower spatial precision (difficult to collimate and reflect/refract) |
| **Damage Type** | Milder photochemistry, DNA damage | Deep ionization, crosslinking, fragmentation |

X rays have fewer numbers of interactions, but each interaction is more likely to break a chemical bond. The overall efficacy of these frequencies may compensate for the difficulties in their optical manipulation.

A similar strategy was tried in China - “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST).” \[2\] This was not an inspiration for me; I found it after I started writing my proposal. But, it still is worth mentioning since it kind of uses the same ingredients: light to fragment tissue for a vaccine. I wish them the best of luck. If they used a photomask (something that selectively blocks light to create an etch pattern), then it is pretty much identical to mine, but I see no indication that they used a photomask.

You don’t need a $200,000,000 ASML machine to do this. All you need is a reliable UV laser source (a few hundred thousand dollars) and a good UV photomask (a few hundred thousand dollars). Wavelengths and Actual Laser System:

- 266 nm (Deep UV, Nd:YAG 4th harmonic) → High precision, strong protein interactions.
- 213 nm (Even deeper UV, Nd:YAG 5th harmonic) → More precise fragmentation control.
- Excimer Lasers (XeCl at 308 nm, ArF at 193 nm) → Used in eye surgery, could be adapted for tumor antigen fragmentation.

IR frequency light interacts with water much more than UV. Thus it will produce more heat and scattering. Water strongly absorbs IR radiation because its molecular vibrations (stretching and bending of O-H bonds) match the energy of IR photons. A skin cell is approximately 30 um in diameter, which corresponds to 109,000 water molecules lined up end to end. Near-IR (800 nm+) would get absorbed by tissue water before reaching the target. Nevertheless, femtosecond (fs) or picosecond (ps) pulsed IR lasers further might allow intracellular disruption of organic bonds before heating. Pulsed IR lasers are tuned to a wavelength in the ~1300–1500 nm range may also minimize heating but maximize bond breaking. Alternatively, low-energy pulses could cause nanobubble formation or localized pressure bursts, rather than full vaporization.

**Practical Considerations:**

Immediately after the UV laser (or X ray) you’ll have a burst of reactive molecular species—free radicals, aldehydes, oxidized lipids, broken protein domains, exposed cysteines, etc. These fragments could rapidly rebind, aggregate, or denature, which could: mask antigenic sites, reduce immune visibility, make the “vaccine” messy or less effective.

The key may be to quench or stabilize the fragments right as they form, before they start cross-linking or misfolding. There are two ways to handle this: a buffer solution and chemically capping the fragments. You can add the buffer solution to the cells immediately after zapping them or have it there before you zap them. Options are listed below for a “fragmentation buffer”.

| **Component** | **Role** |
| --- | --- |
| **N-acetylcysteine (5–10 mM)** | Scavenges ROS, protects thiols |
| **PEG-NHS (0.5–2 mM)** | Blocks exposed amines, reduces aggregation |
| **Mannitol or Sorbitol (10–50 mM)** | Hydroxyl radical scavenger, protects macromolecules |
| **HEPES (25 mM, pH 7.4)** | Stable pH buffer under light/heat |
| **Protease inhibitor cocktail** | Stops enzymatic degradation |
| **Optional: low-concentration TLR ligand (e.g. CpG, poly I:C)** | Primes immune activation after uptake |

I don’t know enough about organic chemistry to offer a capping solution, but consider something that binds to free organic molecules in solution and then becomes refractory, maybe an aromatic plastic group linked by an epoxy?

One advantage of this strategy is the option to enrich the sample – remove unwanted parts so that you are left with more cancer cells which give a more targeted immune response.

Removing non-cancerous cells might be useful, maybe with targeted excision with the UV optical system itself operating like a solid beam not a grid.

A pre-treatment with collagenase might be helpful.  
• Collagen in the stroma can scatter or absorb UV laser energy (collagen’s peptide bonds absorb at ~200–280 nm, overlapping with UV wavelengths like 248 nm). Degrading it first could make ablation more efficient, ensuring the laser focuses on tumor cells and membranes.  
• With ~15–25% of the slice being collagen, pretreatment could dissolve most of it into peptides, leaving a leaner matrix (mostly cells) for the laser to cut. This might yield a higher proportion of phospholipid-rich fragments post-ablation.

Another advantage of this strategy is the option to chemically modify the debris for optimal immunogenicity and stability. You could chemically link the fragments to an immune stimulant.

I stumbled across this article “Tumor Cell Membrane‐Based Vaccines: A Potential Boost for Cancer Immunotherapy.” It is research (also out of China) about creating autologous cancer vaccines. They used sonication to break up the cells which they then combined with cholesterol or whatever to make hybrid liposomes that contained TAAs. \[4\] It got me thinking about my idea. What I think would happen is once you injected my cancer vaccine into the body is those bloody little neutrophils would come along and squirt protease everywhere, effectively denaturing it.

A better approach might be to pulse APC’s in the lab and then inject those into the patient. Or encapsulate the vaccine in liposomes.

Neutrophils (and other myeloid cells) can indeed respond rapidly to foreign material by releasing reactive oxygen species, proteases, and other enzymes, which could degrade your carefully prepared antigen fragments before they reach antigen-presenting cells (APCs) in a meaningful way. This "bystander destruction" is a known issue in vaccine design, especially with tumor lysate-based vaccines.

Here are three viable strategies to improve the vaccine's efficacy:

1\. Ex Vivo Pulsing of APCs (like dendritic cells):

Pros: Highly controlled, allows precise loading of tumor antigens onto MHC molecules.

Cons: Labor-intensive, expensive, and usually autologous (patient-specific).

Potential Optimization: You could combine this with maturation signals (e.g., LPS, CD40L, poly I:C) to enhance APC activation before reinfusion.

2\. Liposome or Nanoparticle Encapsulation:

Pros: Protects antigens from extracellular degradation, improves delivery to lymph nodes, and can be decorated with targeting ligands (e.g., mannose for dendritic cells).

Cons: Requires formulation work and quality control, but very scalable and compatible with off-the-shelf approaches.

Pro Tip: Co-encapsulate immune adjuvants (e.g., CpG, MPLA) with your antigens to boost the immune response.

As a matter of fact, incorporation of cell membranes of tumor cells into nanoparticles and liposomes has been widely tried as cancer vaccines. \[4\] To the best of my knowledge (and the AI’s) no one has used lithography systems to generate those fragments.

3\. Hydrogel or Matrix-Based Slow Release:

Pros: Sustained antigen presentation mimics a persistent infection, allowing better immune training.

Cons: Slightly more invasive depending on the delivery route.

Optional Twist: Use enzymatically responsive hydrogels that degrade in response to MMPs or neutrophil elastase, slowly releasing antigen in inflamed tissue.

**Simplified Workflow Concept (with Pre-Irradiation Buffering):**

1. Tumor Tissue or Cell Lysate Preparation: Tumor cells are harvested from the patient as intact tissue sections.
    - A biopsy or resected tumor sample is obtained from the patient.
    - Tissue sections are cut into slices like for a pathology slide approximately 1-2 cells thick to increase the likelihood of success.
2. UV Laser Exposure in a Grid Pattern:
    - A UV laser (e.g., excimer or femtosecond laser) or X ray laser with a photomask is used to create precise antigen fragments by exposing the sample to a predetermined grid pattern.
    - The pathology slice could be cut while frozen or thawed. Like the size of the fragments, this must be determined empirically along with when to introduce the fragmentation buffer.
    - Note that the laser can be used to cut the sample several times. In fact, it could cut the pathology slice, which is then turned into a lysate and cut again.
3. Fragmentation Buffer: added before or immediately after. Non-ionic detergents (e.g., low concentrations of Triton X-100, Tween-20, or digitonin), EDTA, and maybe some other stuff from the list above.
4. Gentle sonication to fragment the cut/scored cells.
5. Optional: Add solution containing components necessary for liposome formation (triacyl glycerides). Form liposomes through known methods like Azafari method.
6. Optional: Collect and optionally filter or centrifuge to isolate desired particle size range.
7. Optional: chemical modification of fragments

• Use biotin-NHS, PEG-mannose-NHS, or Fc-tagged PEGs during the soak.

• As proteins break apart, their free lysines and N-termini get tagged—simultaneously quenching and targeting the fragments for immunogenicity.

1. The fragmented antigens are collected and reinjected with adjuvants or used to pulse autologous dendritic cells (DCs) ex vivo, which are then reintroduced into the patient.
2. Immune Activation:
    - The processed antigens are presented to T cells, initiating an immune response against tumor-specific epitopes.
    - Co-administered **adjuvants** enhance dendritic cell activation and antigen presentation. A TLR agonist (like CpG DNA, poly-IC, or MPLA) would boost innate immune activation, drawing in antigen-presenting cells. GM-CSF could be injected locally to recruit dendritic cells, ensuring efficient antigen pickup.
    - A **checkpoint inhibitor** (like anti-PD-1 or anti-CTLA-4) could be combined for even stronger T cell activation.

**Desired Outcomes**

- Precision control over antigen size, optimizing immune recognition.
- Increased reproducibility compared to enzymatic digestion methods.
- Enhanced T cell activation due to efficient antigen processing and presentation.
- Potential for personalized, autologous cancer vaccines tailored to individual patients.

**Discussion**

This approach leverages lithography technology (lasers + photomask) for precise antigen fragmentation, enabling the development of an autologous cancer vaccine with enhanced efficacy. I think this is a sufficiently unique idea that is logically sound and therefore must be tried.

It is similar to _in situ_ vaccination after radiation therapy, something that has shown promising results in early studies. The main differences are the location of light exposure (inside vs outside the patient) and the frequency of light (UV vs Ionizing radiation). Compared to in situ vaccination following radiation therapy the possible advantages are: greater control over antigen size, the option to filter unwanted material, the option to chemically optimize the fragments (optimize immunogenicity, optimize stability of fragments), and the ability to better avoid inflammatory degradation either by chemical optimization (adducts, liposomes, hydrogels) or ex-vivo priming of antigen presenting cells (APCs).

This vaccine strategy could easily be used in a treatment plan that includes mRNA vaccines, but a head-to-head comparison is in order.

Vaccines based on mRNA to the best of my knowledge attempt to generate peptides approximately 8-20 amino acids in length. The goal is to find a sequence that is not found anywhere else in the body which you can train the immune system to recognize. One challenge is: in the tumor cell, are these readily available for interaction with the immune system? Immune cells recognize fully folded proteins. Often point mutations can lead to misfolding. Mimicry of quaternary structure with 8-20 amino acids is challenging especially if there are multiple chains contributing to a unique quaternary structure. MRNA vaccines look for contiguous amino acids that are not post translationally modified present only in tumor cells and not normal cells. They have to be either external protein antigens that are not folded into the center of the surface protein complex Or internal protein antigens that are processed and presented by the tumor cells themselves on MHCI complexes. With 20 long peptides there are 20^20 possible combinations of peptides, but with a shorter length say 9 there are only 512 billion combinations. Using a shorter length makes it computationally easier to find a contiguous unmodified external sequence present only in the tumor cells and not normal cells from DNA sequencing. Shorter sequences are more likely to be adjacent as there is a limit to the turn radius of peptides. There is also less chance of being cut into a quaternary structure. Based on the known structure of proteins and protein folding calculations, AI may help identify peptide sequences likely to be external and unmodified and uncut. But, many of the best TAAs are post-translationally modified. MRNA vaccines worked for covid spike protein because it was a well-studied protein that didn't really change much from strain to covid strain and because it is so huge that finding an external unmodified contiguous chain of amino acids was comparatively easy. The problem of finding a unique external contiguous unmodified sequence is much larger for cancer, but possibly doable. But crucially, mRNA technology doesn’t account for post-translational modifications. 

Summary of Where mRNA Cancer Vaccine Tech Struggles:
-PTM Ignorance: mRNA vaccines produce canonical proteins — the cell machinery determines PTMs, and current design pipelines don’t fully predict or manipulate them. 
-Antigen Localization: Many tumor neoantigens are intracellular, requiring MHC-I processing rather than antibody response. 
-Tumor Heterogeneity: Not all cells in a tumor express the same antigen. 
-Tolerance & Immune Editing: The immune system may be partially or fully tolerized to self-like sequences, and tumors can lose antigen presentation (e.g., via β2M loss). 
-Quaternary Structures & Cryptic Epitopes: If the mutation lies in a region that’s conformational or buried, it may never be exposed unless processed.

With this strategy you do not need to reduce the fragment size down to 8-11 amino acids, which is the length of peptide that MHC molecules present. After phagocytosis, lysosomal processing will do that and select the best antigen candidates with full post-translational processing. Breaking the cells into bite sized bits is the key and seems fully doable. The natural target for this approach is pathology slices. 

Since this has never been done, we must attempt to infer its feasibility from existing experimental techniques. Two relevant examples are: (1) the use of UV laser-based cellular dissection in pathology, and (2) the preparation of autologous vaccines using enzymatic and hypertonic cell lysis and their effectiveness.

1\. UV Laser Cellular Dissection (Laser Capture Microdissection): "How well does this technique work in producing small sections of the cell?"

Commentary:

Laser capture microdissection (LCM) is highly effective for isolating individual cells or specific regions of tissue. However, it is typically used for anatomical resolution (e.g., entire cells or nuclei), not biochemical fragmentation. That said, the ability of UV lasers—especially excimer and femtosecond-class systems—to break specific covalent bonds is well-documented in material science and microfabrication. Their precision has not been widely tested for molecular-level fragmentation of proteins in a biological context, but the technology does demonstrate proof-of-principle for spatial precision. \[3\] The challenge will be balancing fragmentation versus denaturation, particularly for preserving MHC-relevant epitopes.

**I firmly believe that you do not need to reduce the size down to 15-20 amino acids which is the length of peptide that MHC molecules present. After phagocytosis, lysosomal processing will do that and select the best antigen candidates. Breaking the cells into bite sized bits is the key.**

2\. Enzymatic or Hypertonic Autologous Cancer Vaccines: "How well have these lysates been characterized?"

Commentary:

Most enzymatic or osmotic preparations result in highly heterogeneous lysates which have not been extensively characterized. These are difficult to characterize precisely at the peptide or epitope level. Mass spectrometry can detect components, but in complex mixtures like whole-cell lysates, reproducibility and identification of functional antigens are problematic. Furthermore, harsh lysis (e.g., hypertonic shock, detergents) often leads to protein unfolding, aggregation, and loss of post-translational modifications and thus yields little useful information. \[1\] These are critical for immune recognition. In this regard, UV-mediated fragmentation might actually offer a more controlled, reproducible way to break proteins into immunologically relevant fragments—if scattering and overexposure can be minimized.

Ultimately, the feasibility depends on how much UV light will scatter through the membrane and cell layers. This is a crucial unknown. UV light at 200–300 nm has shallow penetration depth in biological tissue due to high absorption by proteins and nucleic acids. However, this may be an advantage—by limiting depth, you may effectively fragment material layer by layer, especially in frozen sections. For that, you may need to used two laser grids, each 45 degrees off vertical in the opposite direction of each other. Their vertices would be situated in topmost layer of the pathology slice – think tens – a few hundred nanometers beneath the surface. The frozen immobilization of the cells would prevent mixing after the fragments are generated. Buffer washes would then remove these fragments. The process could be repeated sequentially until the whole slice is fragmented in to nanometer fragments. For comparison, a ribosome is approximately 20-30 nm in diameter.

X rays have fewer numbers of interactions, but each interaction is more likely to break a chemical bond. But it is also most likely to generate a highly reactive intermediate that recombines with other fragments in an uncontrolled way. Experiments are needed to determine the optimal frequency.

How does this compare to mRNA vaccines? For your information, this vaccine could easily be used in a treatment plan that includes mRNA vaccines. They are not mutually exclusive. But this is how it differs.

\-It is more likely to generate complex antigens like lipids, proteoglycans, and proteins that undergo post-translational modifications.

\-There is a tradeoff between \[broadness of spectrum\] and \[specificity and consistency from one dose to another\]. There may be an advantage with regards to tumor heterogeneity and tumor evolution over time. You will get a broader spectrum of epitopes, however, the epitopes from dose to dose will be less reproducible than an mRNA vaccine.

\-The most striking difference is the cost. This is potentially significantly cheaper than mRNA vaccines which means it is much more scalable especially to markets outside the US.

**Future Direction/Initial Experiments**

Surely benchtop research should be done on this idea. I’ve presented a vast number of possibilities that should be tried here.

Within the optical system: wavelength, exposure time, different light patterns (one grid, two grids at angles to each other, multiple passes), temperature

The use of light sonication to break up lightly cut (scored cells)

Within the fragmentation buffer: before or after exposure, chemical content

Chemical variables: stability, immunogenicity, liposomes

**Works Cited**

1) Olivier T, Migliorini D. Autologous tumor lysate-loaded dendritic cell vaccination in glioblastoma: What happened to the evidence? Rev Neurol (Paris). 2023 Jun;179(5):502-505. doi: 10.1016/j.neurol.2023.03.014. Epub 2023 Apr 1. PMID: 37012085.

2) Li, Yuan, et al. “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST) as a Fast Autologous Cancer Vaccine.” Advanced Science, 26 Mar. 2025, [https://doi.org/10.1002/advs.202502937. Accessed 7 Apr. 2025](https://doi.org/10.1002/advs.202502937.%20Accessed%207%20Apr.%202025).

3) Segal, Jeremy P, et al. “Use of Laser-Capture Microdissection for the Identification of Marker Genes for the Ventromedial Hypothalamic Nucleus.” The Journal of Neuroscience, vol. 25, no. 16, 20 Apr. 2005, pp. 4181–4188, [https://doi.org/10.1523/jneurosci.0158-05.2005. Accessed 1 Dec. 2023](https://doi.org/10.1523/jneurosci.0158-05.2005.%20Accessed%201%20Dec.%202023).

4) Yang, Muyang, et al. f Exploration, vol. 4, no. 6, 28 Mar. 2024, [https://doi.org/10.1002/exp.20230171. Accessed 11 Apr. 2025](https://doi.org/10.1002/exp.20230171.%20Accessed%2011%20Apr.%202025).

5) Vanpouille-Box C, Pilones KA, Wennerberg E, Formenti SC, Demaria S. In situ vaccination by radiotherapy to improve responses to anti-CTLA-4 treatment. Vaccine. 2015 Dec 16;33(51):7415-7422. doi: 10.1016/j.vaccine.2015.05.105. Epub 2015 Jul 3. PMID: 26148880; PMCID: PMC4684480.
