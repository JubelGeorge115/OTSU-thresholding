# OTSU-thresholding
<br>
ALSO called OPTIMAL THRESHOLDING  is a binarization technique used in image processing to convert a grayscale image into a binary image. It is named after Nobuyuki Otsu, who developed the method. The technique automatically determines the optimal threshold value to minimize intra-class variance (the variance within the foreground and background).
<br>
<br>

process
<br>
<br>
Histogram Calculation: Compute the histogram of the grayscale image.
<br>
<br>
Probabilities and Means: Calculate the probabilities of each intensity level and the cumulative means.
<br>
<br>
Class Variance Calculation: For each possible threshold, compute the intra-class variance.
<br>
<br>
Optimal Threshold Selection: The threshold that minimizes the intra-class variance is selected as the optimal threshold.
