# canny-edge-detection


---

## AIM

1. Loaded a nature image in grayscale
2. Applied Canny edge detection with 3 different parameter settings
3. Compared results side by side
4. Created interactive mode with sliders for real-time tuning
5. Saved edge detection outputs as image files

---

## REQUIREMENTS

**Software:**
- Python 3.6 or higher

**Libraries:**
- OpenCV (cv2)
- NumPy
- Matplotlib

**Hardware:**
- Any computer (basic specs work fine)

**Input:**
- One image file named `nature.png` in the same folder

**Output:**
- Three edge detection result images (JPG format)

---

## QUICK SETUP

```
pip install opencv-python numpy matplotlib
```

Place `butterfly.png` in your project folder

Run the Python script

---

## PARAMETERS TESTED

| Setting | Low | High | Result |
|---------|-----|------|--------|
| Default | 50 | 150 | Balanced edges |
| Lower | 30 | 100 | More edges, some noise |
| Higher | 100 | 200 | Fewer edges, cleaner |

---

## OBSERVATIONS

- Lower thresholds capture more details but introduce noise
- Higher thresholds give cleaner results but miss weak edges
- Best ratio is high:low = 3:1
- Nature images work best with lower thresholds (40-120 range)
