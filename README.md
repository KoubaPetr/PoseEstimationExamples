# PoseEstimationExamples
Repository providing examples of pose estimation frameworks, supplementing the master thesis "Recognition of dance genres from video".

Containing the google colab notebook 'PoseEstimationReport.ipynb' which is an informal review of some of the Pose Estimation framework as of April 2020. The notebook includes examples, produced by some of the frameworks - using google colab installations of the networks from https://github.com/tugstugi/dl-colab-notebooks .

The notebook OpenPoseDatasetProcessing.ipynb can be run in Google colab but the directory structure needs to be accustomed to users Google Drive directory structure.

The folder ExampleVideos contains 10 videos of the 10 different international style dances, with overlaid skeletons as returned by OpenPose BODY_25 format

The video 'chachacha_tracking_normalization.avi' illustrates results of our tracking and normalization procedure - same colored skeletons in consecutive frames mean the tracking matches these two skeletons as belonging to the same person. Grey coloured skeleton means low confidence in tracking and such tracklets are ignored.
