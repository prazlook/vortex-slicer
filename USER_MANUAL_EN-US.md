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
  ### 1. 
  The slicer is composed of cells. Navigate to this cell : 
  <img width="1911" height="909" alt="image" src="https://github.com/user-attachments/assets/6aacc275-6580-4913-a06a-f3343d4e4ef3" />
  
  ### 2. 
  Replace the "model_name" variable with the name of the model you will be using. The model name must only contain alphanumeric characters.
  <img width="1190" height="556" alt="image" src="https://github.com/user-attachments/assets/8caffcdc-470b-49f7-a096-c0f96f82aa5d" />

  ### 4. 
  Place your stl into the input_models directory. Unless you're rocking an RTX 5090, you’d better keep your mesh under 10,000 KB (unless, of course, you enjoy the smell of a fried GPU or happen to have some eggs to fry today.)<img width="685" height="392" alt="image" src="https://github.com/user-attachments/assets/3ec2b435-fbde-478e-86e8-84d09635f81e" />

  ### 5. 
  Click anywhere into the cell to select it.
  <img width="87" height="142" alt="image" src="https://github.com/user-attachments/assets/8e4cdfe3-946e-4387-8bc2-b9f1cdc02a74" />
  (*This is some stupid-ass sh!t, but since you wittle babies need a wittle image for every single step, here you go.)
  
  ### 6. 
  nocomment<img width="465" height="126" alt="image" src="https://github.com/user-attachments/assets/d0cfa122-5bfe-4738-ba83-240bd3fd475e" />
  ### 7. 
  For the noooooooooooooooooooooooooooooooooooooooooooooooooooooobs, DON'T proceed to the next step while the kernel is running (tiny, too tiny asterisk) (Any subsequent grievances originating from individuals who failed to comply with the aforementioned protocols shall be met with an absolute plea in bar. In other words: If you didn't listen, don't f𝓊cking come crying to me.)
  <img width="370" height="199" alt="image" src="https://github.com/user-attachments/assets/96897303-01a6-45d6-8f3b-adbd45de236b" />


