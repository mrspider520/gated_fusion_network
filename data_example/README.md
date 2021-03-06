### Dataset Description

1. This dataset includes image features, layout features, text features, and target labels.
2. The image features are 4-dimensional vectors, in which the elements include the number of zero-face images, the number of one-face images, the number of multiple-face images, and the total number of images.
3. The layout features are 300-dimensional vectors, in which every element calculates the total number  of a HTML leaf tag.
4. The textual content features are 400-dimensional vectors. Every vector is a padded/truncated word sequence from a textual content.
5. Due to the large size of the generated samples in our experiment dataset, which is up to 28 gigabytes, we added two small corpus of fake samples (in 'generated_data*') generated by GAN and MGAN, respectively, to help users to fast grasp the utilization of generated samples.
6. **NOTE:** Due to GitHub’s limitations of uploading large files, we have submitted the part of our dataset. If you need more data, please contact us.