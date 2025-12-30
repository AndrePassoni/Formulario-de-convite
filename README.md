<h1 align="center">Festivite</h1>

<p align="center">
  Exercise for Rocketseat Fullstack course - <strong>Festivite, a responsive event invitation form page built with HTML and CSS.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<br>

## 💻 About the Project

**Festivite** is a responsive event invitation form page developed as a practical exercise for the **Rocketseat Fullstack Course**.

The main goal of this project was to master advanced HTML and CSS concepts, focusing on **customizing native form elements** (like radios, checkboxes, and file inputs) and creating a responsive layout without relying on JavaScript for visual states.

## ✨ Key Features

- **Responsive Layout**: Built with a mix of **CSS Grid** and **Flexbox**, featuring a sticky sidebar and a scrollable form area.
- **Advanced Form Styling**:
  - **Custom Radio Buttons**: Color pickers with double-border effects using `box-shadow` and `outline`.
  - **Theme Selection Cards**: Grid-based image cards that act as radio buttons.
  - **Styled File Input**: A completely custom "Upload" button using the `::file-selector-button` pseudo-element.
  - **Custom Checkboxes**: Replaced native browser styles with custom SVG icons.
- **CSS-Only Validation**: Immediate visual feedback (red borders and error messages) for required fields using `:invalid` and `:not(:placeholder-shown)` selectors.
- **Visual Toggle Switch**: A styled toggle button for the "Light/Dark" mode concept.

## 🛠 Technologies Used

- **HTML5**: Semantic structure and accessible form attributes (`required`, labels).
- **CSS3**:
  - **CSS Variables** (`:root`): For consistent theming (colors, fonts, spacing).
  - **CSS Grid & Flexbox**: For layout structure and component alignment.
  - **Advanced Selectors**: Extensive use of `:has()`, `:checked`, `::after`, and sibling selectors (`+`, `~`) to control state changes.
  - **Media Queries**: ensuring the layout adapts to mobile devices.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AndrePassoni/Formulario-de-convite.git](https://github.com/AndrePassoni/Formulario-de-convite.git)
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Formulario-de-convite
   ```

3. **Open the project:**
   Simply double-click the `index.html` file to open it in your default web browser, or use a Live Server extension in VS Code.

## 🎨 Style Details

The project pays special attention to the UI details:
- **Fonts**: Uses *Baloo 2* for headings and *Open Sans* for body text.
- **Colors**: A vibrant color palette defined in `global.css`.
- **Interactions**: Smooth transitions on hover and focus states for all interactive elements.

## 📝 License

This project was developed for educational purposes as part of the Rocketseat curriculum.

---

Made with ♥ by **André Passoni**.