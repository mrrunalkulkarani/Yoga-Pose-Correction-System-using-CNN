# 🧘 Yoga Pose Correction

The **Yoga Pose Correction** project is a web-based application designed to help users practice yoga more effectively by detecting and correcting their body postures in real time. The system leverages the power of machine learning in the browser through **ml5.js** (built on top of TensorFlow.js) and **p5.js** to provide an interactive and lightweight solution that requires no additional installations or heavy dependencies. By using the webcam, the application is able to recognize body keypoints, classify poses, and give feedback on whether the user is performing a yoga posture correctly or not.  

One of the key features of this project is its ability to provide **real-time feedback**. As the user performs a pose, the application compares it against trained data stored in JSON files and visually indicates whether the pose matches the correct alignment. This interactive feedback loop makes it easier for beginners to understand where their posture might be off and how to adjust it. The interface is simple and user-friendly, allowing users to start practicing yoga directly from their browser without the need for any external software. The project also includes support for custom datasets, enabling further extension or retraining with additional yoga poses.  

The application is built entirely with **HTML, CSS, and JavaScript**, with ml5.js handling the machine learning aspects and p5.js providing visualization and interaction. Supporting assets like images, logos, and pre-trained JSON data are included to make the user experience engaging and informative. The project runs locally and can be accessed by simply opening the `index.html` file in any modern web browser, making it highly accessible and easy to deploy.  

To use the application, users simply clone the repository and open the main file in their browser. Once the page loads, camera permissions need to be granted for the system to capture body movements. From there, the user can interact with the interface by selecting different modules such as pose classification or correction. As they perform yoga poses in front of the camera, the system analyzes their keypoints and displays visual cues or feedback, guiding them toward the correct alignment. This creates an intuitive way of interacting with the program—essentially practicing yoga with a digital assistant that monitors posture in real time.  

Overall, this project combines **computer vision, machine learning, and web development** to deliver a practical fitness tool. It not only demonstrates how accessible machine learning in the browser has become but also provides a valuable resource for anyone interested in yoga, health, or technology.  

---

## 🚀 Getting Started

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/Yoga-Pose-Correction.git
   cd Yoga-Pose-Correction
   ```

2. Open `index.html` in your browser.  

3. Allow camera permissions to enable pose detection.  

4. Start practicing yoga and follow the on-screen corrections.  

---

## 📂 Project Structure

- `index.html` – Entry point of the app  
- `classify.js`, `correct.js` – Core logic for classification and correction  
- `script/` – Libraries (ml5.js, p5.js)  
- `style/` – Stylesheets for the interface  
- `data.json` – Pre-trained dataset for yoga poses  
- `assets/` – Images, GIFs, and visual resources   

---

## 🛠️ Technologies Used

- **HTML5, CSS3, JavaScript** for the frontend  
- **ml5.js** (PoseNet) for machine learning in the browser  
- **p5.js** for visualization and interactive design  

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork this project, open issues, or submit pull requests to improve functionality, add more yoga poses, or enhance the interface.  

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
