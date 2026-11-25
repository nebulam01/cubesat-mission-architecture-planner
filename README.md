# 🛰️ CubeSat Mission Architecture Planner

An interactive CubeSat mission design tool I built in Google Colab using `Gradio`, `NumPy`, `Pandas`, and `Matplotlib` to frame a mission around one measurable question, select a payload sensor, model daily data generation vs. ground-station downlink capacity, and define clear success metrics.

## ✨ Key Features
- **Single Measurable Question Framing:** Centers each CubeSat profile around a specific, testable scientific or engineering question rather than open-ended goals.
- **Payload & Orbit Trade-Offs:** Covers 2U, 3U, and 6U mission profiles with orbital period calculation, daily orbit count, sensor type, and ground-pass downlink parameters.
- **Data Budget & Quality Plots:** Visualizes cumulative generated vs. downlinked data volume (GB) and orbit-to-orbit observation quality against a success threshold.
- **Full-Width Mission Summary & Matrix:** Presents the measurable question, sensor choice, end-to-end data plan, and success metric in a wide, easy-to-read layout.

## 🛠️ Tech Stack
- **Environment:** Google Colab
- **Analysis, Plotting & UI:** Python, `Gradio`, `NumPy`, `Pandas`, `Matplotlib`

## ⚙️ How to Run the Project
1. **Open in Google Colab:**
   - Upload the notebook or script to Google Colab (`colab.research.google.com`).
2. **Run & Launch:**
   - Run the cell to install `gradio`, `numpy`, `pandas`, and `matplotlib` and launch the dashboard.
3. **Configure & Generate:**
   - Choose a CubeSat mission profile, set ground-station passes/day, downlink MB/pass, and evaluation days, then click **Generate CubeSat Mission Plan**.

## 📌 Scope & Assumptions
- Intended for early-stage mission architecture framing and educational systems engineering exploration, not full flight-qualification mass/power/link budgets.
- Uses two-body orbital period approximations and parametric payload/downlink assumptions to evaluate data-budget margins.
