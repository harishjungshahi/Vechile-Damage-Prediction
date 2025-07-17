# Vehicle Damage Detection App

This app lets you drag and drop an image of a car and it will tell you what kind of damage it has.
The model is trained on third quarter front and rear views, so the picture should ideally capture either the third quarter front or rear view of a car.

![app](app_screenshot.jpg)

### Model Details
1. Used ResNet50 for transfer learning  
2. Model was trained on around 1700 images with 6 target classes:
   - Front Normal  
   - Front Crushed  
   - Front Breakage  
   - Rear Normal  
   - Rear Crushed  
   - Rear Breakage  
3. The accuracy on the validation set was around 80%

### Set Up

1. To get started, first install the dependencies using:
   ```bash
   pip install -r requirements.txt
