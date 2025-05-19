# AgriSense: An AI Powered Platform for Image-Based Crop Health Monitoring and Yield Estimation

AgriSense is an AI-powered web platform developed as a Final Year Project at Namal University. It empowers farmers with actionable insights by leveraging deep learning, computer vision, and cloud technologies to automate crop diagnosis and yield estimation from images.

🔗 **Web Platform:** [AgriSense Platform](https://github.com/ayeshag7/AgriSense-Platform)

---

## Key Features

- **Crop Type Detection**  
  Automatically predict the type of crop (e.g., wheat, maize, rice) from uploaded images to enable context-aware analysis.

- **Disease Diagnosis**  
  Diagnose crop diseases using image-based detection models. Outputs include disease name, confidence score, severity level, and treatment recommendations.

- **Yield Estimation**  
  Estimate crop yield from field images using object detection to count yield-relevant structures (e.g., wheat heads), including optional image stitching for wider field coverage.

- **Health Timeline Tracking**  
  Track changes in crop health across time by grouping multiple images under a field ID. Compare improvements post-treatment using severity scores and overlays.

- **Smart Report Generation**  
  Generate PDF or web-based reports summarizing diagnosis results, severity, treatment notes, and timeline progression with optional QR linking.

- **Interactive Dashboard & Analytics**  
  View diagnosis history, visualize disease trends, and explore health analytics such as infection percentages, common diseases, and time-based patterns.

- **AI Chatbot Assistant**  
  Integrated chatbot to guide users, answer agriculture-related questions, and support decision-making using model insights.

---

## Project Structure
* `src/` → Source code for models, diagnosis engine, web and mobile app
* `datasets/` → Sample images and annotations for training/testing
* `docs/` → Reports, design documents, and references

