Lab 7 — Traditional vs AI Gaussian Filters
Objective

The purpose of this lab was to compare traditional image denoising methods with an AI-based filter for removing Gaussian noise. The goal was to understand how each approach affects image quality in terms of clarity and structure.

Description

A grayscale image (cameraman.tif) was used, and Gaussian noise was added to simulate real-world imperfections.
First, the Wiener filter was applied as a traditional denoising method. It successfully reduced the noise but also made the image slightly blurry and lost some fine details.
Next, the DnCNN model, a pre-trained deep learning filter, was used. It preserved edges and texture much better while removing most of the noise, resulting in a clearer and more natural-looking image.

Results and Discussion

The noisy image had low quality, with visible grain and distortion.
The Wiener filter improved the image smoothness but reduced sharpness.
In contrast, the AI-based DnCNN filter produced the best results, giving higher PSNR and SSIM values and maintaining both detail and structure.

Conclusion

Traditional filters like Wiener are effective for basic denoising, but modern AI-based methods such as DnCNN clearly outperform them by offering cleaner and sharper images.
