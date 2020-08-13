Characters from the signal board image are analysed using image enhancement techniques such as contour extraction, binarization(thresholding), etc.
These identified characters are then passed through the VGG - 19 model trained over the char 74k Dataset to extract and determine the information from the sign board.
This data is later fetched through the newsapi.org API to fetch the conditions at the identifies location.

