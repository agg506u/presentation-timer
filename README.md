# Presentation Timer for Google Colab / Jupyter Notebook

An elegant, extra-large visual timer with built-in metal bell sound alerts, specifically designed for managing presentation times in Google Colab or Jupyter Notebooks.

## Features
- **Responsive Large Display**: Easy to read even from a distance or on a shared screen.
- **Auto-Reflecting Controls**: Easily configure the time limit and warning timing using Google Colab form parameters.
- **Custom Sound Effects**: Utilizes the Web Audio API to generate beautiful metal bell chimes (1 chime for the warning time, 2 for time's up, and 3 for every extra minute over).
- **Count-Up After Time-Over**: Automatically switches to a count-up mode (`+01:00`) once the limit is exceeded, so you know exactly how much you've gone over.

## How to Use
1. Open the `.ipynb` file in Google Colab or your local Jupyter environment.
2. Set your desired hours, minutes, and seconds using the form on the right.
3. Run the cell and click **START**.

## 💡 Pro Tip for Google Colab Users
For the best experience during an actual presentation, we highly recommend displaying the timer in full screen:
1. Hover over the running timer cell and click on the **"Cell actions"** (the three vertical dots menu on the top-right of the cell output).
2. Select **"View output fullscreen"** Select "View output fullscreen". 

This will maximize the timer display, making it look like a dedicated professional timekeeper!
