# Colorizing Black and White images and videos using (CNN, Deep learning and OpenCV)
### Project Overview:
This project is based on a research work developed at the University of California, Berkeley by Richard Zhang, Phillip Isola, and Alexei A. Efros. Colorful Image Colorization.
Image colorization is the process of taking a grayscale (black and white) image as
input and producing a colorized image that accurately depicts the input's semantic
colors and tones (for example, an ocean on a clear sunny day must be convincingly
"blue" – the model cannot color it "pink").

### Description:
As indicated in the original paper, the authors welcomed the problem's
underlying ambiguity by organizing it as a classification job with class-rebalancing
during training time to increase the diversity of colors in the output. The AI
approach is trained on over a million color photos and used as a feed-forward
pass in a CNN (Convolution Neural Network).

### Methodology:
The system is implemented as a feed-forward pass in a CNN at test time and is
trained on over a million color images. We broke videos into frames and applied
filters according to (L + a + b) approach. We evaluated our algorithm using a
“colorization Turing test” asking human participants to choose between a
generated and ground truth color image. Our method successfully fools humans on
32% of the trials, significantly higher than previous methods. Moreover, we show
that colorization can be a powerful pretext task for self supervised feature learning,
acting as a cross-channel encoder. 
