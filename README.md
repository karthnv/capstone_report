- this project uses Keras libraries with tensorflow backend.
- OpenCV library is also used to resign, crop, read and write video clips

- There are 6 algorithms in total that have been implemented and analyzed for best accuracy.

- 3 of the 6 algorithms use the datasets in "train_full", "valid_full" and "test_full" folders

- The other 3 algorithms use the datasets in "train_yolo", "valid_yolo" and "test_yolo" folders

- the difference between these datasets is *_yolo contains video clips that have been parsed through YoloV2 algorithm to video clips that contain only the person of interest.


- The files used to convert full video clips to yolo-cropped video clips can be found in the folder full_to_yolo_conversion. Specifically "Yolo-crop-video_conversion.ipynb"


- Algorithms implement using full video clips can be found in full_vid.ipynb jupyter notebook file.
- Algorithms implement using Yolo cropped video clips can be found in yolo_vid.ipynb jupyter notebook file.


- Capstone project proposal is in the file proposal.pdf
- Capstone project report is in the file report.pdf

- Capstine proposal review can be seen in the following link https://review.udacity.com/#!/reviews/943825