# Sophoappeal
This repository summarizes the work done in the DFG project [Sophoappeal (437543412)](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-elektrotechnik-und-informationstechnik/profil/institute-und-fachgebiete/fachgebiet-audiovisuelle-technik/forschung/dfg-projekt-sophoappeal). 

**important use `git clone --recursive` for the checkout**, and have ssh keys for your git cloning activated.

## Structure

* `images`: all images used in the project

* `aesthetics_srv`: evaluation web service used for lab and crowd tests, for a generic framework checkout [AVRateVoyager](https://github.com/Telecommunication-Telemedia-Assessment/AVrateVoyager)

* models for appeal prediction:
    * `appeal_prediction_dnn_transferlearning`
    * `appeal_prediction_models`
* features:
    * `dnn_features`
    * `image_features_tool`
* extracted maps for images:
    * `depth_segmentation_maps`
    * `saliency_maps`
* photo rule prediction:
    * `rule_prediction`
* subjective lab and crowd tests:
    * `evaluation_image_appeal_test_1`
    * `evaluation_image_appeal_test_2`

* `additional`: follow up work, such as appeal of AI generated images, and [AVRateVoyager](https://github.com/Telecommunication-Telemedia-Assessment/AVrateVoyager)


## Requirements

The provided software is tested under Ubuntu 20.04 and 22.04.

* python3, python3-pip

The subfolders have dedicated Readme.md files with instructions.

## Acknowledgments

If you use this software or data in your research, please include a link to the repository and reference the following paper.

```bibtex
@article{goering2023imageappeal,
  title={Image Appeal Revisited: Analysis, new Dataset and Prediction Models},
  author={Steve G\"oring and Alexander Raake},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE},
  note={to appear}
}
```

## License
GNU General Public License v3. See [LICENSE.md](./LICENSE.md) file in this repository.