#MEL Scripts

A collection of legacy MEL scripts for Maya done between 2002-2006 by **Edvard Toth** (http://edvardtoth.com)

Apart from my confidential, proprietary game-development scripting work I also created a number of freely available, more generic scripts which in their heyday managed to accumulate well over 80.000 total combined downloads. I even received the honor of being included in Pixel Magazine’s "World’s Best Maya Developers" feature.

Please note that even though the scripts **are not supported or updated anymore**, they may still prove to be useful. Please always refer to the script-headers for more thorough documentation.

Contents
----------

* **curveTube [V1.11 01/2006]** The script offers a way of rapidly creating extruded/lofted tubular geometry with precisely controllable width at every cross-section using only two slightly offset curves of identical CV-counts.

* **uniToolBox [V2.0 01/2006]** The script creates a Swiss Army-knife style unified, dockable interface featuring contols grouped in collapsible frames for a number of functions and operations. It includes a comprehensive collection of display-property controls, selection conversion, UV-mapping, prelighting and layer-commands. Useful for having all these frequently used functions in one customizable place without sacrificing precious hotkeys on them. V2.0 adds color-coded tabs, saved tab-states, numerous small fixes, a “Shading” tab and a customizable “User” tab.

* **batchProcessor [V1.0 01/2005]** The script is a highly versatile batch-processing utility which offers a way to apply virtually any single MEL-command, code-snippet or standalone script to entire directories of Maya-files. It provides comprehensive options to control how the files are identified, opened and saved, and it generates a detailed log to help track down any potential processing-interruptions due to command errors or other problems. It is very useful for performing repetitive tasks on a large number of individual files. Please refer to the ‘About’-panel for more detailed information.

* **curveLength [V1.0 08/2004]** This tiny but very straightforward utility measures the length of a curve without all the hassle that comes with using Maya’s implementation of the “Arc Length Tool”.

* **reSource [V1.0 07/2004]** The script is a very handy script-development utility: it allows you to repeatedly source and execute a script-file with a click of a button, greatly simplifying the testing-process. Both the filename (including the full path) and the command-name (including any potential parameters) can be specified either manually or through a browser-window. In addition, these settings are stored as persistent variables and don’t have to be re-entered, even if Maya is restarted.

* **ParentToParticles [V3.0 07/2004]** The script offers a potential way to rapidly and precisely place and adjust a large number of objects using particles as placement-proxies. (It’s particularly useful for tasks like placing rocks or plant-life on uneven terrain without excessive manual tweaking.) V3.0 represents a major overhaul: significantly updated interface and button-set with direct access to supporting Maya-tools, ability to place objects and constrain them to a target-surface in one quick pass, faster operation, more extensive error-checking, etc.

* **pointDistance [V2.1 03/2004]** The script creates a persistent and dynamically updated HeadsUpDisplay-overlay that displays the direct distance between 2 selected points. Only point-like entities (vertices, CVs, curve-points, particles, lights, etc.) are evaluated, all other types within the selection are ignored. Distance-information is shown only if exactly 2 items are selected, otherwise the display resets to “0”. The script can be an extremely useful tool for modeling game-environments, where using certain specific distances is usually a key factor required by gameplay.

* **distributeOnCurve [V2.0 03/2004]** The script makes it possible to create a number of duplicates/instances of a specified object, and distribute them along a curve. The distribution can also be randomized, and the orientation of the selected objects can be constrained to follow the tangency of the curve (For example, this could be useful for properly orienting wooden planks in a winding walkway.) New in V2.0: option to duplicate/instance, now all objects are generated from a single original template, better control of constraints.

* **massPointLights [V1.0 01/2004]** The script creates a customizable pointLight at the origins of any number of selected objects, and each pointLight is generated with an adjustable intensity-curve to control its falloff. The script offers a workaround to the problem of losing the intensity-curve when duplicating/instancing lights of this type, and provides an effective method of placing a large number of these lights at specific positions within a scene (especially when used together with locators to define the placement).

* **pivotMatcher [V1.0 12/2003]** The script makes it possible to match the pivots of any number of selected objects to either the pivots of the same number of target objects, or to the pivot of one selected target object.The selection-order is taken into account during the process.

* **vertexTone [V2.1 12/2003]** The script is a comprehensive global adjustment utility for vertex-color / vertex-alpha values. It performs brightness, contrast, dodge/burn and saturation operations on the colors of selected vertices and features controls to independently modify each RGB-channel. Now it works on pre-defined / sampled vertex-selections to allow fine-tuning, it also works across multiple objects and takes advantage of the functionality offered by Maya’s built-in color editor / color picker tool.

* **randomComps [V1.0 10/2003]** The script makes it possible to randomly select a certain percentage of components (vertices, faces, edges and UVs) on selected objects. Its area of effect can also be limited/tuned even further by using it on an existing component-level selection.

* **groupN [V1.0 10/2003]** The script creates a small pop-up window that contains grouping-preferences and a text-field that makes it possible to properly name new groups in advance: this removes the extra step of having to rename them after the grouping is performed. Provides an useful alternative to the default “group” (CTRL+G) command.

* **proxyUV [V1.0 09/2003]** The script uses a “proxy” NURBS-surface to project UV-coordinates onto a polygonal mesh: it offers a simple and very effective approach to texturing complex polygonal meshes, greatly reducing problems associated with overlapping and uneven, severely stretched UVs. (Even though several other scripts out there utilize a similar method, I believe this version is a simplified and highly streamlined implementation of this technique.)

* **vertexNoise [V1.0 12/2002]** The script applies fully adjustable random noise to selected vertices, even across multiple objects. The type of the noise can either be uniform (based on the vertex-normals) or directional (based on the XYZ-axes). A smoothing function with adjustable intensity is also available for fine-tuning purposes. Since the original vertex-selection is retained, the noise/smooth operations can be applied repeatedly until the desired result is reached.

* **vertexLevels [V1.0 09/2003]** The script selects vertices based on their vertex colors, also taking an adjustable selection-threshold value into account. The selection works on entire scenes, across multiple objects. The resulting set of selected vertices can be adjusted using separate basic RGB-controls. Potential uses could include selecting and brightening up dark areas in a level without having to prelight the entire scene and possibly lose manual vertex-color tweaks.)

* **massReplicate [V2.1 01/2003]** The script creates an interface to mass-duplicate/instance a specified object, and provides randomizable rotation / scaling on all axes for the object-iterations. V2.1 now has a completely redesigned and optimized interface, and adds the option of either randomly scattering the duplicates/instances in an area or placing them at regular intervals using XYZ offsets, plus minor bug-fixes.

* **massConstrain [V1.1 12/2002]** The script constrains any number of selected objects to the normals and/or geometry of a specified target surface. It also leaves behind the normal/geometry constraint nodes on each individual selected object so they can be manually adjusted while they maintain their alignment (they “stick”) to the normals and/or geometry of the target surface. Hint: useful for tasks such as properly orienting / arranging a large number of leaves to tree-branches. Works well together with the ParentToParticles and massReplicate scripts.

* **massUVTransfer [V1.0 06/2003]** The script transfers the UV coordinates of a specified object to any number of other objects of identical topology in one pass, eliminating the need to select individual object-pairs for the transfer.
massRename [V1.2 02/2003] The script provides a very easy-to-use solution for renaming a large number of nodes. It features adjustable starting-number and padding for the renamed nodes, two options for a divider character that separates the new node-name from the node-number and a reorder-function that sorts the nodes into ascending order. The script – unlike other renamers – keeps working even when nodes from multiple levels of the node-hierarchy are selected at the same time.

* **displayTexture [V1.0 01/2003]** The script makes it possible to view the bitmap-texture assigned to a selected polygonal face with a single click, using any external image-viewer that accepts command-line input (fcheck, ACDSee, IrfanView etc.) The location of the image-viewer application has to be specified in the “DT_viewer” variable. The script also shows the name and full path of the viewed texture-file in the “Command Feedback” line at the bottom of the screen, and provides additional details about the texture in the “Script Editor” window.

* **offsetCV [V2.0 12/2002]** The script places/spreads the CVs of a curve evenly along the Y axis. The placement of CVs can be determined by the offset (the Y-distance between each CV) or the span(the total Y-distance between the first and last CV of the curve). The starting Y-position for the first CV can also be specified. All values handled as negative/positive floating values with 4-digit precision. Hint: useful for creating accurate roller-coaster or slide-like surfaces.

* **averageCurves [V2.0 07/2003]** The script generates an averaged, intermediary curve between two selected curves. Particularly useful for terrain or water-surface modeling since it’s adding new cross-section curves for lofting / bi-railing surfaces.

* **supportCurves [V1.0 12/2002]** The script creates a new curve that is offset in XZ-space, but its CVs inherit their Y-axis position from the CVs of the original curve. It was created to provide a workaround to the problem of tilting/banking of slide/ribbon-like extruded surfaces. Using the script to create offset support-curves it becomes very easy to generate (loft or birail) surfaces that maintain horizontal planarity at every subdivision. Works well together with the offsetCV script.

* **sceneCleanUp [V1.1 07/2003]** The script deletes numerous leftover nodes (links, brush-nodes, script-nodes, unconnected intermediate objects etc.) normally unaffected by deleting history or optimizing the scene. It also eliminates excess “stacked” vertex-color data. While individual results will vary depending on application, in many cases the script can drastically reduce the size of large scenes. (This script is the result of a joint effort with Alex Carbonero.)

* **alphaSlider [V1.0 12/2002]** A very simple script that creates a slider to interactively adjust vertex-alpha values. The changes are instantly visible if the slider is dragged. The script automatically converts existing selections into Vertices, providing additional versatility. (See script-header for more details.)
