# imugaitphase

This project aims to pave the way for the development of IMU-based gait phase estimation by employing the state-of-the-art technology, in particular deep learning algorithms.
This data incorporates for gait analysis, the two inertial sensors (XSENS
MTw Awinda, Xsens Technologies B.V., Enschede, The
Netherlands). The XSENS MTw Awinda is a small wireless
IMU sensor which is capable to give highly accurate 3D
orientation in real world environment. This cutting-edge motion tracker includes a 3D gyroscope, 3D accelerometer, and
3D magnetometer. The XSENS Kalman Filter optimises the
output signal to ensure the high performance with minimal
data loss while retrieving the human related motions. The
sensors were installed above the right and left ankles for
this study.


A list of several movement protocols was produced in
order for the model to learn different over-ground walking
styles and become flexible with diverse lower-body gestures
at varying walking rates to obtain the trained datasets.


Activity 1: Walk ahead for about 10 metres at a comfort-
able rate then stop, turn, and return at the same pace. The
task was repeated twice for both quicker and slower pace.
This is termed as a single trial. Each participant completed
two trials.


Activity 2: Rotate 360°while taking modest steps without
moving. This activity was completed at a comfortable self
selected speed. The task was repeated twice again, for both
quicker and slower pace. Each subject went through two
trials.


Activity 3: The first task was subjected to repeat, but the
participant was instructed to adjust the walking speed. Each
participant performed only one trial.


Activity 4: This activity includes the treading with both
legs. This was first completed at a comfortable rate without
shifting or switching locations, then for both quicker and
slower pace. Each subject performed two trials.


Activity 5: As the 4th exercise was performed, the subject
was instructed to take small steps forward and backwards
while executing the task without shifting positions or turning. Each participant completed one trial.


Activity 6: This step was to turn while walking forward.
The participant was instructed to stand on one side of
walking track up at the end, turn 180°while walking to
the other side, and then come to a complete halt.

# Create a virtual environment for this project as follows:
Create a new virtual environment by choosing a Python interpreter and making a .\venv directory to hold it:
python -m venv .\venv
# Activate the virtual environment:
.\venv\Scripts\activate
# Install required libraries from the requirements.txt file
pip install -r requirements.txt
Note: To exit the virtual environment later:
-) deactivate # don't exit until you're done with your project
