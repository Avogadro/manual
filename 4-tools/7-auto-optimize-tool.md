# The Auto-Optimize Tool

The Auto Optimize tool continuously optimizes molecular geometry through molecular mechanics. This tool also provides you with the ability to manipulate the molecule while the molecular geometry is being minimized.

![][1]

[1]: images/7-auto-optimize-tool/27bc0d24-9f97-4a7c-9910-437a3543a1a1.png
#### Force Fields & Algorithms
The Auto-Optimization settings provide several force field options. The default force field is UFF or the Universal Force Field. This force field is capable of reproducing the most structural features across the periodic table. However, depending on the molecule being tested, the other force fields may be better suited to optimize the molecular parameters. The force field options are shown below. For more information on force fields refer to the optimizing geometry section of this lab manual.

![][2]

[2]: images/7-auto-optimize-tool/7f322184-8a2b-41cd-9ee6-e307f70c7962.png

The default setting for "Steps per Update" is 4. This number can be preferentially increased or decreased. If you have a slower computer consider decreasing this number.

![][3]

[3]: images/7-auto-optimize-tool/fdee8a39-3c94-467d-8433-95aa5317afdb.png

Avogadro also has the ability to apply specific algorithms dependent on your need. Steepest descent is the default algorithm, and has the most fluid and interactive system.

![][4]

[4]: images/7-auto-optimize-tool/eb1ab87c-4dbf-408d-b14b-4079675aac43.png
#### Fixing & Ignoring Selected Atoms
If necessary, atoms can be fixed into place before optimization so that they don't move. This is done by going to the "Extensions" menu, holding your cursor over "Molecular Mechanics" and then selecting "Fix Selected Atoms". 

![][5]

[5]: images/7-auto-optimize-tool/cb6ce9e3-bea8-4974-b81b-6d5cf29e0cab.png

Clicking on "Start" will allow you to manipulate the molecule by left clicking on an atom and dragging your cursor. Notice that the fixed atoms don't bend with the manipulation of the molecule. Fixed atoms also provide the benefit of rotation during auto-optimization.

![][6]

[6]: images/7-auto-optimize-tool/33a0c439-2c92-4ac2-b2dc-5e09d0db8b40.png

If the "Fixed atoms are movable" box is checked, the bonds between atoms can be manipulated into a new configuration. The new configuration will be just as immobile as the initial atom configuration, and the number of constraints will be displayed on the screen. 

![][7]

[7]: images/7-auto-optimize-tool/bd79e6ec-e7cb-4df3-81dd-7b61b1f5f627.png

Essentially, the same thing takes place if the "Ignored atoms are movable" box is checked. However, ignored atoms (if the box is checked) *will *reoptimize once dragged. To ignore a selection select the "Extensions" drop down menu, hold your cursor over "Molecular Mechanics" option, and select "Ignore Selection". 

The molecule will reoptimize until dE=0 or "Stop" is clicked.

![][8]

[8]: images/7-auto-optimize-tool/ba606487-98a6-4d53-8319-e8a5ea3890b6.png