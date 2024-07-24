# <img align="center" width="60px" src="https://github.com/user-attachments/assets/1ae2a162-f969-4475-9618-7f16bdb24d98"> X-Reporto
<div align="center">
    <img src="https://github.com/user-attachments/assets/b54cdd8b-c180-4af8-8b85-31ef40c283e4"/>
</div>


## <img align="center" width="60px" src="https://i.pinimg.com/originals/a0/45/ec/a045ece00adca277d0c18a42e025c76d.gif"> Table of Contents
- <a href="#Overview">Overview</a>
- <a href="#tools">Built Using</a>
- <a href="#system">System Design</a>
- <a href="#started">Get Started</a>
- <a href="#contributors">Contributors</a>
- <a href="#license">License</a>

<!-- Overview -->
## <img align="center" width="60px" height="60px" src="https://media2.giphy.com/media/Lqo3UBlXeHwZDoebKX/giphy.gif?cid=6c09b952ca6a8b16a6bd2e3a21cb529de5477c56ab8584ae&rid=giphy.gif&ct=s"> Overview <a id="Overview"></a>
**X-Reporto** is a web-based application designed to support radiologists by automating the reporting process for chest X-ray images. The tool enhances image quality to correct X-ray device defects, generates detailed saliency maps to highlight key findings, and produces comprehensive, template-based reports tailored to each anatomical region and identified disease. By streamlining the diagnostic workflow, **X-Reporto** reduces report generation time and improves diagnostic accuracy, ultimately aiding in faster and more precise medical interventions.

<!-- Tools -->
## <img  align= center width =60px  height =70px src="https://media4.giphy.com/media/ux6vPam8BubuCxbW20/giphy.gif?cid=6c09b952gi267xsujaqufpqwuzeqhbi88q0ohj83jwv6dpls&ep=v1_stickers_related&rid=giphy.gif&ct=s"> Built Using<a id="tools"></a>
<!-- Common Tools -->
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td><img height="60" src="https://iconape.com/wp-content/png_logo_vector/ubuntu-2.png"/></td>
    <td><img height="65" src="https://github.com/user-attachments/assets/9ec6a53e-f371-4d7d-a7dc-2092197c98e2"/></td>
    <td><img height="60" src="https://1000logos.net/wp-content/uploads/2021/11/Docker-Logo-2013.png"/></td>
    <td><img height="60" src="https://learnersgalaxy.ai/wp-content/uploads/2024/01/Python-Symbol.png"/></td>
  </tr>
</table>

<!-- AI Tools -->
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td><img height="55" src="https://github.com/user-attachments/assets/8e5bc6e1-db46-43a6-bb3d-41e6c5973cd2"/></td>
    <td><img height="65" src="https://www.tensorflow.org/static/site-assets/images/project-logos/tensorboard-logo-social.png"/></td>
  </tr>
</table>

<!-- Backend Tools -->
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td><img height="30" src="https://vectorseek.com/wp-content/uploads/2023/09/FastAPI-Logo-Vector.svg-.png"/></td>
    <td><img height="40" src="https://github.com/user-attachments/assets/9121ea56-7d1c-4b96-8a3c-69292c18ca11"/></td>
  </tr>
</table>

<!-- Frontend Tools -->
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td><img height="60" src="https://miro.medium.com/v2/resize:fit:800/0*CBjisl422hUyLxiG.png"/></td>
    <td><img height="60" src="https://github.com/user-attachments/assets/f854d789-64f8-4b25-8365-bf29f49475fc"/></td>
    <td><img height="55" src="https://raw.githubusercontent.com/styled-components/brand/master/styled-components.png"/></td>
    <td><img height="55" src="https://reactrouter.com/_brand/react-router-stacked-color.png"/></td>
    <td><img height="70" src="https://redux.js.org/img/redux-logo-landscape.png"/></td>
    <td><img height="70" src="https://github.com/user-attachments/assets/30b73649-3292-4797-975b-26d1ba1b3677"/></td>
    <td><img height="60" src="https://github.com/user-attachments/assets/7a7ee3e6-67c4-42f5-9e7c-975a698eae88"/></td>
  </tr>
</table>

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

4. **Run AI Server**
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

3. **Start the Backend Server**
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

3. **Start the Client Server**
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

<hr style="border: 0.5px solid #ccc;">

### This project is sponsored by
<div align="center">
  <a href="https://voyance.health/">
    <img src="https://github.com/user-attachments/assets/4802945c-bab5-4f61-a602-1f555792284b" alt="Voynace Medical Logo" height="35px">
  </a>
</div>
