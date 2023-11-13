![banner](assets/ASA_custom_banner.png)

This repository contains data analysis project related to the ASA 2023 challenge. Most of its content is in Portuguese and can be found in the directory [notebooks](notebooks).

The challenge consist in analyzing data, generating insights and creating a model that is capable of detecting the types  of defect found in steel plates during its production process.

The csv originally has the following features:

- **min_x_defect**: X coordinate, start of defect
- **max_x_ defect**: X coordinate, end of defect
- **min_y_ defect**: Y coordinate, start of defect
- **max_y_ defect**: Y coordinate, end of defect
- **area_pixels**: The total of pixels in the steel plate
- **slab_width**: Slab width
- **slab_length**: Slab length
- **sum_pixel_luminosity**: Sum of all pixels luminosity
- **min_pixel_luminosity**: Minimum value of pixel luminosity
- **max_pixel_luminosity**: Maximum value of pixel luminosity
- **conveyer_width**: Conveyer width (x axis) 
- **type_of_steel**: Type of steel: A300 or A400
- **defect_type**: Type of class:  0 or 1