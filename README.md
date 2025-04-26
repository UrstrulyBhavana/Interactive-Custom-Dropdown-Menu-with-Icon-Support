# 🎨 Custom Select Menu Design
---

## Demo.gif

![Image](https://github.com/user-attachments/assets/d8714591-c401-45e1-9de0-e909a920047c)

---

A sleek and interactive **Custom Select Menu** for modern web applications. This project replaces the default dropdown with a beautifully designed, fully customizable select menu featuring smooth animations and social media icons.

---

## Features
- 🖱️ **Interactive Select Menu:** Click to reveal a list of social media options.
- 🎨 **Custom Styling:** Designed to replace the default HTML dropdown for a polished look.
- 🖌️ **Smooth Animations:** Includes smooth opening and closing animations for the menu and arrow icon rotation.
- 🖥️ **Responsive Design:** Works seamlessly across desktops, tablets, and mobile devices.
- 🖼️ **Icon Integration:** Displays social media icons next to each menu option.

---

## Technologies Used
- 🎨 **HTML:** Creates the structure for the select menu and options.
- 🎨 **CSS:** Styles the select menu, dropdown options, and animations.
- ✨ **JavaScript:** Implements the interactive functionality, including toggle effects and content updates.

---

## How to Use

1. **Interact with the Menu:**
   - Click on the **"Select Social Media"** field to open the dropdown menu.
   - Choose your desired social media platform by clicking on one of the options.

2. **View the Selection:**
   - The selected option will replace the **"Select Social Media"** placeholder text.

3. **Responsive Design:**
   - Enjoy a smooth experience on all devices, from desktops to smartphones.

4. **Customizable Options:**
   - Modify the social media options and icons by updating the HTML `li` elements in the dropdown.

---

## Key Code Snippets

### JavaScript for Menu Interaction
```javascript
var selectField = document.getElementById("selectField");
var selectText = document.getElementById("selectText");
var options = document.getElementsByClassName("options");
var list = document.getElementById("list");
var arrowIcon = document.getElementById("arrowIcon");

selectField.onclick = function() {
    list.classList.toggle("hide");
    arrowIcon.classList.toggle("rotate");
};

for (option of options) {
    option.onclick = function() {
        selectText.innerHTML = this.textContent;
        list.classList.toggle("hide");
        arrowIcon.classList.toggle("rotate");
    };
}
```

---

🙋‍♀️ Author
Linga Bhavana – Frontend Developer

GitHub | urstrulybhavana1432@gmail.com

---


📬 **Contact**

For questions or suggestions, feel free to reach out:

- 📧 **Email**: [urstrulybhavana1432@gmail.com](mailto:urstrulybhavana1432@gmail.com)  
- 🐙 **GitHub**: [UrstrulyBhavana](https://github.com/UrstrulyBhavana)


---

📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
