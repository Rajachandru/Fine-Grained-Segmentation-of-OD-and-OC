# Fine-Grained-Segmentation-of-OD-and-OC
Fine Grained Segmentation of OD and OC  (along with patch dataset for segmentation)
The patch dataset and the complete code for (i)patch dataset generation  , (ii) fine grained segmentation through a learner reviser CNN is given.
Read the "Code-details_Read_Me" in the attachments for the details of the codes. 

**Patch dataset:**  (patches_60k_1.zip - patches generated from fundus images around the borders; ODPatches60K.zip - patches generated from fundus Labels around the borders)
The Patch dataset is created cropping patches of size 25 Χ 25 from the Fundus Images in DRISHTI- GS dataset. The patches are created around the borders of the Optical Disc (OD) and Optical Cup (OC) where there "expected ambiguity" is maximum. The ambiguous points (in class belongingness as OD or OC) are extracted by EX-OR ing OD and OC labels. The folder named "Expected ambiguities" shows the images with the ambiguous pixels in white. In the Excel file called "Expected ambiguities" we have taken 50,000 ambiguous points (pixels) randomly from all images. The patches of size 25 × 25 is extracted from the original image and OD ground truth for fine grained learning.
Since “Git Hub” is not accommodating the file size, I share the g-drive with the 50,000 patches of size 25 × 25 created in the images and at the same spatial co-ordinates in the OD labels, for fine- grained supervised learning.
