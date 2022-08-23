# Major New Features

### Speed and Stability

A major concern with Avogadro 1.x was speed on larger systems including biomolecules (protein, DNA/RNA) and materials.

We also know that Avogadro 1.x would crash for multiple reasons - not least because we used older rendering code which was not well supported by modern graphics cards and drivers.

Avogadro 2.0 has been rewritten from the ground up.

### Rendering

Avogadro's new rendering framework easily handles tens and hundreds of thousands of atoms – not just because hardware has improved but by using new 3D graphics rendering methods.

![COVID spike protein 6vxx \~25k atoms with real-time shadows and lighting](<../.gitbook/assets/Covid Spike (1).png>)

New real-time shadows and depth effects

New "close contact" rendering

New non-bonded rendering analysis, including hydrogen bonds, halogen bonds, and chalcogen bonds

New cartoon / ribbon styles for proteins

### Layers

A major new feature in Avogadro 2 is the layer system. You can create new layers for a wide variety of tasks:

* hide part of the molecule (e.g., put solvent fragments into one layer and hide it during analysis or editing)
* change rendering options (e.g., display a protein with cartoon, but show a few key residues with ball-and-stick rendering)
* lock a layer to prevent editing (e.g., moving a molecule to bind with a locked surface or protein active site)

A new section on the Layer doc and tutorials on using layers for common tasks is available.

Future development will help use layers for complex simulations (e.g., QM/MM with one layer defining the quantum chemical fragments).

### Symmetry Properties

Avogadro 2 includes a new tool to perceive molecular symmetry, display symmetry elements, and explore subgroups and classes of symmetric atoms.

![Screenshot of symmetry detection (Ih) and rendering of symmetry elements on a C60 molecule](../.gitbook/assets/Symmetry.png)

### Python Commands / Plugins

With Avogadro 2, it's easier than ever to create a quick Python script and add it as an Avogadro command. These scripts can modify the molecule / atoms (e.g., add a solvent box), run analysis (e.g., assign R and S stereochemical labels with `rdkit`), optimize the geometry, create nanoparticles or nanotubes using installed Python modules (e.g., `pymatgen` or `ASE`), and many more.

You can also share your plugins through GitHub and others can download and instal or update to new versions through the "Download Extensions" command.

