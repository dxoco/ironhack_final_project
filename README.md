# ironhack_final_project

Final project for the Ironhack Data analytics class of August-October 2020

Project: Image detection, segmentation and classification using neural networks
Specifics: Plate number recogition and classification (Letters [A-Z] and numbers [0-9])

Input: any photo of a car where the license plate is visible
Output: list of the components associated with their individual images, i.e.:
	  "N"	  "U"	  "C"	  "6"	  "1"	  "0"	  "9"	<--- List of np.alpha characters

	img_1	img_2	img_3	img_4	img_5	img_6	img_7	<--- Each character of the plate


General Code Components:
WPOD model that detects and segments a license plate in any photo.
TensorFlow model that classifies individual numbers and letters.
Final output: classified images

Inspiring Sources:
analitics_vidhya
medium
tensorflow
sentdex
