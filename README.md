# Raj's Robot Rentals

Welcome to **Raj's Robot Rentals**, a web application designed to calculate rental costs for different robot models. This interactive app allows users to switch between models, set rental durations, and view the updated cost dynamically.

---

## **Features**

1. **Robot Models**:
   - Two models available for booking:
     - **Model XYZ**: $100 per day.
     - **Model CPRG**: $213 per day.

2. **Dynamic Cost Calculation**:
   - Automatically updates the total rental cost when:
     - Switching between robot models.
     - Changing the rental duration.

3. **Interactive Buttons**:
   - **Switch Model**: Toggle between "Model XYZ" and "Model CPRG."
   - **Change Duration**: Enter a custom rental duration to calculate the cost.

4. **Responsive and Styled Design**:
   - Retro-inspired styling using the **Press Start 2P** font.
   - Bright, bold colors and hover effects for buttons.
   - Fixed-width layout for a clean and centered design.

---

## **How to Use**

1. **Access the Application**:
   - Open the `index.html` file in your web browser.

2. **View Robot Options**:
   - Explore the available robot models and their daily rental costs.

3. **Calculate Rental Costs**:
   - Click **Switch Model** to change the selected robot.
   - Click **Change Duration** to enter a new rental duration.
   - The updated cost is displayed dynamically on the page.

4. **Enjoy the Experience**:
   - Hover over the buttons for a visual interaction.
   - See live cost updates as you adjust your selections.

---

## **Technical Details**

### **JavaScript Logic**
1. **Variables**:
   - Tracks the current model (`modelName`) and duration (`duration`).

2. **Recalculate Function**:
   - Calculates the cost dynamically based on the selected model and duration.

3. **Button Logic**:
   - **Switch Model**: Toggles between the robot models and recalculates the cost.
   - **Change Duration**: Prompts the user for a new duration, updates the display, and recalculates the cost.

### **CSS Styling**
- **Typography**:
  - Uses the **Press Start 2P** font for a retro look.
- **Buttons**:
  - Bright green default color with hover effects turning orange.
- **Layout**:
  - Fixed-width (840px) centered design for a clean and consistent layout.
