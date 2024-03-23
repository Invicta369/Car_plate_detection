# Car_plate_detection

This model is trained on over 9k images of number plates using Pytorch's sequential CNN model that traines on over 757,000 parameters

Download the model and save it in a folder.

Download the dataset from my roboflow page abd save it in the folder as well

Download the "indian_license_plate" cascader

Download the model_test.ipynb file to test the model on your selected images

Please note: - The model is not very accurate in drawind the bounding box and even segmenting the plate from car

Due to this low accuracy, please try to input clear images of car with number plate

The reason for this low accuracy is the lack of a better cascader, which happens to be an important tool to identify and bound license plate from an entire image that may contain noise.

If only number plates are supplied to the model then it will predict the text with much more accuracy.

![Cars9](https://github.com/Invicta369/Car_plate_detection/assets/91005649/a59d8442-cfe6-46ae-ae09-4f007a955a09)


Like the one shown above

# Future Updates

I will be adding a basic webpage for a more interact experience for usesrs to test my model.
