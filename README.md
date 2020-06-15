# Pneumonia-classification-using-chest-X-ray
A data preparation and model building notebook on pneumonia classification, created on kaggle

## Context
The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse interstitial pattern in both lungs. The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care. 

## Glimpse of data
Data is imabalanced with 3000+ pneumonia images and 1000+ normal images
<img src='https://www.kaggleusercontent.com/kf/36412895/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..0gpKorQjY0UXavpl-pXnPg.hhmykHyq7i2y_CWTFdomWDKJZIlJpNMVtVXeFNGeCSccGckL2dAkF42jOLbYZO0p-hXdSFs2Hpv2tKb6SkoHf2UMwbtk6knq3qNMrdjhIks5CIRoTJlLyEJtekn_Gi6WoqIeSk3fOE79uD4AU3ScPHpjFKXYJsIf-xsbMDIKCcxlACp12LXSMoIKRnXXSUxq59W22WCGfSFihekj9Qh8maQMarlla2vMfUZBzBLO6dxMl15C4KII79WwJdUcs-_HstDqu0LP_MfWaPQSLEGzpZykfABmKwglcd8IkTSn0meduetKpN8qQh4jMKk-9_s6XV5BiJjJ_VVL_sl-QLKjDiSukxOSPJT8CY79YaHQFVPM0q2PIlMF1lJjaBDjVavdc9vApkSSMHwjcTFIPFcezwwYdyotU1RQBJdyKy4SvN0b6LK-kBPtxNznH0AdTOy9y2bmCWNQNjk-gGXqGynlkCTvnnTYJKjkcFBte0BIkbXJpEV2SOFTxZCqlbl7jM3-_oXcKMPPFaBn03adBjyUwk2ffU55McDuu7R7b6Ud59HD9quvW9R4mZdhsyAI3r4-20Bbm0GO69nHUTZPHnoQ8lgrCNKlBZ-kWH82k5k9T9RtxKvQv6vURT8nnRMZXeKWaAFfsBWZhqG_y0QXEjD1ZpHpiraPFbq5o59bTEJv3AMDclvzLO3Oqw1prLZ-kO1D.qSnkjJhe5RfPzTpOrGAoYg/__results___files/__results___9_0.png'></img><br>
These images look almost similar no matter the case and therefore feature extraction would be quite difficult, I tried to acheive a precision of 0.93 despite of maximum images being of pneumonia. Issue a pull request if acheived better results :)
