
# Smart-Basketball-Score-Board
This IoT-based system detects a basketball and the hoop in real time and determines if a shot results in a score. By analyzing object positions in real-time , the model can detect whether the ball went through the hoop and updates it on the Scoreboard.
## Features
- **Real-time Detection:** Uses YOLOv8 for fast and accurate detection of basketball and hoop.
- **Scoring Analysis:** Determines if the basketball successfully enters the hoop.
- **Scoreboard:** Score is updated on the LED Scoreboard as well as the webpage.
## Technologies Used

- **YOLOv8:** A machine learning model for Object detection for identifying the basketball and hoop.
- **Python:** Primary language for running detection scripts.
- **OpenCV:** Library used for video processing.
- **IoT Devices**: Arduino UNO, RF Module, wireless cameras, WS2812B LED (For scoreboard), Jetson Xavier (GPU).
## Setup

###  Clone the Repository
```bash
 git clone https://github.com/muzammil-ibrahim/Smart-Basketball-Score-Board
```
### Install the dependencies
```bash
  pip install -r requirements.txt
```
### To Run the program
- Download the input video and set the path.
- Run main.py
- Check the webpage.
## Contributors
- [Afreed](https://github.com/mohd-afreed)
- [Ibrahim](https://github.com/muzammil-ibrahim)
- [Shahed](https://github.com/MOHAMMEDSHAHED786)
- [Sumaiya]()
- [Vaishnavi](https://github.com/vaishnavijade)
- [Vyahruti](https://github.com/Vyahruti)
