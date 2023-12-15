# Histogram-Equalization-Coin-Images
I'm trying to enhance the gray-scale contrast of two images "coin on white background" using Histogram Equalization "HE" and Contrast Limited Adaptive Histogram Equalization "CLAHE"


### Problem

- Applying histogram equalization to improve the quality of two images.
- The two images have high contrast due to the differences between the gray intensities in the coin part and the white background.

### Solution

I have applied two algorithms which are:

1. **Histogram Equalization (HE)** - _Low Contrast Approach_
   First, I have tried Histogram Equalization on the two images and its problem was that it is effective when the image has low contrast and the pixel intensities are clustered in a narrow range.
   
1. **Contrast Limited Adaptive Histogram Equalization (CLAHE)** - _High Contrast Approach_
   Second, I have tried the “CLAHE” algorithm due to its power with images including high contrasts. It is particularly useful in images where there are significant local variations in contrast. Unlike HE, CLAHE operates on small regions of the image rather than the entire image.

### Results
1. **Histogram Equalization (HE)**
   
1. **Contrast Limited Adaptive Histogram Equalization (CLAHE)**


### Conclusion

After applying the two algorithms - "Histogram Equalization (HE)" and "Contrast Limited Adaptive Histogram Equalization (CLAHE)" - on the two images, it is clear that (CLAHE) gets us better results than (HE) due to the high contrast between the grayscale intensities such as the coin itself and the white background.
