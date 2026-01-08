
# Color Flipper Project

This is a simple yet functional **Color Flipper** application. It is a single-page project where the styling and logic are integrated directly within the HTML structure for a lightweight approach.

---

# 📝 What Does It Do?

The Color Flipper is a web tool that generates colors and applies them to the document's background. It provides a visual way to explore different color codes instantly.

* **Random Color Generation:** Creates new colors on every click.
* **Color Code Display:** Shows the specific code (e.g., #F15025) so the user can see exactly what color is being applied.
* **Single-File Build:** The entire project is contained in an efficient, easy-to-read structure.

---

# ⚙️ How Does It Work?

The project's logic is based on DOM manipulation and internal styling:

1. **Internal Styling:** All visual designs are defined within `<style>` tags in the `<head>` section of the HTML, making the project highly portable.
2. **Selection:** The JavaScript code selects the button and the color display text using `document.getElementById` or `querySelector`.
3. **Randomization:** A function generates a random index or a hex string (0-9, A-F) using the `Math` library.
4. **Dynamic Update:** When the button is clicked, the script directly modifies the `document.body.style` property and updates the UI text.

---

# 🎓 What Have I Learned?

Building this project helped me strengthen my fundamentals in:

* **Internal CSS Integration:** Learning how to manage styles efficiently within an HTML file using `<style>` tags.
* **DOM Manipulation:** Understanding how to target and modify HTML elements and background styles using JavaScript.
* **Logic Building:** Mastering `Math.random()` and `Math.floor()` to pick items from arrays or generate codes.
* **Event Handlers:** Learning how to trigger functions based on user interactions like clicks.
