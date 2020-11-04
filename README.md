# GRINjector

<!-- ![image](https://user-images.githubusercontent.com/5241605/97932336-945bbb80-1d24-11eb-9098-b09245b89beb.png) -->
![image](https://user-images.githubusercontent.com/5241605/98111332-4a262780-1e55-11eb-887c-673c79a5a353.png)

![GitHub license](https://img.shields.io/github/license/bahanonu/GRINjector?style=flat-square&logo=appveyor)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bahanonu/GRINjector?style=flat-square&logo=appveyor)](https://github.com/bahanonu/GRINjector/releases/latest?style=flat-square&logo=appveyor)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://github.com/bahanonu/GRINjector/graphs/commit-activity?style=flat-square&logo=appveyor)

__GRINjector__ is a device for injecting GRIN lens probes into animals. The advantages are: 
1. The injection needle displaces brain tissue, improving targetting and minimizing tissue compression.
2. The GRIN is held in place during retraction of the placement needle from the GRIN and the GRINJector device.
3. The guide needle can be easily swapped for other guide needles depending on the diameter and length of the GRIN lens probe.

This repository contains CAD files for printing GRINjector version 3.0 components and assembling them into a usable GRINjector.

Questions? Contact: Biafra Ahanonu (bahanonu [at] alum [dot] mit [dot] edu).

## Components

The below figure illustrates several of the main components:

![image](https://user-images.githubusercontent.com/5241605/98120455-d12dcc80-1e62-11eb-9ba5-fa244f60ac75.png)

Below is a list of components needed to assemble a GRINjector:
* Vernier micrometer. SM-13. Newport.
* Bearing stage. 9066-COM. Newport.
* 4x lock screws that come with 9066-COM.
* Model 1770, Kopf Instruments. For attaching GRINjector to stereotaxic arm.
* GRINjector bottom connector (`grinjector_bottom_connector`)
* GRINjector main needle connector top (`grinjector_mainneedle_connector_top`)
* GRINjector main needle connector bottom (`grinjector_mainneedle_connector_bottom`)
* Stereotaxic holder attachment (`stereotaxic_holder_attachment`)
* 2x - 8-32 x 1'' cap screw.
* 1x - 4-40 x 3/16'' cap screw.
* 1x - 4-40 x 1/4'' cap screw.
* 4x - 4-40 x 5/16'' cap screw.
* Luer lock needle matched to the size of the GRIN lens probe.
* 0.5-mm diameter needle that is ~80-mm long.

## Printing

The main parts are provided as STEP and STL files to allow printing on nearly all commonly used 3D printers (Straysys, uPrint, ). We recommend printing with a high-resolution printer to ensure optimal fit and one with easy to remove support material—we have used VeroBlackPlus on a Stratasys Objet30 and found that to work quite well.

## Assembly

Below are step-by-step by step instructions for assembling the GRINjector after building the necessary parts.

1. Connect the SM-13 and 9066-COM to form a functional setup. Remove the locking plate from 9066-COM as below (see https://www.newport.com/medias/sys_master/images/images/he5/h5b/9366526427166/906806B-9066-9067-User-Manual.pdf).

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/97954746-3a291d80-1d59-11eb-84a5-520f62bd6339.png" width="90%"></p>

2. Using 8-32 cap screws, connect the `Stereotaxic holder attachment` to the back of the 9066-COM, connecting to the top-most holes near the micrometer.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98111550-9bceb200-1e55-11eb-8d65-08629b0a189f.png" width="30%"></p>

3. Next, pull down the bearing stage so that the two 4-40 holes in the back are exposed, place 4-40 x 5/16'' cap screws in each hole.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98112684-64f99b80-1e57-11eb-8d2b-5b6605a19908.png" width="30%"></p>

4. Tap the `grinjector_mainneedle_connector_bottom` holes with a 4-40 tap then place it onto `9066-COM` as below and screw in the 4-40 x 5/16'' cap screws (red below).

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98113833-0f25f300-1e59-11eb-8dc2-21cbd99d3b28.png" width="30%"></p>

5. Align the `lock screws` that comes with `9066-COM` to each of the four holes on each side of the `grinjector_bottom_connector`.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98114951-e0108100-1e5a-11eb-87b9-db21052ec571.png" width="70%"></p>

6. Next, place a blunt or syringe tip `Luer needle` that matches the size of your GRIN lens probe into the groove of the `grinjector_mainneedle_connector_bottom` piece then place the `grinjector_mainneedle_connector_top` piece on top. Screw the `grinjector_mainneedle_connector_top` in place with 4-40 x 5/16'' cap screws then secure the Luer needle with a 4-40 x 1/4'' cap screw.

  * Syringe tip Luer needle allows easier parting of the underlying tissue as the GRINjector is lowered into the brain or spinal cord tissue.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98116044-92951380-1e5c-11eb-823e-143962dddfa5.png" width="40%"></p>

7. Next, obtain a long, `0.5-mm diameter needle` and thread through the small opening at the top of `grinjector_bottom_connector`. The needle will then go through the Luer needle. Lock the needle in place with a 4-40 x 3/16'' cap screw.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98115791-3c27d500-1e5c-11eb-88a2-a93a26b4b4f6.png" width="30%"></p>

8. Lastly, verify that the chosen Luer needle fits the GRIN lens probe tightly and that you can push the GRIN lens probe out of the Luer needle smoothly by twisting the SM-13 micrometer.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98116361-0505f380-1e5d-11eb-9d98-f1d25e4e50c8.png" width="60%"></p>

You are now done assembled the GRINjector! Happy imaging.

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98117424-93c74000-1e5e-11eb-941a-dd73a9046b34.png" width="40%"></p>

To use the GRINjector in an animal:
* Attach the GRINjector onto a stereotaxic arm then perform your normal GRIN lens probe crainotomy surgery.
* Lower the GRIN into the brain using the GRINjector (below diagram, left). 
* After placement at desired coordinates in tissue, raise the blunt tip needle by twisting the micrometer until the needle is clear of the GRIN lens probe. The red needle secures the GRIN in place during retraction of the device.
* Secure the GRIN in place with dental cement, UV glue, or your adhesive of choice then after it as set, slowly raise the GRINjector using the stereotaxic arm. 
* If your stereotaxic arm allows angles, the GRINjector can be used to target the same site at different angles to avoid vasculature or vital brain regions (below diagram, right).

<p align="center"><img src="https://user-images.githubusercontent.com/5241605/98118465-1a305180-1e60-11eb-9ea6-34a963d214c3.png" width="100%"></p>

## Acknowledgements

I would like to thank [Prof. Benjamin Grewe](https://www.ini.uzh.ch/en/institute/people?uname=bgrewe) for helping inspire and provide feedback on the initial GRINjector design.

## References

We have a book chapter pending describing this device. In the meantime, please cite our [Corder*, Ahanonu*, et al. 2019](http://science.sciencemag.org/content/363/6424/276.full) _Science_ publication if you used this device in your research:

```Latex
@article{corderahanonu2019amygdalar,
  title={An amygdalar neural ensemble that encodes the unpleasantness of pain},
  author={Corder, Gregory and Ahanonu, Biafra and Grewe, Benjamin F and Wang, Dong and Schnitzer, Mark J and Scherrer, Gr{\'e}gory},
  journal={Science},
  volume={363},
  number={6424},
  pages={276--281},
  year={2019},
  publisher={American Association for the Advancement of Science}
}
```

## License

Copyright (C) 2015-2020 Biafra Ahanonu

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

## Repository stats
- ![Hits](https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2Fbahanonu%2FGRINjector) (starting 2020.11.02)
- ![visitors](https://visitor-badge.glitch.me/badge?page_id=bahanonu.GRINjector) (starting 2020.11.02)