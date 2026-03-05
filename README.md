# TouchPanelTester – User Guide

TouchPanelTester is a tool used to verify the accuracy and functionality of touch panels.

---

## 1. Starting the Application

1. Connect the touch panel and controller to the computer.
2. Open the TouchPanelTester folder.
3. Double-click **TouchPanelTester.exe** to start the application.

---

## 2. Selecting the Display

When the application starts:

1. Select the **Touch Device** that corresponds to the touch panel being tested.
2. Select the **Controller Brand** of the controller of the touch panel that is being tested.
3. Select the **Display/Monitor** that corresponds to the touch panel being tested.
4. Click **Map** to save and confirm the settings.
5. Select the corresponding minotor size that you are testing.
6. Choose a test to perform.

The test window will open on the selected display.

---

## 3. Running the Accuracy Test

The application will show **target points** on the screen.

For each point:

1. Touch the center of the displayed target.
2. Keep your finger steady for a moment.
3. Move to the next target when it appears.

The system records the position of your touch and compares it to the expected location.

---

## 4. Completing the Test

After all points are tested:

* The application will display the **test results**.
* Each tested point shows:

  * Expected position
  * Actual touch position
  * Deviation (difference)
  * Pass/Fail status

Points that fall outside the allowed tolerance will be marked as **Fail**.

---

## 5. Interpreting the Results

The results table provides information about touch accuracy.

**Pass**

* The touch point is within the allowed tolerance.

**Fail**

* The touch point deviates beyond the acceptable range.

---

## 6. Running the Touch Area Test

The **Touch Area Test** verifies that the entire surface of the touch panel responds to touch input.

During the test, the screen becomes a **drawing canvas**.

1. Place your finger on the screen.
2. Slowly move your finger across the display.
3. Cover the entire touch surface.

As you move your finger, the application draws the path of your touch.

The goal is to **cover all areas of the screen**, including:

* the center
* the edges
* all four corners

---

## 7. Observing Touch Coverage

While moving your finger across the screen:

* The drawn trace should **follow your finger smoothly**.
* The line should appear **continuously without interruptions**.

If certain areas of the screen do not produce a trace, this may indicate a **touch detection issue**.

---

