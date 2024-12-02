# Aries Exoplanet Map 🌌
Aries is an interactive 2D map that allows users to explore exoplanets using data from the NASA Exoplanet Archive (PSCompPars). The app enables users to select an exoplanet and view its information. Key features include a search function to locate specific exoplanets, the ability to draw and name constellations, and color-coded planet auras based on temperature. Users can also access detailed information about each exoplanet through an intuitive interface. The app supports exploration across three planes (XY, YZ, and XZ), providing a dynamic way to visualize exoplanets in relation to each other and the sun.

## Project Demonstration 📑
- [Slides](https://drive.google.com/file/d/1-vPQSL-xsWfJW2wppI1yigwxe6l_E70-/view?usp=sharing)
- [Live Demo](https://codingkatty.github.io/aries/)

---

# Project Details ❓
Here are some information about this project we made.

## Function ⚙️
Aries offers a user-friendly, interactive map for exploring over 5500 exoplanets. Users can draw constellations and learn more about each exoplanet's characteristics in this interactive website we made.

1. **Interactive Map** - Displays exoplanets in 2D across three different planes, allowing for detailed spatial exploration.

2. **Temperature-Based Color** - Each exoplanet is color-coded according to its temperature, allowing users to visually differentiate planets based on their environmental conditions.

3. **Show Direction** - Displays a dashed line connecting the selected exoplanet to the sun, providing users with spatial awareness of the exoplanet’s location in relation to the solar system. Also allowing users to find location of  planets from searches.

4. **Search Function** - Allows users to search for exoplanets by name, making navigation easier.

5. **Information Tab** - Displays detailed information about each exoplanet when clicked, including data like temperature and other relevant properties.

6. **Constellation Drawing** - Users can connect exoplanets to form constellations, mimicking the experience of ancient astronomers drawing constellations on Earth.

<p align="center">
    <img src="https://assets.spaceappschallenge.org/media/images/Screenshot_2024-10-06_132832_kpbefmQ.width-500.png" height="200">
    <img src="https://assets.spaceappschallenge.org/media/images/Screenshot_2024-10-05_201206_utpqi2Q.width-1024.png" height="200">
</p>

## How to Use 📚
To draw a constellation, click the "+" button located beside the search bar. Select two exoplanets to create a line between them. Continue connecting exoplanets to form your desired constellation. The side panel will automatically update to show information about the planets included in your constellation. Note: while in constellation mode, the "Show Direction" feature is disabled, and side panel data cannot be reopened by clicking on planets. There's also a bug for drawing constellations (see bugs).

## Tech Stack 💻
![HTML](https://img.shields.io/badge/HTML-FF5733?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Sublime Text](https://img.shields.io/badge/Sublime%20Text-FF9800?style=for-the-badge&logo=sublime-text&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-6C63FF?style=for-the-badge&logo=cursor&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Bugs 🪱
Array Bug in Constellation Drawing: When creating constellations, the system sometimes generates duplicate entries due to how data is stored. For example, if you draw a triangle between points (a -> b, b -> c, c -> a), the data can produce duplicate entries, causing the artwork to break in some cases (deletes b->c right away in same order). Although the constellation mode remains functional, this bug may impact user experience if the plane is switched or constellation mode is reopened.

## Team 💕
Zhi Cheng - Homepage and Design <br>
Candy - Exoplanet Map

---

### Use of Artificial Intelligence 🤖
We utilized artificial intelligence tools like ChatGPT and Claude 3.5 for assistance with project development. These AI models helped with debugging code, summarizing information, and brainstorming ideas, enhancing the project’s overall efficiency and innovation.

### Space Data 🔭
- [NASA Exoplanet Archrive](https://exoplanetarchive.ipac.caltech.edu/index.html)

### References 🖇️
- [Image](https://www.freepik.com/premium-ai-image/galaxy-outer-space-beautiful-fiction-wallpaper_187605341.htm)
- [Equatorial to Cartesian](https://www.jameswatkins.me/posts/converting-equatorial-to-cartesian.html)
- [Favicon Maker](https://formito.com/tools/favicon)
