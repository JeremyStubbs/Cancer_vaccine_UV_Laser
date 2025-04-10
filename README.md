**Laser Lithography to Generate Antigens for Autologous Cancer Vaccination**

Jeremy Stubbs MD<sup>1</sup>

<sup>1</sup>Independent Researcher, United States of America

<jeremyb.stubbs@gmail.com>

**Keywords**

Immunotherapy, Antibody, Granulocytes, Eosinophils, Neutrophils, NK cells, T-cells, Crispr

**Introduction**  
Cancer immunotherapy has revolutionized oncology, yet challenges remain in the development of effective, personalized vaccines. This proposal explores the use of collimated light i.e. lasers with a photomask to precisely generate tumor cell fragments from pathology slices. When purified the fragments would be injected with adjuvants. The photomask transmits a controlled grid pattern to generate the optimal sized antigens empirically. The grid size determines the fragment length. Precise molecular disruption exposes native tumor antigens in a structured way, making them more recognizable by the immune system. This strategy would provide native antigens with all post-translational modifications avoiding the game of trying to predict protein antigens. Furthermore, if feasible the strategy would be cheap and scalable. Existing technology allows for IR, UV and X ray systems to be evaluated.

**Background and Rationale**

Past attempts for antigen preparation methods for autologous cancer vaccines have relied on enzymatic digestion or mechanical disruption, which lack the precision and reproducibility required for optimal immune activation. UV laser lithography is widely used in semiconductor fabrication to achieve nanoscale precision (currently the smallest transistor is 2nm which is much smaller than a 20-30 nm ribosome). The same principles can be applied to fragment tumor-associated antigens in a controlled manner, ensuring the generation of appropriately sized peptides for major histocompatibility complex (MHC) presentation.

Ultraviolet frequency is extremely well suited for breaking organic C-C, C-N bonds. In fact, “laser capture microdissection” is a known method of using UV lasers to dissect individual cells. Fluorine-based excimer laser that operate in the UV-C range (around 193 nm), are also used in eye surgery. Deep UV (200–300 nm) can interact with proteins and DNA without massive heat buildup, making it ideal for precise antigen fragmentation. Femtosecond (fs) or picosecond (ps) pulsed UV lasers are especially good at breaking bonds and not disrupting surrounding tissue.

X-rays are another excellent frequency candidate. In fact, x ray photomasks exist, and lithography systems can achieve nearly the same precision as those that employ UV light. X-rays have significantly less absorption and greater penetration than UV light. For comparison, let’s do a thought experiment. The cell membrane is approximately 10nm thick. Approximately 20-40% of known tumor associated antigens (TAA), are membrane bound. As a safety margin, let’s see the penetration of UV and X rays of 100 nm of tightly wound keratin. By some estimates, the UV (300–350 nm) transmission is ~30–40%, and X-ray (1-10 keV) transmission 99%. But they are higher energy and break bonds much more effectively when they interact.

A comparison of UV vs X rays:

|     | **UV Light** | **X-rays** |
| --- | --- | --- |
| **Tissue Penetration** | Poor (microns at most) | Excellent (millimeters to cm) |
| **Precision/Control** | High with lasers | Lower spatial precision (difficult to collimate and reflect/refract) |
| **Damage Type** | Milder photochemistry, DNA damage | Deep ionization, crosslinking, fragmentation |
| **Immunogenic Fragmentation** | May work but hard to go deep | Can fragment deep tissue into antigens |

X rays have fewer numbers of interactions, but each interaction is more likely to break a chemical bond. That factor may be so advantageous that the overall efficacy of these frequencies more than compensates for the difficulties in their optical manipulation.

Practical Considerations:

Immediately after the UV laser (or X ray) you’ll have a burst of reactive molecular species—free radicals, aldehydes, oxidized lipids, broken protein domains, exposed cysteines, etc. These fragments could rapidly rebind, aggregate, or denature, which could: mask antigenic sites, reduce immune visibility, make the “vaccine” messy or less effective.

So the key is to quench or stabilize the fragments right as they form, before they start cross-linking or misfolding. Options are listed below for a “fragmentation buffer” that is added before fragmentation.

| **Component** | **Role** |
| --- | --- |
| **N-acetylcysteine (5–10 mM)** | Scavenges ROS, protects thiols |
| **PEG-NHS (0.5–2 mM)** | Blocks exposed amines, reduces aggregation |
| **Mannitol or Sorbitol (10–50 mM)** | Hydroxyl radical scavenger, protects macromolecules |
| **HEPES (25 mM, pH 7.4)** | Stable pH buffer under light/heat |
| **Protease inhibitor cocktail** | Stops enzymatic degradation |
| **Optional: low-concentration TLR ligand (e.g. CpG, poly I:C)** | Primes immune activation after uptake |

Simplified Workflow Concept (with Pre-Irradiation Buffering):

1\. Cryopreserve tumor sample or tissue slice (snap freeze or cryosection).

2\. Soak in pre-cooled fragmentation buffer at −20 to 0 °C for 5–10 minutes (ensure full infiltration).

3\. Expose to collimated UV or X-ray.

4\. Allow thawing in same buffer for ~15 minutes.

5\. Collect and optionally filter or centrifuge to isolate desired particle size range.

Extra Layer: In Situ Tagging While Quenching

• Use biotin-NHS, PEG-mannose-NHS, or Fc-tagged PEGs during the soak.

• As proteins break apart, their free lysines and N-termini get tagged—simultaneously quenching and targeting the fragments for immunogenicity.

A similar strategy was tried in China - “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST).” \[2\] This was not an inspiration for me; I found it after I started writing my proposal. But, it still is worth mentioning since it kind of uses the same ingredients: light to fragment tissue for a vaccine. I wish them the best of luck. If they used a photomask (something that selectively blocks light to create an etch pattern), then it is pretty much identical to mine, but I see no indication that they used a photomask.

You don’t need a $200,000,000 ASML machine to do this. All you need is a reliable UV laser source (a few hundred thousand dollars) and a good UV photomask (a few hundred thousand dollars). Wavelengths and Actual Laser System:

- 266 nm (Deep UV, Nd:YAG 4th harmonic) → High precision, strong protein interactions.
- 213 nm (Even deeper UV, Nd:YAG 5th harmonic) → More precise fragmentation control.
- Excimer Lasers (XeCl at 308 nm, ArF at 193 nm) → Used in eye surgery, could be adapted for tumor antigen fragmentation.

IR frequency light interacts with water much more than UV. Thus will produce more heat and scattering. Water strongly absorbs IR radiation because its molecular vibrations (stretching and bending of O-H bonds) match the energy of IR photons. A skin cell is approximately 30 um in diameter, which corresponds to 109,000 water molecules lined up end to end. Near-IR (800 nm+) would get absorbed by tissue water before reaching the target. Nevertheless, femtosecond (fs) or picosecond (ps) pulsed IR lasers further might allow intracellular disruption of organic bonds before heating. Pulsed IR lasers are tuned to a wavelength in the ~1300–1500 nm range may also minimize heating but maximize bond breaking. Alternatively, low-energy pulses could cause nanobubble formation or localized pressure bursts, rather than full vaporization.

**Methodology**

1. Tumor Tissue or Cell Lysate Preparation: Tumor cells are harvested from the patient and prepared as a lysate or as intact tissue sections.
    - A biopsy or resected tumor sample is obtained from the patient. There are two options to proceed.
    - 1\. Tissue sections are cut into slices like for a pathology slide approximately 1-2 cells thick to increase the likelihood of success.
    - 2\. A cell lysate is prepared.
        1. Gentle Detachment of Cells (Breaking Cell-Cell Bonds) – Tumor cells are treated with a mild detergent or enzymatic solution to disrupt extracellular adhesion proteins while keeping individual cells intact. Approaches include: Non-Ionic Detergents (e.g., low concentrations of Triton X-100, Tween-20, or digitonin) to weaken adhesion without lysing membranes. EDTA (0.5 - 5 mM) to chelate calcium ions, weakening cadherin-mediated adhesion. Mild Trypsinization (low-concentration trypsin or Accutase) to gently digest extracellular adhesion proteins.
2. UV Laser Exposure in a Grid Pattern:
    - A UV laser (e.g., excimer or femtosecond laser) or X ray laser with a photomask is used to create precise antigen fragments by exposing the sample to a predetermined grid pattern.
    - The grid size determines the fragment length, ideally within the range of ? amino acids, optimizing binding to MHC-I and MHC-II molecules.
    - 1\. The pathology slice is laid upon a stainless steel plate which is cooled to freezing. The laser cuts the slice.
    - 2\. Cutting a lysate via a Single-Channel Optical Processing System (SCOPS). The processed cell suspension is introduced into a single long microfluidic channel equipped with multiple optical systems. Each system sequentially analyzes the contents and applies targeted laser pulses to rupture membranes or further fragment the material as needed. The cumulative effect mimics a factory line, ensuring that by the time the sample reaches the end of the channel all intact cells have been lysed and the fragments are reduced to the optimal size for immunogenicity. Automated optical sensors dynamically adjust laser intensity based on real-time analysis. The single output of the optical processing system consists of well-sized tumor-derived antigenic fragments, which are collected and prepared for vaccine formulation.
    - Note that the laser can be used to cut the sample several times. In fact, it could cut the pathology slice, which is then turned into a lysate and cut again.
3. In Vitro and In Situ Applications: both _in vitro_ and _in situ_ approaches should be evaluated
    - _In Vitro_: The fragmented antigens are collected and reinjected with adjuvants or used to pulse autologous dendritic cells (DCs) ex vivo, which are then reintroduced into the patient.
    - _In Situ_: The UV laser (or IR laser) is applied directly to the tumor site in a minimally invasive manner, generating immunogenic fragments in the tumor microenvironment then adjuvants are injected where the laser blasted the tissue.
4. Immune Activation:
    - The processed antigens are presented to T cells, initiating an immune response against tumor-specific epitopes.
    - Co-administered **adjuvants** enhance dendritic cell activation and antigen presentation. A TLR agonist (like CpG DNA, poly-IC, or MPLA) would boost innate immune activation, drawing in antigen-presenting cells. GM-CSF could be injected locally to recruit dendritic cells, ensuring efficient antigen pickup.
    - A **checkpoint inhibitor** (like anti-PD-1 or anti-CTLA-4) could be combined for even stronger T cell activation.

**Desired Outcomes**

- Precision control over antigen size, optimizing immune recognition.
- Increased reproducibility compared to enzymatic digestion methods.
- Enhanced T cell activation due to efficient antigen processing and presentation.
- Potential for personalized, autologous cancer vaccines tailored to individual patients.

**Discussion**

This approach leverages lithography technology (lasers + photomask) for precise antigen fragmentation, enabling the development of an autologous cancer vaccine with enhanced efficacy.

Since this has never been done, we must attempt to infer its feasibility from existing experimental techniques. Two relevant examples are: (1) the use of UV laser-based cellular dissection in pathology, and (2) the preparation of autologous vaccines using enzymatic and hypertonic cell lysis and their effectiveness.

1\. UV Laser Cellular Dissection (Laser Capture Microdissection): "How well does this technique work in producing small sections of the cell?"

Commentary:

Laser capture microdissection (LCM) is highly effective for isolating individual cells or specific regions of tissue. However, it is typically used for anatomical resolution (e.g., entire cells or nuclei), not biochemical fragmentation. That said, the ability of UV lasers—especially excimer and femtosecond-class systems—to break specific covalent bonds is well-documented in material science and microfabrication. Their precision has not been widely tested for molecular-level fragmentation of proteins in a biological context, but the technology does demonstrate proof-of-principle for spatial precision. \[3\] The challenge will be balancing fragmentation versus denaturation, particularly for preserving MHC-relevant epitopes.

2\. Enzymatic or Hypertonic Autologous Cancer Vaccines: "How well have these lysates been characterized?"

Commentary:

Most enzymatic or osmotic preparations result in highly heterogeneous lysates which have not been extensively characterized. These are difficult to characterize precisely at the peptide or epitope level. Mass spectrometry can detect components, but in complex mixtures like whole-cell lysates, reproducibility and identification of functional antigens are problematic. Furthermore, harsh lysis (e.g., hypertonic shock, detergents) often leads to protein unfolding, aggregation, and loss of post-translational modifications and thus yields little useful information. \[1\] These are critical for immune recognition. In this regard, UV-mediated fragmentation might actually offer a more controlled, reproducible way to break proteins into immunologically relevant fragments—if scattering and overexposure can be minimized.

Ultimately, the feasibility depends on how much UV light will scatter through the membrane and cell layers. This is a crucial unknown. UV light at 200–300 nm has shallow penetration depth in biological tissue due to high absorption by proteins and nucleic acids. However, this may be an advantage—by limiting depth, you may effectively fragment material layer by layer, especially in frozen sections. For that, you may need to used two laser grids, each 45 degrees off vertical in the opposite direction of each other. Their vertices would be situated in topmost layer of the pathology slice – think nanometers beneath the surface. The frozen immobilization of the cells would prevent mixing after the fragments are generated. Buffer washes would then remove these fragments. The process could be repeated sequentially until the whole slice is fragmented in to nanometer fragments. For comparison, a ribosome is approximately 20-30 nm in diameter.

X rays have fewer numbers of interactions, but each interaction is more likely to break a chemical bond. That factor may be so advantageous that the overall efficacy of these frequencies more than compensates for the difficulties in their optical manipulation.

How does this compare to mRNA vaccines? For your information, this vaccine could easily be used in a treatment plan that includes mRNA vaccines. They are not mutually exclusive. But this is how it differs.

\-It is more likely to generate complex antigens like lipids, proteoglycans, and proteins that undergo post-translational modifications.

\-There is a tradeoff between \[broadness of spectrum\] and \[specificity and consistency from one dose to another\]. There may be an advantage with regards to tumor heterogeneity and tumor evolution over time. You will get a broader spectrum of epitopes, however, the epitopes from dose to dose will be less reproducible than an mRNA vaccine.

\-The most striking difference is the cost. This is potentially significantly cheaper than mRNA vaccines which means it is much more scalable especially to markets outside the US.

**Future Direction/Initial Experiments**

Measure the feasibility of a UV laser to break well known easily produced macromolecules in a controlled way.

Develop a fragmentation buffer.

Refine the grid pattern to optimize antigen delivery.

Choice of adjuvant and checkpoint inhibitor studies.

**Works Cited**

1) Olivier T, Migliorini D. Autologous tumor lysate-loaded dendritic cell vaccination in glioblastoma: What happened to the evidence? Rev Neurol (Paris). 2023 Jun;179(5):502-505. doi: 10.1016/j.neurol.2023.03.014. Epub 2023 Apr 1. PMID: 37012085.

2) Li, Yuan, et al. “Fragment Autoantigens Stimulated T‐Cell‐Immunotherapy (FAST) as a Fast Autologous Cancer Vaccine.” Advanced Science, 26 Mar. 2025, [https://doi.org/10.1002/advs.202502937. Accessed 7 Apr. 2025](https://doi.org/10.1002/advs.202502937.%20Accessed%207%20Apr.%202025).

3) Segal, Jeremy P, et al. “Use of Laser-Capture Microdissection for the Identification of Marker Genes for the Ventromedial Hypothalamic Nucleus.” The Journal of Neuroscience, vol. 25, no. 16, 20 Apr. 2005, pp. 4181–4188, <https://doi.org/10.1523/jneurosci.0158-05.2005>. Accessed 1 Dec. 2023.
