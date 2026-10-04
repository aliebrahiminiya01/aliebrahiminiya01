### Ali EbrahimiNiya

Computer engineering student at Urmia University, Tabriz. Data analysis, machine learning and deep learning.
Looking for a data science or ML role or internship, remote or hybrid.

[Website](https://aliebrahiminiya01.github.io) · [LinkedIn](https://www.linkedin.com/in/aliebrahiminiya) · [ali.ebrahiminiya.01@gmail.com](mailto:ali.ebrahiminiya.01@gmail.com)

#### Selected work

- **[Brain tumor segmentation in MRI](https://github.com/aliebrahiminiya01/brain-tumor-segmentation-unet)** —
  2D U-Net (PyTorch, MONAI) on 484 patients. Test Dice 0.90 / 0.86 / 0.85 for whole tumor, tumor core and
  enhancing tumor, with a patient-level split and a look at where it fails.
- **[Glioma grade prediction with radiomics](https://github.com/aliebrahiminiya01/glioma-grade-radiomics)** —
  LGG vs HGG on BraTS 2020 (369 patients). Shape features reach ROC AUC 0.95 in CV and 0.93 on a mixed-source test;
  texture features turn out to encode the scanner (AUC 0.99 for predicting the data source).
- **[Glioma survival analysis](https://github.com/aliebrahiminiya01/glioma-survival)** —
  1,040 TCGA LGG + GBM patients. Cox model C-index 0.81 and integrated Brier score 0.118 on a held-out test set;
  random survival forest and gradient boosting did not beat it.
- **[Automatic vs. expert masks for radiomics](https://github.com/aliebrahiminiya01/glioma-pipeline)** —
  the three projects above joined into one pipeline (U-Net mask → radiomics → grade and survival), with the
  U-Net retrained in 3 folds. Grade AUC 0.92 with U-Net masks vs 0.95 with expert masks, but 0.85 when a model
  trained on expert masks is applied to U-Net masks.
- **[Meal no-show prediction](https://github.com/aliebrahiminiya01/uni_restaurant_project_demo)** —
  which university restaurant reservations go uncollected. A leakage-free student-history feature and a
  time-based split took ROC AUC from 0.55 to 0.66.
- **[Hotel booking analysis](https://github.com/aliebrahiminiya01/Hotel_Project)** —
  119k bookings; cancellations rise from 8% for last-minute bookings to about 40% for ones made months ahead.
- **[Loan approval prediction](https://github.com/aliebrahiminiya01/Loan_Qualification)** —
  two scikit-learn models in a Tkinter app; when they disagree, a person decides.

#### Other projects

- **[Daymark](https://github.com/aliebrahiminiya01/Daymark)** — task manager and planner for Android (Python, Qt, SQLite), 46 tests and CI.
- **[Repair shop manager](https://github.com/aliebrahiminiya01/RepairShop)** — Persian right-to-left desktop software with Jalali dates and PDF invoices.
- **[Writing Exercise Studio](https://github.com/aliebrahiminiya01/writing_exercise_app)** — desktop app for writing practice.

#### Tools

Python, PyTorch, MONAI, scikit-learn, PyRadiomics, lifelines, scikit-survival, pandas, NumPy, SQL, Matplotlib, Jupyter, Git.
