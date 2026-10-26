# Task-Conditioned Next-Fixation Prediction in Assembly Tasks

**Maria Tsiourva · Esten Ingar Grøtli · Tor Arne Johansen**  
SINTEF Digital · Norwegian University of Science and Technology

Published in *Advances in Visual Computing* (ISVC 2025), Lecture Notes in Computer Science, volume 16396, pages 322–333, 2026.

This project studies task-driven human gaze during building-block assembly. The proposed model combines first-person scene images, task-relevant object templates, and past fixation heatmaps to predict the next fixation as a probability distribution over the scene.

## Paper

[Read the paper on Springer](https://link.springer.com/chapter/10.1007/978-3-032-14492-8_25)  
DOI: [10.1007/978-3-032-14492-8_25](https://doi.org/10.1007/978-3-032-14492-8_25)

The paper evaluates fixation predictions using saliency metrics, examines the effects of fixation history and center bias, and introduces a task-specific hit-rate measure.

## Code

The research implementation has not yet been publicly released. This repository currently contains the project website only. This section will be updated with access information when the research code is released.

## Data

[Access the LegoFixations dataset on Figshare](https://figshare.com/s/551fd18a1868e388a967?file=57408280).

LegoFixations contains first-person recordings of one participant assembling nine distinct building blocks across multiple runs, with synchronized gaze coordinates, object annotations, and reference template images.

- **5,375 scene images** in the training and validation data.
- **Scene video:** 30 Hz, 1600 × 1200 pixels.
- **Recorded gaze:** 200 Hz, collected using the Pupil Labs Neon eye tracker.
- **Synchronization:** gaze samples matched to scene frames by nearest timestamp.
- **Archive:** `LegoFixations.zip`, approximately 4.17 GB, hosted on Figshare.

See the Figshare record for access and licensing information.

## Citation

```bibtex
@inproceedings{tsiourva2026task,
  author = {Tsiourva, Maria and Grøtli, Esten Ingar and Johansen, Tor Arne},
  title = {Task-Conditioned Next-Fixation Prediction in Assembly Tasks},
  booktitle = {Advances in Visual Computing},
  series = {Lecture Notes in Computer Science},
  volume = {16396},
  pages = {322--333},
  year = {2026},
  publisher = {Springer Nature Switzerland},
  doi = {10.1007/978-3-032-14492-8_25}
}
```

## Acknowledgments

This work was supported by the Research Council of Norway through the project *Attention-driven odometry estimation and Spatial AI* (project number 342619).
