**Proposal for Utilizing Either UV Laser Lithography to Generate Antigens for Autologous Cancer Vaccination**

Jeremy Stubbs MD<sup>1</sup>

<sup>1</sup>Independent Researcher, United States of America

<jeremyb.stubbs@gmail.com>

**Keywords**

Immunotherapy, Antibody, Granulocytes, Eosinophils, Neutrophils, NK cells, T-cells, Crispr

**Introduction**  
Cancer immunotherapy has revolutionized oncology, yet challenges remain in the development of effective, personalized vaccines. This proposal explores the use of lasers to precisely generate tumor cell fragments from pathology slices which can be injected with adjuvants. The idea is to use a controlled grid pattern to generate the optimal sized antigens empirically to enhance the immunogenicity of an autologous cancer vaccine. The grid size determines the fragment length. Precise molecular disruption exposes tumor antigens in a structured way, making them more recognizable by the immune system. This strategy would provide native antigens with all post-translational modifications avoiding the game of trying to predict protein antigens. Furthermore, if feasible (i.e. the laser does not excessively denature antigens), the strategy would be cheap after upfront costs. Existing UV frequency laser technology may allow precise molecular bond disruption. IR and X ray systems are less likely to work but should also be examined.

**Background and Rationale**

UV laser lithography is widely used in semiconductor fabrication to achieve nanoscale precision. The same principles can be applied to fragment tumor-associated antigens in a controlled manner, ensuring the generation of appropriately sized peptides for major histocompatibility complex (MHC) presentation. Traditional antigen preparation methods often rely on enzymatic digestion or mechanical disruption, which lack the precision and reproducibility required for optimal immune activation.

Ultraviolet frequency is extremely well suited for breaking organic C-C, C-N bonds. In fact, “laser capture microdissection” is a known method of using UV lasers to dissect individual cells. It also interacts with water much less compared to infrared light and would produce less heat and scattering. Water strongly absorbs IR radiation because its molecular vibrations (stretching and bending of O-H bonds) match the energy of IR photons. A skin cell is approximately 30 um in diameter, which corresponds to 109,000 water molecules lined up end to end. Near-IR (800 nm+) would get absorbed by tissue water before reaching the target. Deep UV (200–300 nm) can interact with proteins and DNA without massive heat buildup, making it ideal for precise antigen fragmentation.

Wavelengths and Actual Laser System:

- 266 nm (Deep UV, Nd:YAG 4th harmonic) → High precision, strong protein interactions.
- 213 nm (Even deeper UV, Nd:YAG 5th harmonic) → More precise fragmentation control.
- Excimer Lasers (XeCl at 308 nm, ArF at 193 nm) → Used in eye surgery, could be adapted for tumor antigen fragmentation.

Nevertheless, femtosecond (fs) or picosecond (ps) pulsed IR lasers might allow intracellular disruption of organic bonds before heat dissipates. A tuned wavelength (~1300–1500 nm range) may minimize heating but maximize energy absorption at the membrane. Alternatively, low-energy pulses could cause nanobubble formation or localized pressure bursts, rather than full vaporization.

Similarly x-ray systems should be examined critically.

**Methodology**

1. Tumor Tissue or Cell Lysate Preparation: Tumor cells are harvested from the patient and prepared as a lysate or as intact tissue sections.
    - A biopsy or resected tumor sample is obtained from the patient. There are two options to proceed.
    - 1\. Tissue sections are cut into slices like for a pathology slide approximately 1-2 cells thick to increase the likelihood of success.
    - 2\. A cell lysate is prepared.
        1. Gentle Detachment of Cells (Breaking Cell-Cell Bonds) – Tumor cells are treated with a mild detergent or enzymatic solution to disrupt extracellular adhesion proteins while keeping individual cells intact. Approaches include:
        2. Non-Ionic Detergents (e.g., low concentrations of Triton X-100, Tween-20, or digitonin) to weaken adhesion without lysing membranes.
        3. EDTA (0.5 - 5 mM) to chelate calcium ions, weakening cadherin-mediated adhesion.
        4. Mild Trypsinization (low-concentration trypsin or Accutase) to gently digest extracellular adhesion proteins.
2. UV Laser Exposure in a Grid Pattern:
    - A UV laser (e.g., excimer or femtosecond laser) is used to create precise antigen fragments by exposing the sample to a predetermined grid pattern.
    - The grid size determines the fragment length, ideally within the range of ? amino acids, optimizing binding to MHC-I and MHC-II molecules.
    - 1\. The pathology slice is laid upon a stainless steel plate which is cooled to freezing. The laser cuts the slice.
    - 2\. Cutting a lysate via a Single-Channel Optical Processing System (SCOPS) is probably the way to do it. The processed cell suspension is introduced into a single long microfluidic channel equipped with multiple optical systems. Each system sequentially analyzes the contents and applies targeted laser pulses to rupture membranes or further fragment the material as needed. The cumulative effect mimics a factory line, ensuring that by the time the sample reaches the end of the channel all intact cells have been lysed and the fragments are reduced to the optimal size for immunogenicity. Automated optical sensors dynamically adjust laser intensity based on real-time analysis. The single output of the optical processing system consists of well-sized tumor-derived antigenic fragments, which are collected and prepared for vaccine formulation.
    - Note that the laser can be used to cut the sample several times. In fact, it could cut the pathology slice, which is then turned into a lysate and cut again.
3. In Vitro and In Situ Applications: both _in vitro_ and _in situ_ approaches should be evaluated
    - _In Vitro_: The fragmented antigens are collected and reinjected with adjuvants or used to pulse autologous dendritic cells (DCs) ex vivo, which are then reintroduced into the patient.
    - _In Situ_: The UV laser (or IR laser) is applied directly to the tumor site in a minimally invasive manner, generating immunogenic fragments in the tumor microenvironment then adjuvants are injected where the laser blasted the tissue.
4. Immune Activation:
    - The processed antigens are presented to T cells, initiating an immune response against tumor-specific epitopes.
    - Co-administered adjuvants enhance dendritic cell activation and antigen presentation. A TLR agonist (like CpG DNA, poly-IC, or MPLA) would boost innate immune activation, drawing in antigen-presenting cells. GM-CSF could be injected locally to recruit dendritic cells, ensuring efficient antigen pickup.
    - A **checkpoint inhibitor** (like anti-PD-1 or anti-CTLA-4) could be combined for even stronger T cell activation.

**Expected Outcomes**

- Precision control over antigen size, optimizing immune recognition.
- Increased reproducibility compared to enzymatic digestion methods.
- Enhanced T cell activation due to efficient antigen processing and presentation.
- Potential for personalized, autologous cancer vaccines tailored to individual patients.

**Conclusion**

This approach leverages UV lithography technology (and other frequency lasers) for precise antigen fragmentation, enabling the development of an autologous cancer vaccine with enhanced efficacy. By refining the grid pattern and optimizing antigen size, this strategy has the potential to revolutionize personalized cancer immunotherapy.

How does this compare to mRNA vaccines?

\-It is more likely to generate complex antigens like proteoglycans, and proteins that undergo post-translational processing.

\-There is a trade off between \[broadness of spectrum\] and \[specificity and consistency from one dose to another\]. There may be an advantage with regards to tumor heterogeneity and tumor evolution over time. You will get a broader spectrum of epitopes, however, less reproducible than mRNA vaccine. It will be much more difficult to provide the same epitope from one dose to another.

\-The most striking difference is the cost. This is potentially significantly cheaper than mRNA vaccines which means it is much more scalable especially to markets outside the US.
