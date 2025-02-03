# Awesome-Protein-Design
A (curated) newbie list of free (for academics) tool for Protein Design, with a focus on enzyme design.

## Protein searching
### Sequence based search
 + The gold standard [NIH Blast Server](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
    With this tool you can search tool protein sequence in datbanks, you can also use to search in metagenomic libraries

 + [MGnify tool](https://www.ebi.ac.uk/metagenomics)
    A tool specific for searching searching proteins from methagenomic EBML-librearies

### Structure based search
 + [AlphaFold Database](https://alphafold.ebi.ac.uk/)
    Compare 3D structures predic with deepmind model

 + [ESM Database](https://esmatlas.com/resources?action=fold)
    Meta 3D structure database prediction 

### Other search Tool
 + [Enzyme miner](https://loschmidt.chemi.muni.cz/enzymeminer/)
    More advance searching and comparing tool that also take in considaration protein solubility in E. Coli

 + [protGPT2 & ZymCTRL](https://huggingface.co/nferruz)
    GPT models that you can use to generate sequence that can folds
    * a peptide
    * a Chemical function

 + [RetroBiocat](https://retrobiocat.com/)
    a tool for designing retrosynthetic pathway or search enzyme reaction

## Protein Visualization

 + Gold standard [Pymol](https://www.pymol.org/)
    Most of the software is open-source, it's the standard for protein visualization, it also offer plugin that can offer varius advance analysis or prepping tools

 + [Chimera](https://www.cgl.ucsf.edu/chimera/)
    Similar to python chimera can do both visualization and analysis of the protein

 + [Protein contact atlas](http://pca.mbgroup.bio/index.html)
    A tool for visualization of contact of the protein structures, to have a different view from pymol and Chimera.

## Tools for proteing engeneering

 + [HotspotWizard](https://loschmidt.chemi.muni.cz/hotspotwizard/)
    A tool for many things:
    - Identify pockets that can potentially be dock, and dock in the server
    - Identify point of flexibility 
    - find correlation between points in the structure
    - identify aminoacid that are conserved or mutated
    - based on all of that somes hotspots are suggested to increase the mutability

 + [funclib](https://ablift.weizmann.ac.il/step/fl_terms/)
     Specialized web-server for multipoint mutations based on consensus of evolutions

 + [Caver Web](https://loschmidt.chemi.muni.cz/caverweb/)
    A tool for working on tunnel of the protein. Is it possible to dock a path on a tunnel present in the structure, as well as explore different tunnels. [Cavern](https://www.caver.cz/) is also avaiable as a offline software

 + [fireprot](https://loschmidt.chemi.muni.cz/fireprotweb/)
     A web tool for increasing thermostability of the protein

 + [fireprot ASR](https://loschmidt.chemi.muni.cz/fireprotasr/)
    A webtool for sequence ancestral reconstraction

 + [Loschmidt page](https://loschmidt.chemi.muni.cz/peg/software/)
    Most of the tool presented here are from Loschmidt lab. To keep update on new software or version you can check the official page.

## Tools for protein simulations

 + [make it rain](https://github.com/pablo-arantes/making-it-rain)
    Jupiter notebooks to runs MD simulation on the web, based on the paper: [Making it rain: Cloud-based molecular simulations for everyone](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00998)

 + [Autodock on colab](https://autodock-vina.readthedocs.io/en/latest/colab_examples.html)
    A collection of Google collab for running docking in the cloud

 + [CollabFold](https://github.com/sokrypton/ColabFold?tab=readme-ov-file)
    A collection of Google collab for runnig Aphafold, ESM, Rosettafold etc on the google, based on the paper: [ColabFold: making protein folding accessible to all](https://doi.org/10.1038/s41592-022-01488-1)
    

## Databases

 + The gold Standard [PDB](https://www.uniprot.org/)
    Database with all cristalized protein

 + [Brenda](https://www.brenda-enzymes.org/)
    Database containing all enzimes classified by it's functions

 + [Rhea](https://www.rhea-db.org/)
    Database containing enzyme classified by it's reactions noted as smile reactions

