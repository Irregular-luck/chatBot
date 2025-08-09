# Chatbot Chetan 🤖 - The Malayalam Roast Bot

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

> "നിങ്ങളുടെ സ്വന്തം റോസ്റ്റ് ബോട്ട്!"
>
> A hilarious, front-end chatbot that roasts you with iconic dialogues and images from classic Malayalam cinema.

![Chatbot Chetan Demo](./assets/demo.gif)

## About The Project

Chatbot Chetan is a fun, simple, and purely client-side web application. It doesn't use any complex AI or backend servers. Instead, it features a hand-picked collection of classic Malayalam movie dialogues to serve as witty, random "roasts." Type anything, and Chetan will hit you back with a memorable line and an image from the movie scene.

## Features ✨

-   💬 **Random Roasts:** Get a unique, random roast every time you ask.
-   🎬 **Iconic Malayalam Dialogues:** Features a curated list of unforgettable dialogues from beloved movies like *Sandesham*, *Kilukkam*, *Nadodikkattu*, and more.
-   🖼️ **Visual Roasts:** Each roast is paired with a memorable image from the movie scene to make it funnier.
-   🎨 **Quirky UI:** A playful, hand-drawn interface with fun fonts and colors to enhance the experience.
-   ⚡ **Purely Client-Side:** Runs entirely in your web browser. No installation or backend dependencies needed!

## Tech Stack 🛠️

-   **HTML5**
-   **CSS3** (with Google Fonts: Manjari & Bungee)
-   **Vanilla JavaScript**

## Getting Started 🚀

Because this is a front-end only project, getting started is incredibly simple.

### Prerequisites

All you need is a modern web browser (like Chrome, Firefox, or Edge).

### Installation

1.  **Clone the repository:**
    ```sh
    $git clone [https://github.com/](https://github.com/)[your-github-username]/[your-repo-name].git$
    ```
2.  **Navigate to the folder:**
    ```sh
    $cd [your-repo-name]$
    ```
3.  **Open the file:**
    Simply double-click the `index.html` file to open it directly in your browser. That's it!

## How to Use ▶️

1.  Open the `index.html` file.
2.  Type anything you want into the input box at the bottom.
3.  Click the **"Roast Me! ✨"** button or press `Enter`.
4.  Wait for Chetan to "think" and enjoy your roast!

## How to Add More Roasts ✍️

Want to contribute and make Chetan even funnier? You can easily add more dialogues!

1.  Open the `index.html` file in a text editor.
2.  Scroll down to the `<script>` section at the bottom.
3.  Find the `const roasts = [...]` array.
4.  Add a new object to the array following this format:

    ```javascript
    { 
        dialogue: "Your new roast dialogue here.", 
        movie: "Movie Name", 
        image: "URL_to_an_image.jpg" 
    },
    ```
5.  Save the file, and your new roast will be in Chetan's rotation!

## Contributing 🤝

Contributions are welcome! If you'd like to improve the UI or add features, please follow these steps:

1.  **Fork** the Project
2.  Create your Feature Branch (`git checkout -b feature/NewRoastStyle`)
3.  Commit your Changes (`git commit -m 'Add a cool new style for roasts'`)
4.  Push to the Branch (`git push origin feature/NewRoastStyle`)
5.  Open a **Pull Request**

## License 📄

Distributed under the MIT License. See `LICENSE` for more information.

---