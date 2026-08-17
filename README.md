Drosophila Adult Half Brain
============================

Domains from confocal serial section image data used for the study "A Systematic Nomenclature for the Insect Brain" Kei Ito, et al.

This has a tricolor brain template (half-brain) displaying presynaptic (n-syb-GFP, green ), postsynaptic (GABA receptor targeted Rdl-HA receptor, blue) and cytoplasmic counter stains (Cytoplasmic DsRed, red).

Original confocal serial section image data used for the study "A Systematic Nomenclature for the Insect Brain"

A Systematic Nomenclature for the Insect Brain
Kei Ito, Kazunori Shinomiya, Masayoshi Ito, J. Douglas Armstrong, George Boyan, Volker Hartenstein, Steffen Harzsch, Martin Heisenberg, Uwe Homberg, Arnim Jenett, Haig Keshishian, Linda L. Restifo, Wolfgang Rossler, Julie H. Simpson, Nicholas J. Strausfeld, Roland Strauss, and Leslie B. Vosshall; Insect Brain Name Working Group
Neuron 81, 755-765 (2014)
https://doi.org/10.1016/j.neuron.2013.12.017

This archive supplements the above study by providing essential raw image data. It contains the following files:

1. tricoloranterior1024.tif_[red/green/blue].nrrd inside the template directory
> This was derived from the original tiff format (not available here): 
> InsectBrainNomenclature_tricolor_1024.zip (250 MB)
> 1024 x 1024 pixels x 135 sections (ZIP-compressed archive of a folder containing 135 images)
> 
> Original TIFF image files of the serial sections of a Drosophila melanogaster brain that is tricolor-labeled with the combination of the following reporters:
> - cytoplasmic DsRed (UAS-DsRed; Verkhusha et al., 2001; red channel), 
> - presynaptic GFP (synaptic-vesicles-targeted UAS-n-syb-GFP; Estes et al., 2000; green channel), 
> - postsynaptic Rdl-hemagglutinin (GABA-receptor-targeted UAS-Rdl-HA; Sanchez-Soriano et al., 2005; blue channel). 
> They are expressed with the pan-neuronal elav-GAL4 expression driver (C155; Lin and Goodman, 1994).
>
> The image was acquired using a confocal laser-scanning microscope LSM510 (Zeiss) with a 40x water-immersion C-Apochromat objective (n.a. = 1.2). Each section was recorded with the resolution of 1024 x 1024 pixels and 1.41-um optical z-slice steps. Consequently, the xyz voxel size of the image stack is 0.32 um by 0.32 um by 1.41 um. 
> 
> Note that, because of the excess amount of ectopic protein expression, the presynaptic and postsynaptic labeling (especially the latter) is not completely specific, visualizing not only synaptic sites but also cell bodies and large fiber bundles.


2. InsectBrainNomenclature_tricolor_512.zip (65 MB) - Lower resolution copy not used by VFB and hance not included
> 512 x 512 pixels x 135 sections (ZIP-compressed archive of a folder containing 135 images)
>
> Down-sampled version of the above files, which should be used together with the following .am files.
> The xyz voxel size of the image stack is 0.64 um by 0.64 um by 1.41 um. 

3. InsectBrainNomenclature_neuropil.am (3.9 MB) avaiable under the combinedIndexFiles directory.
> 512 x 512 pixels x 135 sections
> 
> Amira labelfield files of the synapse-rich neuropils defined in the Systematic Nomenclature. Voxel size as above.

4. InsectBrainNomenclature_fiber_bundle.am (1.7 MB)
> 512 x 512 pixels x 135 sections
> 
> Amira labelfield files of the landmark fiber bundles defined in the Systematic Nomenclature. Voxel size as above.
>  
> Note: One can open Amira labelfield files with ImageJ as well as Amira software (Mercury Inc.)

5. readme.txt
> original ref document included with files.

6. refData / [neuropil/tract]_domain_data.tsv give the index numbers against FlyBase references for numbered domain files and combined index files.

> Original Note: The files 2, 3 and 4 will be useful for spatially matching the defined volumes of synapse-rich neuropils and landmark fiber bundles with the images of other brain samples using three-dimensional registration software such as Computational Morphometry Toolkit (Jefferis et al., 2007) or Brain-Aligner (Peng et al., 2011). The green channel of the BrainName_tricolor_512 images (UAS-n-syb-GFP) resembles the labeling pattern of the anti-Bruchpilot nc82 antibody (Wagh et al., 2006) that is used widely for background labeling of brain samples. By comparing UAS-n-syb-GFP images and nc82 images, one can use the provided image files as a target template onto which your own image data would be morphed and registered, or alternatively, morph the provided image files to any target templates used for your own particular study. 

References

Estes, P.S., Ho, G.L., Narayanan, R., and Ramaswami, M. (2000). Synaptic localization and restricted diffusion of a Drosophila neuronal synaptobrevin-green fluorescent protein chimera in vivo. J. Neurogenet. 13, 233-255.

Jefferis GS, Potter CJ, Chan AM, Marin EC, Rohlfing T, Maurer CR Jr, Luo L. (2007). Comprehensive maps of Drosophila higher olfactory centers: spatially segregated fruit and pheromone representation. Cell. 128, 1187-203.

Lin, D.M., and Goodman, C.S. (1994). Ectopic and increased expression of Fasciclin II alters motoneuron growth cone guidance. Neuron 13, 507-523.

Peng, H., Chung, P., Long, F., Qu, L., Jenett, A., Seeds, A.M., Myers, E.W., and Simpson, J.H. (2011). BrainAligner: 3D registration atlases of Drosophila brains. Nat. Methods 8, 493-500.

Sanchez-Soriano, N., Bottenberg, W., Fiala, A., Haessler, U., Kerassoviti, A., Knust, E., L?hr, R., and Prokop, A. (2005). Are dendrites in Drosophila homologous to vertebrate dendrites? Dev. Biol. 288, 126-138.

Verkhusha, V.V., Otsuna, H., Awasaki, T., Oda, H., Tsukita, S., and Ito, K. (2001). An enhanced mutant of red fluorescent protein DsRed for double labeling and developmental timer of neural fiber bundle formation. J. Biol. Chem. 276, 29621-29624.

Wagh, D.A., Rasse, T.M., Asan, E., Hofbauer, A., Schwenkert, I., Durrbeck, H., Buchner, S., Dabauvalle, M.C., Schmidt, M., Qin, G., et al. (2006). Bruchpilot, a protein with homology to ELKS/CAST, is required for structural integrity and function of synaptic active zones in Drosophila. Neuron 49, 833-844.

