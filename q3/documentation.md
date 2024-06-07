# Question 3 Documentation

## PyTorch section

In this section we selected 5 random images from the COTS dataset. Then using the PyTorch transforms.functions module we implemented 2 different versions of the following data augmentation techniques:

- flipping
- saturation
- brightness

Finally we saved the augmented images to an output folder that could be zipped at a later stage for submission. The function used for saving the images was generated using chat-gpt4, aswell as the list comprehension used to get all the images as a list.

## TensorFlow section

In this section, we selected 5 random images, same images from the PyTorch section, from the COTS dataset. Then, using the TensorFlow 'ImageDataGenerator' class, we implemented the following data augmentation techniques:

- Flipping
- Saturation
- Brightness
- Rotation
- Width Shift
- Height Shift

For each image we generated 6 augmented versions. Finally we saved the augmented images into a folder called 'tensorflow_assignment_images'.
The function to perform the width and height shift was generated using Chat-GPT 4o.