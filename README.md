# AVFR-Gan: Audio-Visual Face Reenactment 
Official github repo for Audio Visual Facial Reenactment (WACV 2023). We will be releasing the code shortly. Stay tuned!

# Introduction
This work proposes a novel method to generate realistic talking head videos using audio and visual streams. We animate a source image by transferring head motion from a driving video using a dense motion field generated using learnable keypoints. We improve the quality of lip sync using audio as an additional input, helping the network to attend to the mouth region. We use additional priors using face segmentation and face mesh to improve the structure of the reconstructed faces. Finally, we improve the visual quality of the generations by incorporating a carefully designed identity-aware generator module. The identityaware generator takes the source image and the warped motion features as input to generate a high-quality output with fine-grained details. Our method produces state-of-the-art results and generalizes well to unseen faces, languages, and voices.  

# Release Notes
Aug 16, 2022: Our paper has been accepted to Winter Conference on Applications of Computer Vision (WACV), 2023.


## Contact
AVFR-Gan was developed by [Madhav Agarwal](https://www.github.com/mdv3101), [Rudrabha Mukhopadhyay](https://rudrabha.github.io/), [Dr. Vinay P. Namboodiri](https://vinaypn.github.io/) and [Dr. C.V. Jawahar](https://faculty.iiit.ac.in/~jawahar/). <br>
For any query, feel free to drop a mail to [Madhav Agarwal](mailto:madhav.agarwal@research.iiit.ac.in) by explicitly mentioning 'AVFR-Gan' in the subject.
