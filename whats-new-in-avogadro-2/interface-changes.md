# Interface Changes

Many parts of the interface have changed in Avogadro 2, particularly menu items. We have tried to separate out commands into groupings.

{% hint style="info" %}
One noticeable change for many users is the split between File => Save and File => Export => Molecule. In Avogadro 1, some users were surprised when saving files to formats which did not retain all information (e.g., bonds are not stored in .xyz files).

In Avogadro 2, File => Save encourages use of **CJSON** files, which are designed to store all information, including bonding, properties, custom colors, etc.

If you wish to export to other formats, use File => Export => Molecule… but not all formats support perfect representations of your molecular data.
{% endhint %}

### Menu Bar

* **File Menu** - commands for opening, importing, saving and exporting files
* **Edit Menu** - undo/redo, copy and paste, including copy graphics, SMILES, and InChI
* **View Menu** - this includes commands to center / focus the view, change perspective, rendering options, and coloring atoms and residues
* **Build Menu** - this includes commands to insert molecules, fragments, adjust hydrogen atoms and bonding, and add centroids from selections
* **Select Menu** - this includes commands for selecting atoms and interacting with selections (e.g., enlarging / shrinking selections, creating layers, etc.)
* **Analysis Menu** - this includes commands for viewing properties of the molecule, atoms, bonds, angles, torsions, as well as vibrations, molecular surfaces, orbitals, etc.
* **Crystal Menu** - this includes commands for unit cells, including perceiving space groups, filling the unit cell with symmetry-defined atoms, editing lattice parameters, etc.
* **Extensions Menu** - this includes integrations with other packages, such as Open Babel, RDKit, as well as for optimizing geometries.
* **Input Menu** - this includes tools to generate input for a wide variety of computational chemistry programs. Many of these use Python scripts, so if your Input Menu is short, either install Python on your system or go to Extensions => Set Python Path… to configure it.
