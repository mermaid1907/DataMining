# TP, TN, FP, FN

Say that your aim is to detect wheteher an email is smap or not, in that case if the the model

1. flags a **spam** email as **spam** this is **True Positive**
2. flags a **non-spam** email as **non-spam** this is **True Negative**
3. flags a **spam** email as **non-spam** this is **False Negative**
4. flags a **non-spam** email as **spam** this is **False Positive**

# Accuracy

Accuracy is calculated with following formula:
`Accuracy = (TP + TN) / (TP + TN + FP + FN)`

Accuracy is one of the metrics that's used to evaluate a model's overall performance.



