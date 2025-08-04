# Final-Computer-Vision

## Data Description

The dataset was obtained from **ChaLearn Looking at People**. It was prepared for the project and placed in the `/datasets/faces/` folder. The folder contains:

- `final_files/` — a directory with 7.6k facial photos  
- `labels.csv` — a CSV file with two columns: `file_name` and `real_age`

As the number of image files is quite large, it's best **not to load them all at once** to avoid using too much memory. Instead, read the images sequentially using the `ImageDataGenerator` class. This method was explained in **Chapter 3: Convolutional Neural Networks**, **Lesson 7: Data Generators**.

---

## Your Task

Perform the **Exploratory Data Analysis (EDA)**:

- Check the dataset size.
- Explore the age distribution.
- Display 10–15 sample photos from different age groups to get a visual impression of the data.

**Paths to the files for analysis:**
- `/datasets/faces/labels.csv`
- `/datasets/faces/final_files/`

---

## Notes

- Consider how dataset characteristics (e.g. age imbalance, image quality, or lighting conditions) may affect model training.
- These factors may impact performance and should guide how you prepare and augment the data.
