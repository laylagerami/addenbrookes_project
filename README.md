# addenbrookes_project

when you add a file, or modify a file (on your local machine), to update the github repository

git add file_name

git commit -m "message here"

git push origin master

when you want to copy changes from the repo into your local machine

git pull

## Pharmacophore modelling

### PDGFR-a
Loaded 5grn.pdb into Schrodinger and ran preparation (all default, except I deleted Cl atoms and remove waters with less than 1 H-bonds to non-waters, added missing side chains).

Saved file as 5grn_prepared.pdb.

Tasks -> Develop Pharmacophore Model, create pharmacophore model using -> Receptor-ligand complex
* Method: Auto (E-Pharmacophore)
* Hypothesis name: PDGFRa_hypothesis
* See PDGFRa_pharmacophore_1/2.png


