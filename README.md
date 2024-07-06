# vide-emotion-analyzer
Python script for analyzing emotions in videos using facial recognition libraries. A project for extracting emotional data from videos with the fer library (FER stands for Facial Emotion Recognition)

# Features:

- Extracts emotional data from videos: Analyzes each frame to identify emotions displayed by individuals. 
- Supports various emotions: Detects anger, disgust, fear, happiness, sadness, surprise, and neutral expressions.
- Generates data visualizations: Creates informative plots to visualize the emotional trends throughout the video.

# Requirements:

- Python 3.x
- `fer` library (`pip install fer`)
- `pandas` library (`pip install pandas`)
- (Optional) `matplotlib` library (`pip install matplotlib`) for visualizations

 # Installation:

1. Install the required libraries (`fer`, `pandas`, optionally `matplotlib`) using pip:

   pip install fer pandas matplotlib  # (optional for visualizations)


# Usage:

1. Clone or download this repository.
2. Update the video file paths in the script (`video_emotion_analysis.py`) to point to your videos.
3. Run the script from the command line:

   python video_emotion_analysis.py

5. Or run it on Google Colab
   

# Output:

The script will:

- Analyze the video(s).
- Generate a pandas DataFrame containing the detected emotions for each frame.
- Create a plot (if `matplotlib` is installed) visualizing the emotional trends over time.
