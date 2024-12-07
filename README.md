# Homo sapien Malate dehydrogenase 2

# Uniprot ID: P40926
# Variation: Mimic variant and PTM at site 203 



## Description 
ASP 203 of Human MDH2 was identified as the post-transitionally modified site using AlphaFold software to determine the impact of it's structure and function. TPO 203 was my phosphorylated site in MDH2. No previous research has been done at this modification site. 



# Comparison of MDH2 models to mimic variant and PTM

1. Alignment of MDH2, unmodified (yellow and green), modified (purple and blue), and variant (gray and tan). 
![image](https://github.com/user-attachments/assets/5e3a05eb-392c-4fde-a27f-a3c95fa80a60)




2. Modification site alignment within MDH2
![image](https://github.com/user-attachments/assets/f9c28447-ba13-4c36-b14d-aa372e853571)

TPO 203, ASP 203, and THR 203 are the modification sites. TPO 203 interacts with LEU 199 and GLN 207. The unmodifed has the same interactions at the modification site. The variant has no interactions.

## Effect of the sequence variant and PTM on MDH dynamics

The RMSD of the final frame from MD simulations of MDH2 was 1.49 Å. The unmodified MDH2 is shown in green and yellow while the modified form is shown in brown and gray. 
![image](https://github.com/user-attachments/assets/fb47edee-c849-4b27-9fd2-35406f9e7241)



After simulation, the overall protein structures are similar as well as the area surrounding the modification sites. A solvent sodium ion has moved close and is forming an ionic interaction with the D in position 177. D177 also is making contact with R174. Neither of these interactions are observed in the unmodified enzyme.


![alt text](images/md_site.png)

### Comparison of the enzyme dynamics
After simulation, the dynamics as described by the root mean square fluctuation (RMSF) value were compared. In the plot, there are differences between the unmodified (purple) and S177D (green) around amino acids 400 and 500. These sites are loops bordering the active site. The difference around residue 400 is the active site loop which is key for binding the carboxylic acid substrate. The vertical line indicates the end of one subunit and the beginning of the next subunit of the MDH1 dimer.

![alt text](images/rmsf_compare.png)

The loops sites are shown below in blue with stick representations. The upper grouping is the active site loop. The yellow ellipse shows the approximate bind sites of the carboxylic acid and NAD+ substrates.

![alt text](images/loop_sites_active.png)


### Effect of modification on the pKa values

Overall the modification did not affect the pKa values of the active site histidine. There are only minor differences in the spread of the data over the simulation which may be due to equilibration. 
![alt text](images/pka_over_traj.png)


## Comparison of the mimic and the authentic PTM
The RMSD MDHS177D and phosphoS177 MDH1 was 0.48 Å. The overall structures are similar with no major differences in structure or position.

![alt text](images/mod_compare.png)

## Authors

Christopher E. Berndsen

## Deposition Date
10/21/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

## References

* Reinders, Jörg, et al. “Profiling Phosphoproteins of Yeast Mitochondria Reveals a Role of Phosphorylation in Assembly of the ATP Synthase.” Molecular & Cellular Proteomics: MCP, vol. 6, no. 11, Nov. 2007, pp. 1896–906. PubMed, https://doi.org/10.1074/mcp.M700098-MCP200.
