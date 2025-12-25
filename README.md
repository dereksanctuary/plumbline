# plumbline

plumbline is a video-based posture analysis tool built with MediaPipe Pose.  
it analyzes prerecorded video to estimate neck and torso inclination and evaluate posture consistency over time.

## approach
- processes prerecorded video for consistent framing
- computes joint angles using custom geometry
- tracks posture using streak-based logic rather than raw frame counts
- designed for extensibility (calibration, alternative views, real-time input)

## note
this project is inspired by open-source mediapipe posture analysis work, but is reimplemented from scratch with original structure and logic.
