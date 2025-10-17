# Bowel-Sound-Detection

 **Project:** Bowel sound detection (classes: `b`, `mb`, `h`) with onset/offset regression inspired by the paper: *You Only Hear Once: A YOLO-like Algorithm for Audio
Segmentation and Sound Event Detection*.


paper's link: https://arxiv.org/abs/2109.00962
---
**Summary:**
- **Problem:** Detect bowel sound events in continuous audio and provide event type (`b`, `mb`, `h`) and precise start/end times.  
- **Why it matters:** Non-invasive monitoring of gut sounds can assist diagnosis and monitoring of gastrointestinal motility disorders; automated detection can scale screenings and enable remote patient monitoring.  
- **Approach:** We adapt the YOHO paradigm — transforming frame-based classification into a regression + classification network that predicts event presence and event boundaries directly. This yields faster inference and simpler post-processing.  
- **Results & impact:** (See K-Fold results below.) The model shows promising detection and temporal localization performance across folds; next steps include more data, refined augmentation, and clinical validation.
---
