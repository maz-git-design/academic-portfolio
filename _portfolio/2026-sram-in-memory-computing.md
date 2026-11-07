---
title: "A 7T/8T SRAM In-Memory Computing Macro Supporting Inference and Online Tsetlin Machine Learning for Edge AI"
excerpt: "Design and simulation of a 7T/8T SRAM-based in-memory computing macro supporting inference and online Tsetlin Machine learning for Edge AI.<br/><br/><img src='/academic-portfolio/images/sram-imcmacrolayout.png' alt='SRAM IMC Macro Layout' style='width:250px; max-width:100%; height:auto; display:block; margin:10px 0;'>"
collection: portfolio
permalink: /portfolio/sram-in-memory-computing
date: 2026-08-21
---
<style>
.research-figure {
  margin: 30px auto;
  text-align: center;
}

.research-figure img {
  display: block;
  max-width: 100%;
  max-height: 550px;
  width: auto;
  height: auto;
  margin: 0 auto;
  object-fit: contain;
  border-radius: 6px;
}

.research-figure figcaption {
  margin-top: 10px;
  font-size: 0.85em;
  color: #888;
  font-style: italic;
}

.research-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 20px;
  align-items: center;
  margin: 25px 0;
}

.research-gallery .research-figure {
  margin: 0;
}

@media (max-width: 600px) {
  .research-gallery {
    grid-template-columns: 1fr;
  }
}
</style>

Overview
======

This research investigates the design and simulation of a 7T/8T SRAM-based in-memory computing (IMC) macro supporting both inference and online learning for Tsetlin Machines.

The project focuses on integrating learning operations within SRAM structures to reduce data movement and improve energy efficiency in Edge AI applications.

<figure class="research-figure">
  <img src="{{ site.baseurl }}/images/sram-imc-8T-7T.png"
       alt="7T/8T SRAM-based in-memory computing macro"
       loading="lazy"
       style="background-color: white; padding: 15px; border-radius: 6px;">
  <figcaption>Figure 1. Overview of the proposed 7T/8T SRAM-based IMC design.</figcaption>
</figure>

Research Objectives
======

* Develop SRAM architectures supporting Tsetlin Automata state updates.
* Enable inference and online learning within memory structures.
* Reduce data movement between processing and memory.
* Investigate energy-efficient circuit implementations for Edge AI.

System Architecture
======

The proposed architecture explores the integration of SRAM-based storage and in-memory operations for Tsetlin Machine learning and inference.

<figure class="research-figure">
  <img src="{{ site.baseurl }}/images/sram-imc-8T-archi.png"
       alt="SRAM in-memory computing architecture"
       loading="lazy"
       style="background-color: white; padding: 15px; border-radius: 6px; width: 50%; max-width: 100%; height: auto; box-sizing: border-box;">
  <figcaption>Figure 2. Architecture of the SRAM-based in-memory computing system.</figcaption>
</figure>

7T SRAM Bitcell Design
======

The 7T SRAM bitcell is investigated as a circuit-level building block for implementing in-memory operations.

<div class="research-gallery">

  <figure class="research-figure">
    <img src="{{ site.baseurl }}/images/sram7T.png"
         alt="7T SRAM bitcell"
         loading="lazy">
    <figcaption>Figure 3. 7T SRAM bitcell architecture.</figcaption>
  </figure>

  <figure class="research-figure">
    <img src="{{ site.baseurl }}/images/sram7Tschematic.png"
         alt="7T SRAM transistor-level schematic"
         loading="lazy">
    <figcaption>Figure 4. Transistor-level schematic of the 7T SRAM bitcell.</figcaption>
  </figure>

</div>

8T SRAM Bitcell Design
======

The 8T SRAM bitcell is explored as an alternative architecture for supporting the required in-memory computing operations.

<div class="research-gallery">

  <figure class="research-figure">
    <img src="{{ site.baseurl }}/images/sram8T.png"
         alt="8T SRAM bitcell"
         loading="lazy">
    <figcaption>Figure 5. 8T SRAM bitcell architecture.</figcaption>
  </figure>

  <figure class="research-figure">
    <img src="{{ site.baseurl }}/images/sram8Tschematic.png"
         alt="8T SRAM transistor-level schematic"
         loading="lazy">
    <figcaption>Figure 6. Transistor-level schematic of the 8T SRAM bitcell.</figcaption>
  </figure>

</div>

Physical Design
======

The physical design stage involves transistor-level layout implementation and verification.

### 8T SRAM Layout

<figure class="research-figure"
        style="display: flex; flex-direction: column; align-items: center;">

  <img src="{{ site.baseurl }}/images/sram8Tlayout.png"
       alt="8T SRAM physical layout"
       loading="lazy"
       style="width: 50%; max-width: 100%; height: auto;">

  <figcaption style="display: block; width: 100%; text-align: center; margin-top: 10px;">
    Figure 7. Physical layout of the 8T SRAM bitcell.
  </figcaption>

</figure>

### SRAM IMC Macro Layout

<figure class="research-figure"
        style="display: flex; flex-direction: column; align-items: center;">

  <img src="{{ site.baseurl }}/images/sram-imcmacrolayout.png"
       alt="SRAM in-memory computing macro layout"
       loading="lazy"
       style="width: 50%; max-width: 100%; height: auto;">

  <figcaption style="display: block; width: 100%; text-align: center; margin-top: 10px;">
    Figure 8. Physical layout of the SRAM-based IMC macro.
  </figcaption>

</figure>

Design Methodology
======

* CMOS transistor-level circuit design.
* SRAM bitcell and memory macro development.
* Functional verification through circuit simulation.
* Physical layout design and verification.
* Evaluation of circuit-level performance and energy efficiency.

Tools and Technologies
======

* **EDA:** Cadence Virtuoso, Spectre, and Calibre.
* **Technology:** UMC 65 nm CMOS.
* **Circuit Design:** 7T/8T SRAM and low-power digital CMOS.
* **Application:** Tsetlin Machines and Edge AI.
* **Research Area:** In-memory computing and online machine learning.

Research Information
======

* **Institution:** Newcastle University, United Kingdom
* **Programme:** MSc Microelectronics: Systems & Devices
* **Research Supervisor:** Prof. Alex Yakovlev
* **Year:** 2026