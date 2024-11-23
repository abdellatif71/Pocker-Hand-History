 Poker Hand History to XML Converter

This project is a simple web application that converts poker hand histories into XML format. It is ideal for analyzing poker sessions or processing the data in other systems.

## 🛠️ Features
- User-friendly interface for entering poker hand histories.
- Automatic conversion of hand histories to XML format.
- Display of the generated XML code directly in the browser.

## 📋 Requirements
You only need a web browser to use this application.

## 🚀 How to Use
1. Open the `index.html` file in your browser.
2. Enter your poker hand history in the provided text area, using the following format:
Player: John,1000 Player: Alice,2000 Player: Bob,1500

php
Copier le code
3. Click the **"Convert to XML"** button.
4. The generated XML will be displayed below, like this:
```xml
<session sessioncode="123456789">
  <game gamecode="987654321">
    <players>
      <player seat="1" chips="1000" name="John" />
      <player seat="2" chips="2000" name="Alice" />
      <player seat="3" chips="1500" name="Bob" />
    </players>
  </game>
</session>
💡 Example Hand History
Input:

makefile
Copier le code
Player: John,1000
Player: Alice,2000
Player: Bob,1500
Output XML:

xml
Copier le code
<session sessioncode="123456789">
  <game gamecode="987654321">
    <players>
      <player seat="1" chips="1000" name="John" />
      <player seat="2" chips="2000" name="Alice" />
      <player seat="3" chips="1500" name="Bob" />
    </players>
  </game>
</session>
📂 Project Structure
bash
Copier le code
index.html  # Main file containing HTML, CSS, and JavaScript
🖌️ Design
Minimalistic and user-friendly design.
Color scheme:
Background: Light gray (#f8f9fa)
Button: Blue (#007bff), changes to dark blue (#0056b3) on hover.
🔧 Customization
If you want to modify the XML structure or adjust the layout, you can edit the JavaScript code inside the <script> block of the index.html file.

📜 License
This project is licensed under the MIT License. You are free to use and modify it.

📧 Contact
If you have any questions or feedback, feel free to contact me:
Abdellatif Abouelabbes
📧 abouabdellatif.9@gmail.com

csharp
Copier le code

### Notes:
- Save this as **README.md** in the same directory as your `index.html`.
- This file will be automatically displayed on your GitHub repository 