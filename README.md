# Digital Clock Web Application  

This project is a **Digital Clock** implemented using **HTML**, **CSS**, and **JavaScript**. The clock dynamically updates every second and displays the current time in a visually appealing format.

---

## Features  

- **Real-Time Clock:**  
  Continuously updates to display the current time (hours, minutes, seconds).  

- **12-Hour Format with AM/PM:**  
  Uses a standard 12-hour clock format to make it user-friendly.  

- **Minimal Design:**  
  - Centered on the screen for clean aesthetics.  
  - Glowing green text on a black background for a futuristic, sleek look.

---

## Technologies Used  

1. **HTML:** For structuring the application.  
2. **CSS:** For styling the clock and creating the glowing green text effect.  
3. **JavaScript:** For fetching and updating the time dynamically.  

---

## How It Works  

1. **HTML Structure:**  
   Contains a `<div>` element with an ID `Digitalclock`, which serves as the container for the time display.  

2. **CSS Styling:**  
   - The body has a black background.  
   - The clock text is centered using `position: absolute` and `transform`.  
   - Glowing green effect is applied with the `rgb(131, 246, 147)` color.

3. **JavaScript Logic:**  
   - Fetches the current time using `new Date()`.  
   - Formats the time to always show two digits for hours, minutes, and seconds.  
   - Updates the clock every second using `setTimeout`.  

---

## How to Use  

1. Copy the code into an `.html` file.  
2. Open the file in any modern web browser.  
3. The digital clock will automatically display the current time and update every second.  

---

## Sample Output  

### Time Display:  
```
09:45:27 AM
```

---

## Future Enhancements  

- Add a **toggle button** to switch between 12-hour and 24-hour formats.  
- Include **date display** below the clock.  
- Enhance styling with animations or customizable themes.  

---

Feel free to fork, modify, and enhance this project! 😊  
