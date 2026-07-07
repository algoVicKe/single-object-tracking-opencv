# Single Object Tracking with OpenCV

This project implements single object tracking using optical flow (Lucas-Kanade method) in OpenCV. The tracker follows a moving object across video frames, stores its trajectory, and visualizes the movement path.

## Features

- Video acquisition with upload, existing file, or sample download options
- Automatic object detection using contour detection in the first frame
- Optical flow based tracking (Lucas-Kanade method)
- Trajectory visualization with start and end points
- Position over time plotting
- Trajectory data export to CSV

## Files

- `single_object_tracking.ipynb` - Main Jupyter notebook with complete implementation
- `trajectory_plot.png` - Visual trajectory path of the tracked object
- `trajectory_data.csv` - Frame-by-frame position data
- `tracked_output.avi` - Output video with tracking overlay (optional)

## Requirements

- Python 3.7+
- OpenCV
- NumPy
- Matplotlib
- Pandas

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Run all cells sequentially
3. Upload a video or use an existing/sample video
4. Object is automatically detected and tracked
5. View trajectory plots and export data
