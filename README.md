lpba40 Mean Cortical Thickness and Surface Area Calculator
==========================================================

This tool uses the cortex labels defined by the lpba40 atlas and CIVET output
files to calculate the mean cortical thickness, and total surface area at 26
regions of interest:
```
tral_middle_frontal_gyrus_inferior_tier
caudal_middle_frontal_gyrus
superior_frontal_gyrus
rostral_middle_frontal_gyrus_superior_tier
inferior_frontal_gyrus
precentral_gyrus
middle_orbitofrontal_gyrus
lateral_orbitofrontal_gyrus
gyrus_rectus
postcentral_gyrus
superior_parietal_gyrus
supramarginal_gyrus
angular_gyrus
precuneus
superior_occipital_gyrus
middle_occipital_gyrus
inferior_occipital_gyrus
cuneus
superior_temporal_gyrus
middle_temporal_gyrus
inferior_temporal_gyrus
parahippocampal_gyrus
lingual_gyrus
fusiform_gyrus
insular_cortex
cingulate_gyrus
```

To run, this script requires a complete CIVET output as well as the lpba40
atlas in minc format, as well as a flipped version named:
```
lpba40_labels_May8-2012_L-Final.mnc
lpba40_labels_May8-2012_L-Final-flip.mnc
```

The lpba40 atlas can be found at http://www.loni.usc.edu/atlases/Atlas_Detail.php?atlas_id=12

To run:
```
$ get-lpba40-CT-SA.pl /path/to/civet/output outputfile.csv
```
