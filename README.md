<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=165&section=header&text=Iron%20Mind&fontSize=38&fontColor=ffffff&fontAlignY=36&desc=Fitness%20Exercise%20Guide%20and%20BMI%20Calculator&descAlignY=58&descSize=15" alt="Iron Mind fitness website" width="100%" />

**A multi-page fitness website with muscle-group exercise videos and a browser-based BMI calculator.**

<img src="https://img.shields.io/badge/HTML5-Multi--Page%20Site-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-Responsive%20Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-BMI%20Calculator-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />

</div>

## Overview

Iron Mind is a static fitness website organized around targeted exercise guidance. Separate pages cover shoulders, arms, legs, chest, and abdominal exercises, using locally stored demonstration videos. A JavaScript BMI calculator accepts weight and height and displays the resulting category in the browser.

## Features

- Dedicated workout pages for five muscle groups.
- Locally embedded MP4 exercise demonstrations.
- Navigation shared across the main fitness pages.
- BMI calculation from kilograms and centimeters.
- BMI categories for underweight, normal weight, overweight, and obese ranges.
- Branded landing page, contact form layout, and local logo/media assets.

## Project Structure

```text
Iron-Mind/
├── homepage.html          # Landing page and navigation
├── shoulders.html         # Shoulder exercises
├── arms.html              # Arm exercises
├── legs.html              # Leg exercises
├── chest.html             # Chest exercises
├── abs.html               # Abdominal exercises
├── bmi-calculator.html    # Client-side BMI calculator
├── logo.png
├── runningnew.jpg
└── *.mp4                  # Exercise demonstration videos
```

## Run Locally

No package installation or application server is required.

```powershell
git clone https://github.com/FarisDosani/Iron-Mind.git
cd Iron-Mind
Start-Process .\homepage.html
```

You can also open `homepage.html` directly in a modern browser. Keep the HTML pages, images, logo, and MP4 files together so relative asset paths continue to work.

## Notes

- BMI output is informational and is not medical advice.
- The contact form is a visual frontend form with no server-side submission handler.
- Exercise videos are repository assets; no additional download step is required.

---

<div align="center">

<a href="https://github.com/FarisDosani/Iron-Mind">View repository</a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=80&section=footer" alt="" width="100%" />

</div>
