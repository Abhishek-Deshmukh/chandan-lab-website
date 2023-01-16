<template>
  <!-- <img src="/img/hood.jpg" class="pt-7"> -->
  <marquee :img-urls="['/img/hood.jpg', '/img/hood2.jpg', '/img/wells.jpg', '/img/etbr_area.jpg', '/img/microscope.jpeg', '/img/screen.jpg', '/img/sds_page_area.jpg']" />

  <div class="container mx-auto text-left">
    <h1 class="text-4xl underline pt-7 pl-3">
      Research
    </h1>

    <ResearchCard
      title="Functional importance of thermosensitive TRPM8 channel in inflammatory conditions"
      description="Inflammatory disease conditions, such as in inflammatory bowel disease (IBD), colitis, neuronal inflammation, arthritis, brain inflammation, asthma, COPD, autoimmune diseases etc. involve various cellular functions that have involvement of thermosensitive TRP channels. Hence, understanding of how these channels affect in any diseased conditions and their response in a synergistic or antagonistic way will pave the way to novel therapeutic approaches."
      img="/img/TRPM8 conservation - Deep Shikha.png"
    />

    <div class="w-100% m-3 bg-gray-200 dark:bg-gray-800 xl:h-xl rounded-xl">
      <div class="xl:flex xl:flex-row">
        <div class="xl:basis-full xl:h-xl xl:pt-10">
          <img src="/img/ram_model.jpg" class="xl:h-40% xl:mx-auto xl:mb-5 md:mx-auto md:pt-9" style="height:-webkit-fill-available">
        </div>
        <div class="xl:basis-full xl:pt-8 xl:pr-10 xl:pb-5 md:p-7 p-5">
          <h2 class="text-4xl">
            Presence of TRPV3 in macrophage lysosomes helps in skin wound healing against bacterial infection
          </h2>
          <div class="bg-teal-300 w-10 h-2 my-3" />
          <p class="text-xl xl:text-left md:text-center">
            Transient Receptor Potential Vanilloid subtype 3 (TRPV3) is a non-selective cation channel that is known to be activated by physiological temperature and endogenous ligands. Involvement of TRPV3 in different skin functions has been reported. In this work, we demonstrate that activation of TRPV3 by FPP, an endogenous ligand enhances skin wound healing and bacterial clearance there. We report for the first time that TRPV3 is endogenously expressed in macrophages and activation of TRPV3 results in efficient bacterial clearance. We propose that TRPV3 act as a lysosomal regulator and sensor for cellular stress. These findings may have broad implications in understanding the cellular stress and TRPV3-induced channelopathies and may have clinical relevance to skin infection treatment.
          </p>
        </div>
      </div>
    </div>
    <ResearchCard
      title="Hydrogel-Mediated Release of TRPV1 Modulators to Fine Tune Osteoclastogenesis"
      description="Bone defects, including bone loss due to increased osteoclast activity, have become a global health-related issue. Osteoclasts attach to the bone matrix and resorb the same, playing a vital role in bone remodeling. Ca2+ homeostasis plays a pivotal role in the differentiation and maturation of osteoclasts. In this work, we examined the role of TRPV1, a nonselective cation channel, in osteoclast function and differentiation. We demonstrate that endogenous TRPV1 is functional and causes Ca2+ influx upon activation with pharmacological activators [resiniferatoxin (RTX) and capsaicin] at nanomolar concentration, which enhances the generation of osteoclasts, whereas the TRPV1 inhibitor (5′-IRTX) reduces osteoclast differentiation."
      img="/img/ranbir model - Rokade Tejas Pravin.gif"
    />
    <ResearchCard
      title="TRPV4 acts as a mitochondrial Ca2+-importer and regulates mitochondrial temperature and metabolism"
      description="TRPV4 is associated with the development of neuropathic pain, sensory defects, muscular dystrophies, neurodegenerative disorders, Charcot Marie Tooth and skeletal dysplasia. In all these cases, mitochondrial abnormalities are prominent. Here, we demonstrate that TRPV4, localizes to a subpopulation of mitochondria in various cell lines. Improper expression and/or function of TRPV4 induces several mitochondrial abnormalities. TRPV4 is also involved in the regulation of mitochondrial numbers, Ca2+-levels and mitochondrial temperature. Accordingly, several naturally occurring TRPV4 mutations affect mitochondrial morphology and distribution. These findings may help in understanding the significance of mitochondria in TRPV4-mediated channelopathies possibly classifying them as mitochondrial diseases."
      img="/img/mitochondrian model - Rokade Tejas Pravin.png"
    />
    <ResearchCard
      title="TRPV4 interacts with MFN2 and facilitates endoplasmic reticulum-mitochondrial contact points for Ca2+-buffering"
      description="Mitochondrial fission-fusion events, distribution, and Ca2+-buffering abilities are relevant for several diseases, yet are poorly understood events. TRPV4 channels are a group of thermosensitive ion channel which regulate cellular and mitochondrial Ca2+-level. The underlying mechanisms of the change in mitochondrial dynamics upon modulation of TRPV4 channel are ill explored."
      img="/img/ms 2model - Rokade Tejas Pravin.png"
    />
    <ResearchCard
      title="Importance of the crosstalk between TRP channels and cytoskeleton in chronification of pain."
      description="Recent results suggest that different cytoskeleton as well as multiple receptors recognizing several noxious stimuli contribute to the pain signaling. Several key molecular factors which are involved in acute and chronic pain have been identified. Among those, TRPV receptors (TRPV1-6) are important as these receptors act as non-selective cation channels and recognize several stimuli, and integrate extracellular as well as intracellular signaling events. Interestingly, involvement of microtubule cytoskeleton in the chronification of pain has been speculated for a long time. We are the first one to demonstrate the physical interaction between TRPV channels with microtubule cytoskeleton and functional relevence of such cross-talk in the context of different cellular functions."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/r2.png"
    />
    <ResearchCard
      title="Importance of TRP channels as a sub-membranous signalling scaffold."
      description=" Taxol®, a microtubule stabilizer, often used as a chemotherapeutic drug in the treatment of cancer and AIDS is known to induce severe and chronic neuropathic pain. However, the exact molecular mechanisms of Taxol®-induced strong chronic pain is currently not known. TRP ion channels act as a molecular scaffold at the sub-membranous region, interact with different cellular components including microtubule cytoskeleton and contribute to different pain signaling. Among all channels, we are interested to elucidate the role of thermo-sensitive ion channels, namely TRPV channels (TRPV1-6), TRPM8 and TRPA1 in the context of Calcium ion-dependent as well as Calcium ion-independent signaling and further cytoskeletal reorganization. Such understanding has importance in the context to chemotherapy-induced chronifiction of pain."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/proj1.png"
    />
    <ResearchCard
      title="Regulation of vesicular recycling by TRP channels."
      description=" Receptor-mediated uptake, exocytosis, endocytosis, vesicle trafficking and recycling are complex cellular events which control several cellular functions. For neurons, such functions in turn control synaptic functions, release and/or uptake of specific neurotransmitters. Regulation of vesicular recycling also regulates the neuronal structures and connectivity. Interestingly, different thermosensitive TRP channels regulate these aspects in a very specific and unique manner. Using high-end imaging techniques we characterize these TRP-mediated vesicular recycling and membrane organization. Such understandings have broad importance in different neuronal as well as non-neuronal systems and have immense implications to dissect pathophysiological disorder at the cellular and molecular levels. "
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/r3.png"
    />

    <ResearchCard
      title="TRPV-mediated channelopathy"
      description="Rare yet naturally occurring mutations in TRPV channels are known to induce several critical pathophysiological disorders due to altered channel function, regulation and/or distribution. For example, mutations in TRPV4 lead to development of CMT2 disease and other mascular dystrophies. Similarly, mutations in TRPV3 lead to “Olmsted Syndrome”. Such mutations alter channels' structure-function relationship and affect cellular functions largely. We aim to understand the molecular and cellular mechanisms that go wrong in such cases."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/proj3.png"
    />
    <ResearchCard
      title="Importance of TRP channels in reproduction"
      description="TRP channels are present in several parts of the reproductive tissues including mature male gametes. In sperm cells, thermosensitive TRP channels seem to play diverse and complex functions such as thermosensation, Calcium signaling, capacitation, acrosomal reaction, regulation of sperm motility and fertility. We explore these functions in details. Such understandings will have both clinical and commercial importance in future as well."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/proj4.png"
    />
    <ResearchCard
      title="TRP channels in immune functions."
      description="Immune activation is a temperature dependent event and also needs massive Calcium influx. Indeed, so far several reports have suggested that TRP channels are present in the immune cells where diverse immune functions are regulated by this group of proteins. We investigate the importance of thermosensitive TRP ion channels in mammalian immune systems."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/proj5.png"
    />
    <ResearchCard
      title="Molecular Evolution of TRP channels"
      description="Genes coding for TRP channels are present in fungus to human (but so far have not been identified in plants). In all these species, TRP channels mainly act as a set of molecular tools required for different “sensory” functions. Over millions of years, such functions in turn play crucial role in the adaptation, ecological niche formation, speciation and also in evolution. Analyzing the sequences of TRP channels from different species provides useful information regarding the selection pressure and the molecular evolution of these channels. Such in silico analysis helped us to identify certain hidden motifs and characterize such motifs in details, which provides useful information regarding the molecular mechanism of these channels per se."
      img="https://www.niser.ac.in/~chandan/images/content/demo-only/proj6.png"
    />
  </div>
</template>
