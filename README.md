# Full Vs Flat Cnn With TensorFlow

## Classify Images of Properly Filled and Underfilled Tires

Multiple industries are tasked with inspecting vehicle to make sure they are safe for the road.
For exampel:
Truck weigh station inspect eatch passing truck to verify they comply with safty regulations and their parts function properly.
Theis inspections are often lengthy and conducted manually.

## The Proplem :

One critical safty check is validating that tires are properly inflated. **Low pressure tires reduce vehicle handling and can lead to dangerouse blowouts on the road**.
**Tiers that are underinflated should be fixed befoure driving on them further**.

Manually checking eatch tire can  be sped up by employing an **Automated camera sysyem that captures images of vehicles as they drive past**. Machine Lerning models can process these images to determine what is being seen :

- **Full** : Properly inflated tire.
- **Flat** : Underfillted tire.
- **No-Tire** : Any non-tire object - Such as system could notify inspector anytime a flat tire is detacted.

The aim of this dataset is to provide sampel images to see if machine learning models can acuuratly catagorize images as **Full , Flat or no-tire**


## Content

This dataset consists of images captured by an OpenMV Cam H7 Plus. It includes **900 240x240** grayscale images labeled as either **"full", "flat", or "no-tire"**.

The images were captured from shifted angles and distances, as well as multiple tire rotation angles.

Provided is a directory tire-dataset that contains the entire dataset as .jpg images.

Three subdirectories titled after each label - "full", "flat", "no-tire" - contain the images for that label.

## Class Labels

**The "full" class** :

includes 300 images of tires at a proper tire pressure (~45 PSI). Images in this class are near-centered on a single car tire with a 6-12 inch buffer area surrounding it. Images are captured at slightly different angles and distances from the tire, and at various rotations of the tire.

**The "flat" class** :

includes 300 images of tires at a low tire pressure (~10 PSI). Images in this class are near-centered on a single car tire with a 6-12 inch buffer area surrounding it. Images are captured at slightly different angles and distances from the tire, and at various rotations of the tire.

**The "no-tire" class** :

includes 300 images non-tire objects. This includes images of the side of the car, empty garage background, and partial tires that to not meet the criteria of the "full" or "flat" labels.



The dataset and context can be found in :

https://www.kaggle.com/rhammell/full-vs-flat-tire-images
