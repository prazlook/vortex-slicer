# 🌪️ Vortex Slicer - User Manual
**From Zero to First Print: The Official Guide for the Core R-Theta Printer**

Welcome, Pilot. This guide will help you set up the **Vortex Slicer** environment on your machine. Let's get that hardware moving!

---

## 🛠️ Step 1: Environment Setup

  The Vortex Slicer runs on **Python** via **Jupyter Notebook**. This allows for real-time visualization of your 4-axis paths.
  
  ### 1. Install Python & Jupyter
  If you don't have it yet, the easiest way is via **Anaconda** or directly via **pip**:
  ```bash
  pip install notebook
  ```
  ### 2. Install Dependencies
  Vortex requires specific mathematical and graphical libraries to process the 4th axis:
  ```bash
  pip install numpy matplotlib scipy shiny
  ```
## 🚀 Step 2: Installing the Slicer
  ### 1. Navigate on your favorite path with this command: 
  ```bash
  cd <YOUR\FAVORITE\PATH>
  ```
  ### 2. Clone this repository with this command: 
  ```bash
  git clone https://github.com/prazlook/vortex-slicer.git
  ```
  ### 3. In your terminal, navigate to the folder with the cd command and type:
   ```bash
   python -m notebook
   ```
  ### 4. Your browser will open. Click on Vortex_Slicer_Main.ipynb.
  
## Step 3: The Cell-By-Cell Workflow
  ### 1. The slicer is composed of cells. Navigate to this cell : 
  ### 2. Replace the "model_name" variable with the name of the model you will be using. The model name must only contain alphanumeric characters.
  ### 3. Place your stl into the input_models directory. Unless you're rocking an RTX 5090, you’d better keep your mesh under 10,000 KB (unless, of course, you enjoy the smell of a fried GPU or happen to have some eggs to fry today.)
