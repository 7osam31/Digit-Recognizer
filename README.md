# Digit-Recognizer

---

## What Didn't Work:
In the first training run, the loss dropped to almost 0% unexpectedly. This was an indication of severe **Overfitting**, as the Validation Accuracy was significantly lower than the Train Accuracy. 

---

## What Worked:
I successfully boosted the accuracy to **over 99%**. I protected the model from overfitting by implementing **Data Augmentation** and **Dropout** layers. Additionally, I significantly decreased training time and avoided wasted compute power by utilizing **Early Stopping**.

---

## What I'd Change:
In the future, I would like to use a more complex, real-world dataset that contains colored images and multi-digit numbers (like "1034") to expand the model's capabilities.

---

## Next Steps:
My next step is to deploy this trained model into a web application. Furthermore, I aim to test it on real-world bank datasets to explore its utility in automated **Check/Cheque** reading systems.
