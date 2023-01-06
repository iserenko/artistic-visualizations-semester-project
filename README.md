# Computational Augmentation of Dance Videos through Artistic Renderings
This repository contains code for the semester project "Computational Augmentation of Dance Videos through Artistic Renderings" done by Irina Serenko at eM+ lab, EPFL in 2022.

Structure of the repository:

- `Lausanne_Prix_final_code.ipynb` is the notebook containing code to generate 3 implemented types of artistic visualizations: white skeleton with black background and a few inpainted previous frames, movement inpainting in the original video, and movement inpainting with black background;

- `oneEuro.py` is the helper file with a function to apply the low-pass OneEuro filtering (https://jaantollander.com/post/noise-filtering-using-one-euro-filter/) to the predicted landmark coordinates of the dancer's body;

- `drawing_utils_mine.py` and `drawing_styles_mine.py` are the helper files for creating the final output skeleton video. These files are the modified versions of `drawing_utils.py` and `drawing_styles.py` taken from the MediaPipe model setup (https://github.com/google/mediapipe/tree/master/mediapipe/python/solutions);

- `Additional_notebooks` folder contains notebooks created during the features extraction step of the project: `Optical_Flow_.ipynb` and `Optical_flow_RAFT.ipynb` demostrate 2 different approaches to estimate the optical flow (classical algorithms and machine learning), `MiDaS.ipynb` is an attempt to estimate depth of each frame using MiDaS model (https://pytorch.org/hub/intelisl_midas_v2/)


# Credits:

- https://github.com/google/mediapipe
- https://google.github.io/mediapipe/solutions/pose
- https://jaantollander.com/post/noise-filtering-using-one-euro-filter/
- https://pytorch.org/hub/intelisl_midas_v2/
- https://learnopencv.com/optical-flow-in-opencv/
- https://pytorch.org/vision/main/auto_examples/plot_optical_flow.html?highlight=optical+flow

- https://www.prixdelausanne.org
