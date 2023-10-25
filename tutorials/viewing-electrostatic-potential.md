# Viewing Electrostatic Potential Maps

The electrostatic potential maps help to visualize charge distribution, and other charge related properties of molecules.

Overall, let's say you want to determine visually if a specific proton has more or less electron density. First, you'll want to begin with your molecule of choice (shown below is trifluoracetic acid).

![File => Import => Download by Name... trifluoroacetic acid](<../.gitbook/assets/trifluoroacetic acid.png>)

Then under the "Analysis" menu, select "Create Surfaces...".

![Analysis => Create Surfaces...](broken-reference)

A dialog box will pop up providing you with various surface options. Under "Color By:" select "Electrostatic Potential", and optionally the electrostatic model (e.g., EEM or Gasteiger or MMFF94). You can also select a colormap (e.g., Balance, Coolwarm, Spectral, Turbo). Then click "Calculate". After Avogadro calculates the surface select "Close".

![Create Surfaces - Color by Electrostatic Potential: Several electrostatics models are listed, including EEM, Gasteiger, MMFF94, etc.](../.gitbook/assets/CreateSurfacesDialog.png)

An electrostatic surface has now been created. From this surface, you can interpret where the most electron density resides (in the more red areas), and where the least electron density resides (deep blue areas). You can further determine, and compare the acidity of various protons, and how surrounding atoms impact the overall electron density.

![Red = more negative charge (e.g, fluorine and oxygen atoms) Blue = more positive (i.e., acidic proton)](../.gitbook/assets/ElectrostaticMap.png)

This example was taken from "Exploring the Acidity of Organic Molecules with Avogadro" written by Tamika Madison.

## Changing Surface Settings

The opacity of the surface can the be changed by clicking the  "Meshes" display type and tweaking the display to your liking.

![Meshes display options](../.gitbook/assets/Meshes.png)

