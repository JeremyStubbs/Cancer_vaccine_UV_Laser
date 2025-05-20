**Laser Lithography to Generate Antigens for Autologous Cancer Vaccination**

Jeremy Stubbs MD<sup>1</sup>

<sup>1</sup>Independent Researcher, United States of America

<jeremyb.stubbs@gmail.com>

**Keywords**

Immunotherapy, Antibody, Granulocytes, Eosinophils, Neutrophils, NK cells, T-cells, Crispr

**Introduction**  
Cancer immunotherapy has revolutionized oncology, yet challenges remain in the development of effective, personalized vaccines. This proposal explores the use of lithography technology to generate tumor cell fragments from pathology slices. Lithography is the use of collimated light i.e. lasers with a photomask to etch a pattern on a substrate. Chemically optimized and purified fragments would be injected with adjuvants. The photomask grid pattern dictates fragment size whose optimal dimensions can be determined empirically. Precise molecular disruption exposes native tumor antigens that retain all post-translational modifications unlike another leading cancer vaccine approach - mRNA. Furthermore, if feasible the strategy would be cheap and scalable. Existing technology allows for UV, X-ray, and possibly IR systems to be evaluated.

**Background and Rationale**

In situ vaccination following radiation therapy represents a promising therapeutic strategy that has demonstrated encouraging clinical outcomes. \[5\] However, this is a highly variable process. It’s not clear that radiation produces consistent sized tumor-associated antigen (TAA) fragments. In addition, the highly inflammatory state post-radiation which includes neutrophils who release digestive enzymes may compromise the chemical integrity of fragments, limiting the precision of the immune response

Past attempts for antigen preparation for autologous cancer vaccines have generally relied on enzymatic digestion or mechanical disruption (sonication) of biopsy samples. This is also relatively crude for its lack of ability to make precise sized fragments that maintain the native form of macromolecules.

A slight improvement is a strategy called “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST).” They used x-rays to kill and fragment tumor cells from a biopsy \[2\] This was not an inspiration for me; I found it after I started writing my proposal. But, it is worth mentioning that it kind of uses the same ingredients: light to fragment tissue for a vaccine, only I think the frequency should be UV and it should use a photomask.

My novel thought was to use UV lithography. UV lithography is the use of a UV laser with a photomask (something that selectively blocks light) to etch patterns on a substrate. It is widely used in the semiconductor industry. The same principles can be applied to fragment tumor-associated antigens in a controlled manner, ensuring the generation of appropriately sized glycopeptides that antigen presenting cells (APC) can process and present on major histocompatibility complexes (MHC).

Compared to the aforementioned techniques, it may offer greater control over antigen integrity, size and immunogenicity. The main differences between this new approach and in situ vaccination following radiation therapy are location of light exposure (inside vs outside the patient) and frequency of light (UV vs Ionizing radiation). The possible advantages are: greater control over antigen size, the option to filter unwanted material, the option to chemically optimize the fragments (optimize immunogenicity, optimize stability of fragments), and the ability to better avoid inflammatory degradation either by chemical optimization (adducts, liposomes, hydrogels) or ex-vivo priming of antigen presenting cells (APCs).

UV laser lithography is widely used in semiconductor fabrication to achieve nanoscale precision (currently the smallest transistor is 2nm which is much smaller than a 20-30 nm ribosome). The reason I think it can be applied to vaccine preparation is because ultraviolet frequency is extremely well suited for breaking organic C-C and C-N bonds. In fact, “laser capture microdissection” is a known method of using UV lasers to dissect individual cells. Because of the nice cuts they make, fluorine-based excimer lasers that operate in the UV-C range (around 193 nm) are also used in eye surgery. Deep UV (200–300 nm) can interact with proteins and DNA without massive heat buildup, making it ideal for precise cellular fragmentation. Femtosecond (fs) or picosecond (ps) pulsed UV lasers are especially good at breaking bonds and not disrupting surrounding tissue.

X-rays are another excellent frequency candidate. In fact, x ray photomasks exist, and lithography systems can achieve nearly the same precision as those that employ UV light. X-rays have significantly more energy than UV light. The cell membrane is approximately 10nm thick. Approximately 20-40% of known tumor-associated antigens (TAA) are membrane bound so it is safe to use the outermost portion as the initial target. As a safety margin, let’s examine the penetration of UV and X rays of 10 nm of tightly wound keratin. By some estimates, the UV (300–350 nm) transmission is ~30–40%, and X-ray (1-10 keV) transmission 99%. Less x-rays will be absorbed, but they are higher energy and break bonds much more effectively when they are absorbed.

Table 1. A comparison of UV vs X rays.

|     | **UV Light** | **X-rays** |
| --- | --- | --- |
| **Tissue Penetration** | Poor (microns at most) | Excellent (millimeters to cm) |
| **Precision/Control** | High with lasers | Lower spatial precision (difficult to collimate and reflect/refract) |
| **Damage Type** | Milder photochemistry, DNA damage | Deep ionization, crosslinking, fragmentation |

X rays have fewer numbers of interactions, but each interaction is more likely to break a chemical bond. The overall efficacy of these frequencies may compensate for the difficulties in their optical manipulation.

You don’t need a $200 million ASML machine to do this. All you need is a reliable UV laser source (a few hundred thousand dollars) and a good UV photomask (a few hundred thousand dollars). Wavelengths and Actual Laser System:

- 266 nm (Deep UV, Nd:YAG 4th harmonic) → High precision, strong protein interactions.
- 213 nm (Even deeper UV, Nd:YAG 5th harmonic) → More precise fragmentation control.
- Excimer Lasers (XeCl at 308 nm, ArF at 193 nm) → Used in eye surgery, could be adapted for tumor antigen fragmentation.

IR frequency light interacts with water much more than UV. Thus it will produce more heat and scattering. Water strongly absorbs IR radiation because its molecular vibrations (stretching and bending of O-H bonds) match the energy of IR photons. A skin cell is approximately 30 um in diameter, which corresponds to 109,000 water molecules lined up end to end. Near-IR (800 nm+) would get absorbed by tissue water before reaching the target. Nevertheless, femtosecond (fs) or picosecond (ps) pulsed IR lasers further might allow intracellular disruption of organic bonds before heating. Pulsed IR lasers are tuned to a wavelength in the ~1300–1500 nm range may also minimize heating but maximize bond breaking. Alternatively, low-energy pulses could cause nanobubble formation or localized pressure bursts, rather than full vaporization.

**Practical Considerations:**

The natural target for a lithography system is a thin layer of material. Pathology slices fit that description perfectly. In order to generate enough material for a vaccine, a sizeable biopsy must be taken which can be cut into hundreds or thousands of slices which are treated with the UV laser. The process of preparation, photomask placement, exposure and post-processing must be streamlined. The slice may need to be cut all the way through or simply scored and broken apart later by mechanical means like sonication.

Immediately after the UV laser (or X ray) you’ll have a burst of reactive molecular species—free radicals, aldehydes, oxidized lipids, broken protein domains, exposed cysteines, etc. These fragments could rapidly rebind, aggregate, or denature, which could: mask antigenic sites, reduce immune visibility, make the “vaccine” messy or less effective. In the short-term, these must be stabilized either chemically or physically by freezing them. In the long-term these need to be chemically stabilized so that they can be given in a vaccine.

If you cut the slices while they are kept at cryogenic temperatures, the bonds may break and not reform until the temperature rises. When you raise the temperature, it will be in the presence of a solution that contains the reagents to chemically neutralize the fragments or lock them into a matrix.

I don’t know enough about organic chemistry to offer a solution for quenching reactive fragments, but the questions you must ask are: Is there any chemical reaction you could use to cap biological molecules, specifically lipids, proteins and large carbohydrates so that they don’t recombine after you cut them with a UV laser? To chemically quench or stabilize the fragments right as they form, before they start cross-linking or misfolding, a buffer solution must be present that contains chemicals that react with the fragments. Options are listed below for a “fragmentation buffer”. While there isn't a single universal "magic bullet" reaction, several chemical strategies could potentially be employed to cap the cut ends of lipids, proteins, and large carbohydrates after UV laser cleavage. The specific reaction and capping agent would need to be carefully chosen based on the type of biomolecule, the likely reactive species generated by the laser, and the desired outcome. For all three types of molecules, having a high concentration of a fast-reacting and specific capping agent present immediately after the laser pulse would be critical for success. Radical scavenging and reactions with newly exposed functional groups (thiols, amines, aldehydes/ketones, reducing ends) appear to be the most promising approaches. To chemically quench or stabilize the fragments right as they form, before they start cross-linking or misfolding, a buffer solution must be present that contains chemicals that react with the fragments. Options are listed below in Table 2. for a “fragmentation buffer”.

Locking them into a matrix for long-term stability might be as easy as thawing them in the presence of a biologically compatible superglue (cyanoacrylate). Maybe sonicate it during the curing process to mechanically distribute the fragments evenly throughout the resulting cyanoacrylate matrix. 

Again, I am not a chemist, but I’ll speculate on long-term quenching of fragments. UV laser ablation, especially at 193–248 nm, generates free radicals, carbocations, carbonyls and other oxidized groups, and unstable double bonds. These reactive fragments can recombine, oxidize further, or crosslink, unless they are stabilized quickly. So you want fast-reacting capping agents present in the buffer during irradiation or during thawing.

1\. Proteins – Capping Free Amines, Thiols, and Radicals  
After UV exposure, proteins can be left with:  
Free amines (from lysine or N-termini)  
Free thiols (from cysteine)  
Radicals or oxidized residues (e.g., carbonyls on side chains)

Capping Strategies:  
Iodoacetamide or N-ethylmaleimide (NEM): alkylate thiols to prevent disulfide formation.  
Formaldehyde + sodium cyanoborohydride: for amine capping via reductive methylation.  
Acrylamide: can react with amines and thiols.  
Spin traps (e.g., DMPO, PBN): stabilize free radicals.  
Methionine or other scavengers: quench ROS.

2\. Lipids – Capping Reactive Double Bonds and Aldehydes  
Lipids can form:  
Peroxides and aldehydes (especially polyunsaturated fatty acids)  
Radicals or epoxides

Capping Strategies:  
Butylated hydroxytoluene (BHT) or Trolox: antioxidant scavengers for radicals.  
Hydroxylamine derivatives: react with aldehydes and ketones to form oximes.  
Silylation reagents (e.g., TMS derivatives): protect hydroxyls and carboxylic acids.  
Maleimide-functionalized PEGs: can cap thiol-containing headgroups.

3\. Carbohydrates – Capping Reducing Ends and Hydroxyls  
UV fragmentation of polysaccharides may expose:  
Reducing ends (aldehydes)  
Radicals on carbon chains  
Free hydroxyls

Capping Strategies:  
Sodium borohydride (NaBH4) or cyanoborohydride: reduces aldehydes to stable alcohols.  
Aniline derivatives or hydrazides: form Schiff bases or hydrazones with reducing ends.  
Acetylation or methylation: cap hydroxyls.

Buffer Additives for General Radical and ROS Quenching  
You can add the following to your buffer before or during UV exposure:  
DTT or TCEP: thiol-based reducing agents  
Ascorbic acid: antioxidant  
Methionine: radical scavenger  
Spin traps: for stable radical adducts  
EDTA: chelates metals that catalyze ROS formation  
NEM or iodoacetamide  
Hydroxylamine or borohydride  
Trolox or BHT

Table 2. Fragmentation Buffer Composition and Role.

| **Component** | **Role** |
| --- | --- |
| **N-acetylcysteine (5–10 mM)** | Scavenges ROS, protects thiols |
| **PEG-NHS (0.5–2 mM)** | Blocks exposed amines, reduces aggregation |
| **Mannitol or Sorbitol (10–50 mM)** | Hydroxyl radical scavenger, protects macromolecules |
| **HEPES (25 mM, pH 7.4)** | Stable pH buffer under light/heat |
| **Protease inhibitor cocktail** | Stops enzymatic degradation |
| **Optional: low-concentration TLR ligand (e.g. CpG, poly I:C)** | Primes immune activation after uptake |

One advantage of this strategy is the option to enrich the sample – remove unwanted parts so that you are left with more cancer cells which give a more targeted immune response. You can remove both cellular and non-cellular parts.

Removing non-cancerous cells might be useful, maybe with targeted excision with the UV optical system itself operating like a solid beam not a grid.

A pre-treatment with collagenase might be helpful.  
• Collagen in the stroma can scatter or absorb UV laser energy (collagen’s peptide bonds absorb at ~200–280 nm, overlapping with UV wavelengths like 248 nm). Degrading it first could make ablation more efficient, ensuring the laser focuses on tumor cells and membranes.  
• With ~15–25% of the slice being collagen, pretreatment could dissolve most of it into peptides, leaving a leaner matrix (mostly cells) for the laser to cut. This might yield a higher proportion of phospholipid-rich fragments post-ablation.

Another advantage of this strategy is the option to chemically modify the debris for optimal immunogenicity and stability. You could chemically link the fragments to an immune stimulant. This is different from the stability chemistry mentioned above.

Another option for chemical stability and biological compatibility is to incorporate the fragments into liposomes. There is precedent for this, see “Tumor Cell Membrane‐Based Vaccines: A Potential Boost for Cancer Immunotherapy.” It is research (also out of China) about creating autologous cancer vaccines with liposomes. They used sonication to break up the cells which they then combined with cholesterol or whatever to make hybrid liposomes that contained TAAs. \[4\]

Neutrophils (and other myeloid cells) can indeed respond rapidly to foreign material by releasing reactive oxygen species, proteases, and other enzymes, which could degrade carefully prepared antigen fragments before they reach antigen-presenting cells (APCs) in a meaningful way. This "bystander destruction" is a known issue in vaccine design, especially with tumor lysate-based vaccines.

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
    - Tissue sections are cut into slices like for a pathology slide approximately 1-2 cells thick to increase the likelihood of success. Likely hundreds or thousands of slices need to be cut.
2. UV Laser Exposure in a Grid Pattern:
    - A UV laser (e.g., excimer or femtosecond laser) or X ray laser with a photomask is used to create precise antigen fragments by exposing the sample to a predetermined grid pattern.
    - The pathology slice could be cut while frozen or thawed. Like the size of the fragments, this must be determined empirically along with when to introduce the fragmentation buffer.
    - Note that the laser can be used to cut the sample several times. In fact, it could cut the pathology slice, which is then turned into a lysate and cut again.
3. Fragmentation Buffer: added before or immediately after and contains chemical reagents to prevent recombination.
4. Optional: Thawing and Gentle Sonication to fragment the cut/scored cells.
5. Optional: Form liposomes through known methods like Azafari method. The buffer solution contains components necessary for liposome formation (triacyl glycerides).
6. Optional: Collect and optionally filter or centrifuge to isolate desired particle size range.
7. Optional: chemical modification of fragments

• Use biotin-NHS, PEG-mannose-NHS, or Fc-tagged PEGs during the soak.

• As proteins break apart, their free lysines and N-termini get tagged—simultaneously quenching and targeting the fragments for immunogenicity.  
• Lock the fragments into a matrix

1. Reinject fragments with adjuvants or pulse autologous dendritic cells (DCs) ex vivo, which are then reintroduced into the patient.
2. Immune Activation:  
    • The processed antigens are presented to T cells, initiating an immune response against tumor-specific epitopes.  
    • Co-administered **adjuvants** enhance dendritic cell activation and antigen presentation. A TLR agonist (like CpG DNA, poly-IC, or MPLA) would boost innate immune activation, drawing in antigen-presenting cells. GM-CSF could be injected locally to recruit dendritic cells, ensuring efficient antigen pickup.  
    • A **checkpoint inhibitor** (like anti-PD-1 or anti-CTLA-4) could be combined for even stronger T cell activation.

**Desired Outcomes**

- Precision control over antigen size, optimizing immune recognition.
- Increased reproducibility compared to enzymatic digestion methods.
- Enhanced T cell activation due to efficient antigen processing and presentation.
- Potential for personalized, autologous cancer vaccines tailored to individual patients.

**Discussion – Part I – Justification and Checkpoint Inhibitors**

This approach leverages lithography technology (lasers + photomask) for precise antigen fragmentation, enabling the development of an autologous cancer vaccine. I think this is a sufficiently unique idea that is just plausible enough to warrant trying.

It is similar to _in situ_ vaccination after radiation therapy, something that has shown promising results in early studies. The main differences are the location of light exposure (inside vs outside the patient) and the frequency of light (UV vs Ionizing radiation). Compared to in situ vaccination following radiation therapy the possible advantages are: greater control over antigen size, the option to filter unwanted material, the option to chemically optimize the fragments (optimize immunogenicity, optimize stability of fragments), and the ability to better avoid inflammatory degradation either by chemical optimization (adducts, liposomes, hydrogels) or ex-vivo priming of antigen presenting cells (APCs).

Like all experimental cancer vaccine strategies, this could be combined with a checkpoint inhibitor (like anti-PD-1 or anti-CTLA-4).

**Discussion – Part II – mRNA Vaccines Scientific Basis**

This vaccine strategy could easily be used in a treatment plan that includes mRNA vaccines, but a head-to-head comparison is in order. **The main difference between a UV lithography vaccine and mRNA vaccine is probably heterogeneity vs dose. I stand firmly, though more than anything that these are not mutually exclusive strategies that could be used together synergistically.**

First, let’s discuss the assumptions behind mRNA cancer vaccine technology. The idea behind mRNA cancer vaccines is they identify the mutations in DNA that are likely to result in a 8-11 length peptide presented on MHC I as a result of expression, proteasomal cleavage, transport and MHC I binding. Then of course, the mRNA must at the vaccination site must replicate that. The fundamental questions which I hope to answer by the end of this section are: How accurately can you translate DNA sequence into a neoantigen that will be presented on MHC I at the tumor? How accurately can you translate mRNA to the same neoantigen presented on MHC I at the vaccination site?

To summarize the following long-winded discussion, there are significant unknowns like will two patients with the same MHC genotype but different lysosomal genes present the same peptides? But mRNA vaccines are scientifically plausible. Because of that scientific plausibility, mRNA vaccines should be explored for cancer.

Bias disclaimer: Regarding mRNA-4157 clinical trial design, I don’t agree with cherry picked outcomes like progression free survival after complete resection, which yeah depends on a lot of stuff including surgeon performance. The gold standard has always been and will always be overall survival. They have not released that data or data specifically focusing on separate site vs local recurrence (including upstream lymph nodes) which is essential to determine adequate study design. Furthermore, the sample size of 240 and 260 patients in the phase 3 trials seems grossly insufficient.

I. Is DNA sequencing reliable enough to catch mutations? How often do cancers in different people have the same mutations?

DNA sequencing is reliable enough to trust for both clinical and research purposes, with >95% sensitivity and >99% specificity for high-confidence mutations, provided high-quality samples, sufficient sequencing depth, and robust analysis pipelines are used. COSMIC and TCGA are two well known repositories of known cancer DNA mutations.

In the COSMIC database there are approximately 25 million unique mutations for 1.5 million samples. At the sequence level, some driver mutations (e.g., BRAF V600E, KRAS G12D) are highly consistent across patients with the same cancer type, but most mutations, including passenger mutations, vary significantly due to tumor heterogeneity and patient-specific factors. The combination of mutations for each patient are often highly unique.

II. How reliable are the other steps?

Going from a DNA mutation to an unmodified peptide presented on MHC class I is a monumental task due to the multi-step process, biological variability, and imperfect prediction tools. While DNA sequencing and protein translation are highly reliable, the other steps predictions are less accurate (70-90%). AI models predict neoantigens presented on MHC class I with ~50-70% precision and ~60-80% sensitivity for high-confidence candidates, based on mass spectrometry and clinical trial data. MHC binding predictions are the most accurate (80-90% for common HLA alleles), while proteasomal cleavage (70-80%) and TAP transport (60-70%) predictions are less reliable. Overall, the pipeline is sufficiently reliable for research and clinical applications (e.g., neoantigen vaccines), and emerging technology like mass spectroscopy based peptidonomics may improve it. That might all be true, but the whole process seems like a shot in the dark without enough data transparency.

There are billions of combinations of MHC, but with computers it may be possible to estimate the structure of the presenting domain. You must estimate coding domains of the millions of possible cancer mutations, then estimate the lysosome cleavage into peptides, then you must correlate the diversity of peptides with that diversity of MHC structures. Those numbers are multiplicatively enormous but maybe still estimable with supercomputers.

One fair criticism is databases like NetMHCpan or NetMHCIIpan, which list peptides known to be presented on different MHCs, are based on a wide variety of experimental data like mass spectroscopy and binding affinity, not the gold standard for this sort of data: T cell activation assays. Mass spect and elution data usually depend on isolating a fully folded MHC complex from a group of cells. This process may denature the complex and require computational deconvolution because it does not look at a uniform population of one MHC on a single cell. So far as I can tell there has never been a confirmatory study in which MHC complexes and peptides are randomly selected from the database to evaluate accuracy via T cell activation assays. The T cells would be generated by in vitro pulsing a culture with the peptides long enough until they generate an immune response. Then those T cells would be used to test specific MHC/peptide combinations. These criticisms aren’t meant to dismiss mRNA tech – the data used to make the database is probably good enough – just to maintain scientific honesty. There should be a confirmatory study of the database, and the lack of it seems scientifically dishonest.

But the absence of confirmatory papers might reflect that neoantigen prediction is often embedded within broader studies on mRNA vaccine development which focus on clinical outcomes. The scarcity of standalone papers reflects the field’s focus on integrated pipelines, proprietary methods, and clinical outcomes. It might be counterproductive and slow down progress.

AI is widely used in this process. Since I already talked about NetMHCpan, let’s look at MHC binding as an example of how AI is being used to improve the process. AI can predict which peptides are likely to bind to specific MHC alleles by using algorithms to find patterns between elution data and MHC DNA sequence. AI can also use more explicit algorithms like “Position-Specific Scoring Matrices” which are based on the frequency of amino acids at each position in known binding peptides. But these are limited by the accuracy of their training set data, the elution and mass spect data. Increasingly the training endpoint is clinical outcome not this data. For example, integrated pipelines (e.g., MuPeXI, EDGE) achieve reasonable success in clinical settings, with ~30-50% of predicted neoantigens eliciting T-cell responses. AI algorithms require vast training data which they use to get incremental improvements. True they are not starting from zero, with the NetMHCpan, but again there is a lack of scientific honesty, specifically transparency. Why are there no mathematical estimates for how long it will take before we can expect the algorithms to improve? I would at least like an admission that it is an ongoing process of incremental improvement in the algorithm and an estimate of how many patients it will take to perfect.

III. For mRNA cancer vaccines, peptide presentation must occur twice: at the vaccination site (by APCs, particularly DCs, processing mRNA-encoded neoantigens) and at the tumor site (by tumor cells presenting endogenous neoantigens). How can they possibly get overlap?

The vaccination site relies on mRNA uptake, translation, and DC processing, which is relatively reliable but limited by cleavage and immunogenicity predictions. The tumor site follows the complex DNA-to-MHC pipeline. Differences in proteasomal cleavage between DCs and tumor cells are a key hurdle, but solutions like minimal epitope design and robust neoantigen selection improve success. The process is reliable enough for clinical use (evidenced by ongoing trials), but variability necessitates careful design and validation.

Let’s continue with a head-to-head presentation.

**Discussion – Part III – mRNA Vaccines Comparison**

Both strategies attempt to generate both MHCI and MHCII response. In both cases, the goal is to train the immune system to recognize cancer specific molecules at both the vaccination site and the tumor. Again, UV generated fragments-based vaccines could easily be used in a treatment plan that includes mRNA vaccines. But in a sentence the difference is: **Do you trust your body to get it right with a full variety of antigens but a lower dose of each or do you trust AI and database pipelines to coax the immune system to focus on specific peptide in the tumor by delivering a consistent high dose of them?**

Before we go into an extremely in-depth immunological discussion, in slightly more detail, the main differences can be summarized as:  
**\-It is more likely to generate complex antigens like lipids, proteoglycans, and proteins that undergo post-translational modifications.**  
\-There is a tradeoff between \[broadness of spectrum\] and \[specificity and consistency from one dose to another**\]. There may be an advantage with regards to tumor heterogeneity and tumor evolution over time.** You will get a broader spectrum of epitopes, however, the epitopes from dose to dose will be less reproducible than an mRNA vaccine.  
**\-There are slight differences in the immune response mechanisms, and this may generate a better MHC II and B cell response but it’s possible that mRNA data pipeline technology can identify antigens for MHC I better than the body can. These differences may provide synergy when the technologies are combined.**  
**\-The most striking difference is the cost. This is potentially significantly cheaper than mRNA vaccines which means it is much more scalable especially to markets outside the US.**

From a detailed immunologic perspective, to generate a CD 8+ response, APCs at the vaccination site present mainly peptides 8-11 amino acids long on MHC I complexes to immature T cells, though there may be some glycopeptide presentation. In mRNA vaccines, the mRNA is taken up by a wide variety of local cells which then translate it into peptides, some of which are presented on MHCI via a pathway that presents internal peptides in addition to the pathway used by APCs to present external peptides. The presentation of both internal and external peptides relies on lysosomal degradation. mRNA vaccines specifically engineer the resultant peptide to maximize binding to MHC I and MHC II. The mRNA molecule is not (8-11)x3 bases long. It is much longer, and the target sequence is embedded within restriction enzyme targets and specific sequences in such a way to optimize MHC binding. Often multiple separate 8-11 codons are in a single mRNA molecule and multiple mRNA molecules are used. Both internal and external presentation and engineered MHC I binding bode well for mRNA vaccines theoretically, but realistically the body is pretty good at finding targets itself. For mRNA cancer vaccines, peptide presentation must occur twice: at the vaccination site (by APCs, particularly DCs, processing mRNA-encoded neoantigens) and at the tumor site (by tumor cells presenting endogenous neoantigens from DNA mutations). The vaccination site relies on mRNA uptake, translation, and DC processing, which is relatively reliable but limited by cleavage and immunogenicity predictions. The tumor site follows the complex DNA-to-MHC pipeline, with additional challenges from tumor heterogeneity and immune evasion. Differences in proteasomal cleavage between DCs and tumor cells are a key hurdle, but solutions like minimal epitope design and robust neoantigen selection improve success.

This strategy relies on natural processing mechanisms to select an immunogenic sequence that will get presentation whereas mRNA relies on massive data pipelines integrated with artificial intelligence (AI) reasoning. I have no way to compare the two, but what I can say is there is a tradeoff of variety vs dose. With this strategy all you have to worry about is getting the tumor cells into bite sized bits. This strategy depends on the use of hundreds to thousands of pathology slices, but the whole process will be streamlined. You will get a larger variety of antigens, but the individual amount of any particular antigen will be low within a dose and the antigens may be highly variable from dose to dose. There may be an advantage with regards to tumor heterogeneity and tumor evolution over time, but epitopes from dose to dose will be less reproducible than an mRNA vaccine.

Major challenges exist in both mRNA and this strategy in creating a CD8 response. Viral antigens like spike protein in covid are highly immunogenic and highly expressed on MHCI and come with all sorts of other inflammatory signals from infected cells – not so in cancer. T cell receptors (both CD 4+ and CD 8+) develop to tolerate self-antigens which TAAs fundamentally are. Also, CD 8+ TCRs require MHC I presentation (regardless of whether surface or internal), which is often greatly reduced in tumor cells. Furthermore, tumors are highly heterogeneous and constantly evolving and easily ignore immune attacks.

The real difference lies in B cell and MHC II responses. B cell receptors recognize fully folded post-translationally modified proteins. An activated B cell has various actions including the production of antibodies. B cells are also APCs so they can phagocytose stuff and present it via MHC II to naïve CD 4+ T cells. Other APCs include B cells, dendritic cells, macrophages, etc. MHC II presents a wider range of material than MHC I (including very often glycopeptides) and larger peptides up to 25 amino acids long. But similar to MHC I they present material that has been lysosomally processed to the T cell receptor. Mature CD4+ T cells migrate to the tumor where they interact with resident or migrated APCs there to coordinate CD 8+ and B cell responses, partly via local cytokines. While tumors sometimes can be coaxed into expressing MHCII (e.g. with interferon), this is considered a minor factor.

Short linear peptides coded by mRNA vaccines cannot mimic quaternary structure with post translational modifications. Quaternary structure of a BCR-recognizable domain often involves multiple chains folded and interchain bonded together. And post-translational modifications are likely present in something large enough to be recognized by a B cell receptor. B cell targets most likely have to be external antigens that are not folded into the center of the surface protein complex. But many of the best surface TAAs are post-translationally modified. mRNA vaccines may have elicited a B cell response for covid spike protein because it was secreted from infected cells. Spike protein is a well-studied protein that didn't really change much from strain to covid strain and it is so huge that finding an external unmodified contiguous chain of amino acids was comparatively easy. The problem of finding a unique external contiguous unmodified sequence is much larger for cancer, but possibly doable whereas B cells will have no problem viewing UV lithography generated fragments.

Concerning MHC II presentation, mRNA technology has an advantage of engineered binding optimization (as with MHC I). This strategy may attain comparable MHCII presentation efficiency of chimeric proteins used by mRNA technology if the right adjuvants and chemical optimization or liposomes/nanoparticles are used. Experimental work is needed to optimize the strategy whereas mRNA is a mature technology. This strategy has the advantage of the presentation of a broader range of antigens. MHC II presents a wider range of material than MHC I (including very often glycopeptides) and larger peptides up to 25 amino acids long, so compared to MHC I, MHC II may even better address tumor heterogeneity.

For mRNA cancer vaccines, peptide presentation on MHC II must occur twice: at the vaccination site (by APCs, particularly DCs, processing mRNA-encoded neoantigens) and at the tumor site (by separate APCs). The idea that an APC at the vaccine site will take up the produced protein and process and present it and an APC within tumor will take up necrotic debris process it and present the same thing with any efficiency seems improbable. In this strategy the same material and process is used for MHC II presentation at both the vaccination site and tumor. This probably gives better cross presentation and antigen sharing because the same stuff gets processed the same way.

In both strategies, the MHC II response is limited by the ability of APCs to enter the tumor and pick up antigens for presentation. An effective immune response is also limited because the immune system may be partially or fully tolerized to self-like sequences, and tumors can lose antigen presentation (e.g., via β2M loss). Lastly, again, tumors are highly heterogeneous and constantly evolving and easily ignore immune attacks.

Summary of advantages of mRNA: more consistent dose every time, engineered MHC binding both one and two, internal expression which may increase MHC one presentation.

Summary of advantages of UV lithography: wider variety of antigens, including those with post translational modifications and not proteins, which is particularly good for MHC two and B cells, same processing material for MHC two presentation.

**Basically, do you trust your body to get it right with a full variety of antigens but a lower dose of each or do you trust AI and database pipelines to coax the immune system to focus on specific peptide in the tumor by delivering a consistent high dose of them?**

**It does not escape me that these are potentially complementary strategies based on the fact that this strategy gets a good B cell and MHC II response, and mRNA may provide the MHC I response. Nor does it escape me that this mechanistic explanation could be used to justify combining in situ vaccination after radiation exposure and mRNA vaccination.**

Summary of Where mRNA Cancer Vaccine Tech Struggles compared to UV Lithography:  
\-PTM Ignorance: mRNA vaccines produce canonical proteins — the cell machinery determines PTMs, and current design pipelines don’t fully predict or manipulate them.  
\-Antigen Localization: Many tumor neoantigens are intracellular, requiring MHC-I processing rather than antibody response.  
\-Tumor Heterogeneity: Not all cells in a tumor express the same antigen.  
\-Quaternary Structures & Cryptic Epitopes: If the mutation lies in a region that’s conformational or buried, it may never be exposed unless processed.

Table 3. Core Conceptual Differences

| **Feature** | **mRNA Cancer Vaccines** | **UV Lithography Vaccine Platform** |
| --- | --- | --- |
| **Antigen Format** | Encoded peptides (typically 8–20 aa) | Whole-protein fragments with native PTMs and structures |
| **Post-Translational Modifications (PTMs)** | Ignored or uncontrolled | Preserved and naturally processed by immune cells |
| **Antigen Discovery** | Requires prediction from DNA/RNA | Uses actual tumor tissue; empirical representation |
| **Immune Response** | Weak B cell, Likely Weak MHC I, Strong MHC II | Stronger B cell, Likely Weak MHC I, Unknown MHC II |
| **Complex Antigen Structures** | Poor at mimicking quaternary or cryptic epitopes | Retains antigen conformation, aiding natural processing |
| **Tumor Heterogeneity** | Requires precise selection; may miss variants | Captures entire antigenic landscape of the tumor slice |
| **Practical Output** | Personalized mRNA libraries | Customized, photoprocessed tumor-derived vaccine particles |
| **Cost** | High: require DNA sequencing and custom synthesis | High upfront, low operational |

**Discussion – Part IV – mRNA Synergy**

**I stand firmly, though more than anything that these are not mutually exclusive strategies that could be used together synergistically.**

Broad Antigen Presentation from Tumor Fragments: The fragmented tumor material could provide a comprehensive and unbiased source of tumor-associated antigens, including those not predicted or targeted by the mRNA vaccine. This could prime a broad initial immune response against a wide range of potential targets.

Focused and Enhanced Response from mRNA: The personalized mRNA vaccine could then be designed to specifically boost the immune response against a select set of highly immunogenic or clinically relevant neoantigens identified through prediction algorithms and potentially validated through analysis of the patient's immune response to the fragment vaccine. This allows for a more focused and amplified attack on key tumor targets.

Addressing Antigen Spreading and Evolution: The broad immunity generated by the tumor fragments might help to control tumor cells that lose the specific neoantigens targeted by the mRNA vaccine (antigen escape). The mRNA vaccine could also be updated over time to target newly emerging neoantigens.

Harnessing Different Immune Mechanisms: The fragmented tumor material might stimulate a broader range of immune responses, including innate immunity and different T-cell subsets, while the mRNA vaccine could be optimized to elicit strong CD8+ T-cell responses against specific intracellular antigens.

Improving Antigen Presentation: The UV lithography aspect of your fragment vaccine could potentially be used to optimize the size, shape, or surface properties of the fragments to enhance their uptake and processing by antigen-presenting cells, thereby improving the presentation of all the tumor-derived antigens, including those that might synergize with the mRNA-encoded antigens.

**Discussion – Part V – Feasibility**

Is this strategy possible?

The two big questions are: Can you initially generate fragments via UV lithography of a certain size that don’t lose their native structure or immediately degrade? Can you keep them stable long enough to be injected? I have a feeling that if you could do both of those things, you would be some sort of immune response.

Since this has never been done, we must attempt to infer its feasibility from existing experimental techniques. Two relevant examples are: (1) the use of UV laser-based cellular dissection in pathology, and (2) the preparation of autologous vaccines using enzymatic and hypertonic cell lysis and their effectiveness.

1\. UV Laser Cellular Dissection (Laser Capture Microdissection): "How well does this technique work in producing small sections of the cell?"

Commentary:

Laser capture microdissection (LCM) is highly effective for isolating individual cells or specific regions of tissue. However, it is typically used for anatomical resolution (e.g., entire cells or nuclei), not biochemical fragmentation. That said, the ability of UV lasers—especially excimer and femtosecond-class systems—to break specific covalent bonds is well-documented in material science and microfabrication. Their precision has not been widely tested for molecular-level fragmentation of proteins in a biological context, but the technology does demonstrate proof-of-principle for spatial precision. \[3\] The challenge will be balancing fragmentation versus denaturation, particularly for preserving MHC-relevant epitopes.

**I firmly believe that you do not need to reduce the size down to 15-20 amino acids which is the length of peptide that MHC molecules present. After phagocytosis, lysosomal processing will do that and select the best antigen candidates. Breaking the cells into bite sized bits is the key.**

2\. Enzymatic or Hypertonic Autologous Cancer Vaccines: "How well have these lysates been characterized?"

Commentary:

Most enzymatic or osmotic preparations result in highly heterogeneous lysates which have not been extensively characterized. These are difficult to characterize precisely at the peptide or epitope level. Mass spectrometry can detect components, but in complex mixtures like whole-cell lysates, reproducibility and identification of functional antigens are problematic. Furthermore, harsh lysis (e.g., hypertonic shock, detergents) often leads to protein unfolding, aggregation, and loss of post-translational modifications and thus yields little useful information. \[1\] These are critical for immune recognition. In this regard, UV-mediated fragmentation might offer a more controlled, reproducible way to break proteins into immunologically relevant fragments—if scattering and overexposure can be minimized.

Ultimately, the feasibility depends on how much UV light will scatter through the membrane and cell layers. This is a crucial unknown. UV light at 200–300 nm has shallow penetration depth in biological tissue due to high absorption by proteins and nucleic acids. However, this may be an advantage—by limiting depth, you may effectively fragment material layer by layer, especially in frozen sections.

**Future Direction/Initial Experiments**

Surely benchtop research should be done on this idea. I’ve presented a vast number of possibilities that should be tried here. The most notable variables are:  
\-Within the optical system: wavelength, exposure time, different light patterns (one grid, two grids at angles to each other, multiple passes), temperature  
\-The use of light sonication to break up lightly cut (scored cells)  
\-Within the fragmentation buffer: before or after exposure, chemical content  
\-Chemical variables: stability, immunogenicity, liposomes

One idea that I would like to see tried is cutting the slice while frozen under a thin layer of buffer solution, and transporting it frozen to the patient. Just before injection, it is thawed and sonicated with additional buffer, reagents and adjuvants. Being immobilized in a frozen crystal might stabilize the fragments.

**Works Cited**

1) Olivier T, Migliorini D. Autologous tumor lysate-loaded dendritic cell vaccination in glioblastoma: What happened to the evidence? Rev Neurol (Paris). 2023 Jun;179(5):502-505. doi: 10.1016/j.neurol.2023.03.014. Epub 2023 Apr 1. PMID: 37012085.

2) Li, Yuan, et al. “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST) as a Fast Autologous Cancer Vaccine.” Advanced Science, 26 Mar. 2025, [https://doi.org/10.1002/advs.202502937. Accessed 7 Apr. 2025](https://doi.org/10.1002/advs.202502937.%20Accessed%207%20Apr.%202025).

3) Segal, Jeremy P, et al. “Use of Laser-Capture Microdissection for the Identification of Marker Genes for the Ventromedial Hypothalamic Nucleus.” The Journal of Neuroscience, vol. 25, no. 16, 20 Apr. 2005, pp. 4181–4188, [https://doi.org/10.1523/jneurosci.0158-05.2005. Accessed 1 Dec. 2023](https://doi.org/10.1523/jneurosci.0158-05.2005.%20Accessed%201%20Dec.%202023).

4) Yang, Muyang, et al. Exploration, vol. 4, no. 6, 28 Mar. 2024, [https://doi.org/10.1002/exp.20230171. Accessed 11 Apr. 2025](https://doi.org/10.1002/exp.20230171.%20Accessed%2011%20Apr.%202025).

5) Vanpouille-Box C, Pilones KA, Wennerberg E, Formenti SC, Demaria S. In situ vaccination by radiotherapy to improve responses to anti-CTLA-4 treatment. Vaccine. 2015 Dec 16;33(51):7415-7422. doi: 10.1016/j.vaccine.2015.05.105. Epub 2015 Jul 3. PMID: 26148880; PMCID: PMC4684480.
