# AATEC-Online: Approach Avoidance Training vs Evaluative Conditioning 

**Author:** Anoushiravan Zahedi  
**Repository:** [https://github.com/anoushzahedi/AATEC](https://github.com/anoushzahedi/AATEC)

## Overview
This version of the **AATEC** suite is optimized for **online administration** and behavioral lab settings. It utilizes standard computer peripherals (**Mouse & Keyboard**) to ensure maximum accessibility and ease of use for remote participants.

The task investigates how attentional training influences consumer preferences and choice behavior using a modular within-subject design.

---

## Experimental Structure

The experiment consists of three sequential parts:

### Part 1: Baseline Preferences
1. **Willingness to Pay (WTP)**: Participants view toy images and indicate their valuation using a **mouse-controlled** continuous slider.
2. **Binary Choice Task**: A rapid choice task where participants use the **keyboard** to indicate whether they would like to have the presented toy.

### Part 2: Attentional Training
1. **Approach/Avoid Task (Sound-Cued)**: Participants use the **mouse** to "pull" or "push" toys based on auditory cues (e.g., high vs. low pitch tones).
2. **Emotion Categorization Task**: A speeded **keyboard-response** task where participants categorize emotional stimuli as quickly and accurately as possible.

### Part 3: Post-Training & Competitive Choice
1. **Willingness to Pay (WTP)**: Follow-up valuation to measure the impact of training.
2. **Binary Choice Task**: Follow-up choice consistency check.
3. **Competitive Choice Task**: A forced-choice paradigm where participants use the **mouse or keyboard** to choose between two simultaneously presented options.

---

## Technical Specifications

### Administration & Input
- **Optimized for Online Use**: Designed for stability across different monitor sizes and web-based environments.
- **Input Devices**: 
  - **Mouse**: Used for continuous scales and approach/avoid movements.
  - **Keyboard**: Used for rapid categorization and binary decisions.
- **Software**: Compatible with MATLAB/Psychtoolbox or exportable for web-based platforms (e.g., Pavlovia/JATOS).

### Data Quality & Engagement
- **Attention Checks**: Multiple validated attention checks are embedded throughout the tasks to ensure data reliability in unmonitored environments.
- **Inactivity Timeout**: The task will automatically terminate if no response is detected for **3 minutes** to prevent incomplete or low-effort data collection.

---

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/anoushzahedi/AATEC.git
   ```
2. Ensure your environment supports audio playback for the sound-cued tasks.
3. Run the initialization script to calibrate the screen and input sensitivity for the participant's local hardware.

## License
This project is licensed under the MIT License.
