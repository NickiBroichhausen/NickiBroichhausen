# Hi, I'm Nicki

I am a Master's student specializing in Satellite Technology and Robotics at Julius Maximilians Universtiaet in Germany. I am currently completing my Master's thesis at DLRs Robotics and Mechatronics Institute where I focus on **Visual Odometry** for planetary exploration.

**Research Interests:** Computer Vision • Autonomous Navigation • Planetary Robotics • Space Systems

---

## Key Research & Projects

### Visual Odometry for Planetary Exploration
* **Role:** Master's Thesis Researcher
* **Tech Stack:** C++, ROS2, OpenCV, Eigen, Sophus
* **Summary:** Developing a scale-aware Visual Odometry (VO) framework for autonomous planetary drones, based on Basalt [[1]](https://gitlab.com/VladyslavUsenko/basalt). Solving scale ambiguity with stereo cameras even at high flight altitudes.

### PRELUDE Satellite Mission
* **Role:** Lead Software Engineer (Exchange Semester in Japan)
* **Tech Stack:** C++, Arduino, Electrical Components
* **Summary:** Led the development of the mission software for the PRELUDE CubeSat Mission, which allowed for high througput on-board data processing with a prallel multicore design.
* **Images:**
    <p align="center">
      <img width="400" alt="image" src="https://github.com/user-attachments/assets/e94e839c-41fc-4107-b173-e859c23ff21f" />
      <br />  <em>Figure 1.1: Assembled Mission OBC</em> <br />
    </p>
* **Links:** [PRELUDE Project](https://github.com/PRELUDE-Project)

### FloatSat: State Estimation
* **Summary State Estimation:** Developed a camera based system to estimated spacecraft orientation. Designed a new feature descriptor inspired by SIFT, that relied on star formations instead of color gradients, allowing feature matching in sparse images of the night sky. 
* **Tech Stack:** Python, RaspberryPI, OpenCV, Electrical Components
* **Images:** 
    <p align="center">
      <img width="500" alt="image" src="https://github.com/user-attachments/assets/4b68752d-e9b7-4fb0-86d9-079876afb6b0" />
      <br />  <em>Figure 2.1: Example of a Feature Descriptor Based on Star Formations</em>  <br />
      <img width="500" alt="image" src="https://github.com/user-attachments/assets/ad92be0b-c4e4-4381-bf00-2ebb874f13ca" />
      <br /> <em>Figure 2.2: Example of All Star Formations in an Image</em>  <br />
      <img width="500" alt="image" src="https://github.com/user-attachments/assets/3de5954a-8d0e-4bc6-9f44-c73b5622bf6c" />
      <br />  <em>Figure 2.3: Example of Feature Matching Between Two Images</em> <br />
    </p>
* **Links:**  [StarSift](https://github.com/NickiBroichhausen/starmapper)

### FloatSat: AI Controller
* **Summary AI Controller:** Developed a Reinforcement learning controller to control spacecraft attitude with a reaction wheel
* **Tech Stack:** Python, Basilisk Simulation [[2]](https://github.com/AVSLab/basilisk/), Gym, StableBaselines
* **Images:**
    <p align="center">
      <img width="400" alt="image" src="https://github.com/user-attachments/assets/3507ca94-e76f-4b77-b719-6516413beebf" />
      <br />  <em>Figure 3.1: Example of Satellite Position and Control Input Over Time</em> <br />
    </p>
* **Links:**  [AI Controller](https://github.com/NickiBroichhausen/FloatSat_AI_Controller)


### NASA Space Apps Challenge
* **Tech Stack:** Python, TensorFlow, sklearn, Jupyter Notebooks
* **Summary:** Local Event Winner at the NASA Space Apps Challenge Hackathon with our AI algorithm that detects anomalies in Seismometer data
* **Images:**
    <p align="center">
      <img width="600" alt="image" src="https://github.com/user-attachments/assets/56943fec-24bd-421d-9758-6a01c0e86e52" />
      <br />  <em>Figure 4.1: Example of Input Data and predicted Anomalie</em> <br />
    </p>
* **Links:** [Jupyter Notebook](https://github.com/NickiBroichhausen/NASASpaceAppChallange24/blob/main/Seismic_ML.ipynb)


### Fraunhofer Research Camp on Autonomous Flight
* **Tech Stack:** Python, TensorFlow, OpenCV, ROS
* **Summary:** 1 week research camp with a group project on autonoumous landing site detection with a JetsonOrin, based on an Image Segmentation AI
* **Images:**
    <p align="center">
      <img width="500" alt="image" src="https://github.com/user-attachments/assets/4639146a-2d50-4b44-8858-9640b897c627" />
      <br />  <em>Figure 5.1: Code Architecture Overview </em> <br />
      <img width="500" alt="image" src="https://github.com/user-attachments/assets/f44890df-c203-49a8-ad0f-62f9c8a46216" />
      <br />  <em>Figure 5.2: Landing Spot Detection Based on Image Segmentation</em> <br />
    </p>

    





---

## Publications & Presentations
* **N. Broichhausen**, M. Yamazaki, M. Schmidt, "A Case Study of CLTP14: How Knowledge from the PRELUDE Satellite is Used to Educate the Next Generation of Space Leaders" presented at the *5th Symposium on Space Educational Activities (SSEA)*, Munich, 2026.

---

## Technical Toolkit
* **Languages:** C++, Python, LaTeX
* **Libraries & Frameworks:** ROS2, OpenCV, Sophus, Eigen
* **Tools:** Git, Docker, Linux
