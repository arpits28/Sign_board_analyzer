The project is going to illustrate a new use-case for Character recognition backed up with numerous image enhancement techniques for the pre-processing. So, in this project, an image of a signal board from a normal highway is going to be fed and the following stages are going to be performed sequentially:
1). Extraction of characters from the signal board image using image enhancement techniques such as contour extraction, binarization (thresholding), etc.
2). Determining which characters occur in the same row/line in the board and grouping the character images (contours) in terms of the row to which they belong.
3). Applying a CNN over the character images to determine the character/letter they represent and grouping/concatenating them to determine the name of the places that signal board possesses.
4). Finally, feeding the names of those places to multiple APIs to extract information such as weather data, news data, etc. for those respective places.
