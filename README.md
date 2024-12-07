# Homo sapien Malate dehydrogenase 2

# Uniprot ID: P40926
# Variation: Mimic variant and PTM at site 203 



## Description 
ASP 203 of Human MDH2 was identified as the post-transitionally modified site using AlphaFold software to determine the impact of it's structure and function. TPO 203 was my phosphorylated site in MDH2. No previous research has been done at this modification site. 



# Comparison of MDH2 models to mimic variant and PTM

1. Alignment of MDH2, unmodified (yellow and green), modified (purple and blue), and variant (gray and tan).
   
![image](https://github.com/user-attachments/assets/5e3a05eb-392c-4fde-a27f-a3c95fa80a60)




2.  Modification site alignment within MDH2

![image](https://github.com/user-attachments/assets/f9c28447-ba13-4c36-b14d-aa372e853571)

TPO 203, ASP 203, and THR 203 are the modification sites. TPO 203 interacts with LEU 199 and GLN 207. The unmodifed has the same interactions at the modification site. The variant has no interactions.

## Effect of the sequence variant and PTM on MDH dynamics

The RMSD of the final frame from MD simulations of MDH2 was 1.49 Å. The unmodified MDH2 is shown in green and yellow while the modified variant is shown in brown and gray. 
![image](https://github.com/user-attachments/assets/fb47edee-c849-4b27-9fd2-35406f9e7241)



After simulation, the overall protein structures are similar as well as the area surrounding the modification sites. The phosphorylation allows for two hydrogen bond connections. Whereas the variant does not have any hydrogen bond interactions but instead a cation-π interaction present between HIS 176 and ARG 86 that is not seen in the other two structures. 


![image](https://github.com/user-attachments/assets/7201166d-2309-4d06-b6f5-2e287ee66bf8)


### Comparison of the enzyme dynamics
After simulation, the dynamics as described by the root mean square fluctuation (RMSF) value were compared. In the plot, there are differences between the mimic variant (dark blue) and the unmodified (orange). There are distinctions at amino sites 90, 400 and 570. These loop sites correspond to the changes made by the modification to the active site. 

![image](https://github.com/user-attachments/assets/bce2c371-b14e-4d85-96cc-7a19d85457a4)


The loops sites are shown below in dark green with stick representations. The upper grouping is the active site loop. The yellow ellipse shows the distance between the binding and active site. 

![image](https://github.com/user-attachments/assets/49c8cc9c-689a-4113-b2ec-4176cbc510a6)




### Effect of modification on the pKa values

The modification did not have a large affect on the PKa values of the active site. There are very small differnces with almost no change. 
![image](https://github.com/user-attachments/assets/e9d07273-abdb-4a7e-bc2f-01b966140835)


## Comparison of the mimic and the authentic PTM
The RMSD MDHS177D and phosphoS177 MDH1 was 1.7 Å. The overall structures are very similar with only minor differences in structure or position.

![image](https://github.com/user-attachments/assets/11519e04-7d30-440f-956d-1db3ff3ff63c)

## Colab Notebook Links

Copy of mdanalysis_colab_Step1.ipynb
Copy of mdanalysis_colab_Step2.ipynb

## Authors

Jacob Ullman

## Deposition Date
12/7/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

## References
Uniprot. https://www.uniprot.org/uniprotkb/P40926/entry#disease_variants. Accessed December 5, 2024.
