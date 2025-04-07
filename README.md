# Awesome-Protein-Design
A (curated) newbie list of free (for academics) tools for Protein Design, focusing on enzyme design.

## Protein searching
### Sequence-based search
 + The gold standard [NIH Blast Server](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
   
    With this tool you can search for protein sequences in databanks, you can also use it to search in metagenomic libraries.

 + [MGnify tool](https://www.ebi.ac.uk/metagenomics)
   
    A tool specific for searching proteins from metagenomic EBML-libraries.

### Structure-based search
 + [AlphaFold Database](https://alphafold.ebi.ac.uk/)
   
    Compare protein 3D structures and predict with Deepmind model.

 + [ESM Database](https://esmatlas.com/resources?action=fold)
   
    Meta 3D structure database prediction.

### LLM based tools

+ [protGPT2 & ZymCTRL](https://huggingface.co/nferruz)
   
    Language models that you can use to generate sequences with a high probability of fold:

    * ProtGPT2 needs a peptide as input
    * ZymCTRL needs a Chemical reaction in smile format as input.

+ **EVO-2**, DNA functional model.

   It's a model designed principally for DNA and genomic, it could be usefull for some specific application, i.e. if you are working on DNA sequence based source. 

  * [Nvidia's server](https://build.nvidia.com/nvidia/evo2-protein-design)

  * [Arc instute's server](https://arcinstitute.org/tools/evo/evo-designer )


### Other search tools

+ [Enzyme miner](https://loschmidt.chemi.muni.cz/enzymeminer/)
   
    More advanced searching and comparing tools that also take into consideration protein solubility in E. Coli.

 + [RetroBiocat](https://retrobiocat.com/)
   
    A tool for designing retrosynthetic pathways or search enzyme reactions.

## Protein Visualization

 + Gold standard [Pymol](https://www.pymol.org/)
   
    Most of the software is open-source, it's standard for protein visualization, and it also offers plugins that can offer various advanced analysis or prepping tools.

+ [chatMol](https://chatmol.org/)

  A pymol plugin to perform operation on pymol by using natural languange throught chatGPT. If you are a beginner, or you want to use it just one time is the software for you.

 + [Chimera](https://www.cgl.ucsf.edu/chimera/)
   
    Similar to Pymol, Chimera can do both visualization and analysis of the protein.

 + [Protein contact atlas](http://pca.mbgroup.bio/index.html)
   
    A tool for visualization of contact within the protein structure, to have a different view respect to Pymol and Chimera.

 + [Pymol fitter](https://github.com/HiteSit/PyMol_Fitter) 
   
   A docker image for the simple installation of a Pymol installation that is able to dock on your machine
 

## Tools for protein engineering

 + [HotspotWizard](https://loschmidt.chemi.muni.cz/hotspotwizard/)
   
    A tool for many things:
    - Identify pockets that can potentially be dock, and dock them in the server
    - Identify points of flexibility 
    - Find correlations between points in the structure
    - Identify amino acids that are conserved or mutated
    - Based on these informations the software suggests some hotspots that are most probable to make a difference in your protein.

 + [funclib](https://ablift.weizmann.ac.il/step/fl_terms/)
   
     Specialized web server for multipoint mutations based on consensus of evolutions.

 + [Caver Web](https://loschmidt.chemi.muni.cz/caverweb/)
   
    A tool for searching and dock on tunnels inside the proteins. Is it possible to dock a path on a tunnel present in the structure, as well as explore different hypothetical tunnels. [Cavern](https://www.caver.cz/) is also available as an offline software.

 + [fireprot](https://loschmidt.chemi.muni.cz/fireprotweb/)
   
     A web tool for increasing the thermostability of the protein.

 + [fireprot ASR](https://loschmidt.chemi.muni.cz/fireprotasr/)
   
    A web tool for sequence ancestral reconstruction.

 + [Loschmidt page](https://loschmidt.chemi.muni.cz/peg/software/)
   
    Most of the tools presented here are from the Loschmidt lab. To keep updated on new tools you can check their official page.

## Tools for protein simulations and folding

 + [make it rain](https://github.com/pablo-arantes/making-it-rain)
   
    Jupiter notebooks to run MD simulation on the web, based on the paper: [Making it rain: Cloud-based molecular simulations for everyone](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00998).

 + [Autodock on colab](https://autodock-vina.readthedocs.io/en/latest/colab_examples.html)
   
    A collection of Google collab for running docking in the cloud.

 + [CollabFold](https://github.com/sokrypton/ColabFold?tab=readme-ov-file)
   
    A collection of Google collab for running Aphafold, ESM, Rosettafold, etc. on Google's Cloud, based on the paper: [ColabFold: making protein folding accessible to all](https://doi.org/10.1038/s41592-022-01488-1).

 + [RFDiffusion collab](https://colab.research.google.com/github/sokrypton/ColabDesign/blob/v1.1.1/rf/examples/diffusion.ipynb)
   A collab that use David Backer's RFdiffusion algorithm to generate a backbone from a structure.

 + **QM/MM simulation**
   
   Unfortunately, there are no ready-to-use tools to perform such calculations.
   I was able to find just a tutorial from [CPPbiosim](https://github.com/CCPBioSim/qmmm-workshop) and a simple Google collab [notebook](https://colab.research.google.com/github/CCBatIIT/modelingworkshop/blob/main/labs/3-2/qmmm.ipynb) to move first step in calculation. Maybe with a little tweaking, it can work on your case.
    

## Databases

 + The gold Standard [PDB](https://www.uniprot.org/)
   
    Database with all crystallized proteins.

 + [Brenda](https://www.brenda-enzymes.org/)
   
    Database containing all enzymes classified by their functions.

 + [Rhea](https://www.rhea-db.org/)
   
    Database that contains enzymes classified by its reactions noted as smile reactions.

# License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

This means you are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:
- Attribution — You must give appropriate credit
- NonCommercial — You may not use the material for commercial purposes
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

This is a human-readable summary of (and not a substitute for) the [license](http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).
