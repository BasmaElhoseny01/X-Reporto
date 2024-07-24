# X-Reporto

## <img align="center" width="60px" src="https://i.pinimg.com/originals/a0/45/ec/a045ece00adca277d0c18a42e025c76d.gif"> Table of Contents

<!-- Overview -->
## <img align="center" width="60px" height="60px" src="https://media2.giphy.com/media/Lqo3UBlXeHwZDoebKX/giphy.gif?cid=6c09b952ca6a8b16a6bd2e3a21cb529de5477c56ab8584ae&rid=giphy.gif&ct=s"> Overview <a id="Overview"></a>

<!-- System Design -->
## <img align="center" width="60px" src="https://static.wixstatic.com/media/5f84fe_fcede06aae5c437ab31306d83706e65a~mv2.gif"> System Design <a id="system"></a>
![image](https://github.com/user-attachments/assets/2d7859f6-55d6-4039-847f-c00d300681c2)

### Repositories
- **[AI Repository](https://github.com/BasmaElhoseny01/X-Reporto-AI)**: Contains all the AI modules for the X-ray analysis project, including object detection, classifiers, heatmap generation, and denoising models.
- **[Frontend Repository](https://github.com/BasmaElhoseny01/X-Reporto-Frontend)**: Includes the user interface for the X-ray application, designed using React and Ant Design. It handles the presentation and interaction aspects of the application.
- **[Backend Repository](https://github.com/BasmaElhoseny01/X-Reporto-Backend)**: Hosts the server-side code and APIs for the X-ray project, built with Flask/FastAPI. It manages data processing, model inference, and interactions between the frontend and AI components.

<!-- Getting Started -->
## <img align="center" width="60px" height="60px" src="https://media3.giphy.com/media/wuZWV7keWqi2jJGzdB/giphy.gif?cid=6c09b952wp4ev7jtywg3j6tt7ec7vr3piiwql2vhrlsgydyz&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=s"> Get Started <a id="started"></a>

### Native

#### AI Server

1. **Clone the Repository**
    ```bash
    git clone https://github.com/BasmaElhoseny01/X-Reporto-AI.git
    cd X-Reporto-AI
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Model Weights**
    ```bash
    # Download X-Reporto Models
    curl -o /models/object_detector.pth https://path-to-your-models/object_detector_best.pth
    curl -o /models/region_classifier.pth https://path-to-your-models/region_classifier_best.pth
    curl -o /models/LM.pth https://path-to-your-models/LM_best.pth

    # Download Heat Map Models
    curl -o /models/heat_map.pth https://path-to-your-models/heat_map_best.pth
    ```

4. **Run AI Server** (port 8001)
    ```bash
    python -m src.app
    ```

#### Backend Server

1. **Clone the Repository**
    ```bash
    git clone https://github.com/BasmaElhoseny01/X-Reporto-Backend.git
    cd X-Reporto-Backend
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Start the Backend Server** (port 8000)
    ```bash
    # Command to start the backend server
    ```

#### Client Server

1. **Clone the Repository**
    ```bash
    git clone https://github.com/BasmaElhoseny01/X-Reporto-Frontend.git
    cd X-Reporto-Frontend
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Start the Client Server** (port 3000)
    ```bash
    npm start
    ```

<!-- Contributors -->
## <img align="center" width="60px" src="https://www.123code.org/images/fields/GIF/coding.gif"> Contributors <a id="contributors"></a>

<!-- Contributors list -->
<table align="center">
  <tr>
    <td align="center"><a href="https://github.com/Ahmedsabry11"><img src="https://avatars.githubusercontent.com/u/75908511?v=4" width="150px;" alt=""/><br /><sub><b>Ahmed Sabry</b></sub></a></td>
    <td align="center"><a href="https://github.com/AhmedHosny2024"><img src="https://avatars.githubusercontent.com/u/76389601?v=4" width="150px;" alt=""/><br /><sub><b>Ahmed Hosny</b></sub></a></td>
    <td align="center"><a href="https://github.com/zeinabmoawad"><img src="https://avatars.githubusercontent.com/u/92188433?v=4" width="150px;" alt=""/><br /><sub><b>Zeinab Moawed</b></sub></a></td>
    <td align="center"><a href="https://github.com/BasmaElhoseny01"><img src="https://avatars.githubusercontent.com/u/72309546?v=4" width="150px;" alt=""/><br /><sub><b>Basma Elhoseny</b></sub></a></td>
  </tr>
</table>

## <img align="center" height="60px" src="https://cdn-icons-png.freepik.com/512/1046/1046441.png"> License <a id="license"></a>
This software is licensed under the MIT License. See [License](https://github.com/BasmaElhoseny01/X-Reporto/blob/main/LICENSE) for more information ©Basma Elhoseny.

---
<div align="center">
  This project is sponsored by 
  <a href="https://voyance.health/">
    <img src="https://github.com/user-attachments/assets/4802945c-bab5-4f61-a602-1f555792284b" alt="Voynace Medical Logo" height="20px">
  </a>
</div>

**Sponsored By**: This project is sponsored by <a href="https://voyance.health/"><img src="https://github.com/user-attachments/assets/4802945c-bab5-4f61-a602-1f555792284b" alt="Voynace Medical Logo" height="20px"></a>
