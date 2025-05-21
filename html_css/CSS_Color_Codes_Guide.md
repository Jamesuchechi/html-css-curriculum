### CSS Color Codes & Guide  

CSS allows you to define colors in multiple formats. Below is a guide on how to use them effectively.

---

## **1. Color Formats in CSS**
### **1.1 Named Colors**  
CSS provides **140+ named colors** that you can use directly. Examples:  
```css
color: red;
color: blue;
color: green;
color: black;
color: white;
```

### **1.2 Hexadecimal (Hex) Colors**  
A 6-digit (or 3-digit shorthand) hex code represents Red, Green, and Blue (RGB) values.  
- **Format:** `#RRGGBB` (or `#RGB` for shorthand)  
- **Example:**  
  ```css
  color: #ff0000; /* Red */
  color: #00ff00; /* Green */
  color: #0000ff; /* Blue */
  color: #fff;    /* White (shorthand for #ffffff) */
  ```

### **1.3 RGB (Red, Green, Blue) Colors**  
- **Format:** `rgb(red, green, blue)`  
- **Example:**  
  ```css
  color: rgb(255, 0, 0); /* Red */
  color: rgb(0, 255, 0); /* Green */
  color: rgb(0, 0, 255); /* Blue */
  ```

### **1.4 RGBA (RGB with Alpha - Transparency)**  
- **Format:** `rgba(red, green, blue, alpha)`  
- **Example:**  
  ```css
  color: rgba(255, 0, 0, 0.5); /* Semi-transparent Red */
  ```

### **1.5 HSL (Hue, Saturation, Lightness) Colors**  
- **Format:** `hsl(hue, saturation, lightness)`  
- **Example:**  
  ```css
  color: hsl(0, 100%, 50%); /* Red */
  color: hsl(240, 100%, 50%); /* Blue */
  ```

### **1.6 HSLA (HSL with Alpha - Transparency)**  
- **Format:** `hsla(hue, saturation, lightness, alpha)`  
- **Example:**  
  ```css
  color: hsla(0, 100%, 50%, 0.5); /* Semi-transparent Red */
  ```

---

## **2. Background Color**
```css
background-color: lightblue;
background-color: #ffcc00;
background-color: rgb(200, 200, 200);
background-color: rgba(0, 0, 0, 0.8);
```

---

## **3. Text Color**
```css
p {
  color: navy;
}
```

---

## **4. Border Color**
```css
border: 2px solid red;
border-color: #333;
```

---

## **5. Transparent Colors**
```css
background-color: transparent;
```

---

## **6. Gradient Colors**
### **6.1 Linear Gradient**
```css
background: linear-gradient(to right, red, blue);
```

### **6.2 Radial Gradient**
```css
background: radial-gradient(circle, red, yellow, green);
```

---

## **7. CSS Color Variables**
```css
:root {
  --primary-color: #3498db;
}
button {
  background-color: var(--primary-color);
}
```

---

### 🎨 **Tip:** Use [CSS Color Picker](https://www.w3schools.com/colors/colors_picker.asp) to find colors easily!

Would you like an interactive example? 🚀