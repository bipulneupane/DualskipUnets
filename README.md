# DualskipUnets
This is the repo to collect and prepare multi-resolution MELB data proposed in the paper entitled "Dual skip connections in U-Net, ResUnet and U-Net3+ for remote extraction of buildings". The paper is archived at: https://arxiv.org/abs/2303.09064

Please use the Jupyter notebook "Data_gather_from_NearmapTileAPI" to download the datasets. You need a Nearmap Tile API key to access the images from Nearmap. Please visit their website for the details and documentation.

Building samples of the City of Melbourne is available in the CityPolygon folder, which is openly available at https://data.melbourne.vic.gov.au/explore/dataset/2020-building-footprints/information/

The paper is currently under review in a well-reputed journal. The codes for the DS-Unet, DS-ResUnet, and DS-Unet3+ will be available in this repo after the paper is published.

If you use the codes from the repo, we appreciate your citation to the paper as:

```json
@misc{neupane2023rethinking,
      title={Dual skip connections in U-Net, ResUnet and U-Net3+ for remote extraction of buildings}, 
      author={Bipul Neupane and Jagannath Aryal and Abbas Rajabifard},
      year={2023},
      eprint={2303.09064},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
Acknowledgement:
The authors would like to thank Nearmap for providing the API service to collect the image data for the experiments.
