# CSC8639_210346785_Dissertation
CSC8639 Dissertation Project
Download Cross Age Celebrity Dataset images from this location:
https://bcsiriuschen.github.io/CARC/

Download Asian Face Age Dataset images from this location:
https://github.com/afad-dataset/tarball
Use shell script restore.sh to restore the orignal file from splitted tarball files.

For doing different types of augmentation for CACD dataset, please run CACD_CORAL.ipnyb
For Training with CACD dataset, run CACD_CORAL.ipynb
Download different best trained models from https://github.com/debr20008/CSC8639_210346785_Dissertation.git/ Model folder.
For Testing lipstick augmented age prediction model with CACD dataset, run CACD_Test.ipnyb with best_model_cacd_lipstick.pt checkpoint file.
For Testing eye color augmented age prediction model with CACD dataset, run CACD_Test.ipnyb with best_model_cacd_eyecolor.pt checkpoint file.
For Testing faceswap augmented age prediction model with CACD dataset, run CACD_Test.ipnyb with best_model_cacd_faceswap.pt checkpoint file.
For Testing sunglass augmented age prediction model with CACD dataset, run CACD_Test.ipnyb with best_model_cacd_sunglass.pt checkpoint file.
For Testing age prediction model with original images of CACD dataset, run CACD_Test.ipnyb with best_model_cacd_org.pt checkpoint file.

For doing different types of augmentation for AFAD dataset, please run AFAD_CORAL.ipnyb
For Training with AFAD dataset, run AFAD_CORAL.ipynb
For Testing age prediction model with original images of AFAD dataset, run AFAD_Test.ipnyb with best_afad_model.pt checkpoint file.
For Testing geometrically augmented age prediction model with AFAD dataset, run AFAD_Test.ipnyb with best_afad_geo_model.pt checkpoint file.
For Testing photometrically augmented age prediction model with AFAD dataset, run AFAD_Test.ipnyb with best_afad_photo_model.pt checkpoint file.


Download the dlib 68-point facial landmark model from this location:
https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat



