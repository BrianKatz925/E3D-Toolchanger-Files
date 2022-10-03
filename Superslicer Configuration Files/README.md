# Getting Printer Configuration into SuperSlicer

## Prerequisites

1. Install SuperSlicer using this link: [E3D Toolchanger Slicer Settings](https://e3d-online.zendesk.com/hc/en-us/articles/4402755255825-ToolChanger-Slicer-Settings)

## Instructions

2. Download the attached [configuration bundle](https://github.com/BrianKatz925/E3D-Toolchanger-Files/blob/a7acd65cfd7cc165d1f3e66c989ba941ff94d47c/Superslicer%20Configuration%20Files/SuperSlicer_config_bundle_CA_v1.ini)
3. Import the file into SuperSlicer by going to File -> Import -> Import Config Bundle and select the downloaded bundle.
4. Navigate to the Printer Settings tab and the General subgroup. Select the Bed Shape under Size and Coordinates and click Set.
5. Set the size of the bed to 300 x 200 mm and the origin to (0,0).
6. Apply the [svg file](https://github.com/BrianKatz925/E3D-Toolchanger-Files/blob/a7acd65cfd7cc165d1f3e66c989ba941ff94d47c/Superslicer%20Configuration%20Files/e3d_toolchanger_bed%20(1).svg) to the texture field.
7. Apply the [stl file](https://github.com/BrianKatz925/E3D-Toolchanger-Files/blob/a7acd65cfd7cc165d1f3e66c989ba941ff94d47c/Superslicer%20Configuration%20Files/e3d_toolchanger_bed%20(1).stl) to the model field.
8. Now, you should have a bed that looks like the E3D Toolchanger and a configuration file with four tools loaded.
