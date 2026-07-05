# Peer-Tutoring-Matcher
An intermediate-to-pro level Python Tkinter desktop administrative dashboard engineered for academic departments to optimize peer tutoring programs. The system integrates automated conditional pairing workflows with standalone dynamic queue registries to handle data allocation conflicts in real-time.

##  Core Interface Architecture
The application layout uses an optimized two-tab structure using `ttk.Notebook` architectures to split administrative data processes:

###  1. Match Dashboard Tab
A visual overview control deck containing split component structures:
* **Active Pairing Registry:** A master `ttk.Treeview` layout logging successfully validated tutor-student matches.
* **Side-by-Side Split Queues:** Independent, synchronized left and right table blocks mapping unmatched students and vacant tutors in parallel matrix windows for fast visual scanning.

###  2. Registration Management Tab
A structured configuration panel built within clean label frame containment fields:
* Integrated dropdown menus (`ttk.Combobox`) locking structured role types and subject specialization rules.
* Case-insensitive validation scripts parsing operational timelines smoothly.

##  How the Matching System Works

###  Real-Time Auto-Matching (Dynamic Pass)
Upon triggering `Save & Check Match`, the application checks active records:
* If a new **Student** profile commits, the script loops over the unmatched tutors data frame instantly.
* If a target slot matches on both **Academic Subject** and **Availability Time**, an immediate link is locked and logged into `self.matches`.
* **Conflict Prevention:** Once bound, both references are automatically omitted from their respective queues to guarantee absolute double-booking protection.

###  Full Optimization Refactor
Clicking the **Run Full Optimization Matcher** button triggers a complete global reset. It flushes old pairings, creates tracking vectors, and re-runs multi-pass logical checks across all data streams from scratch to achieve the absolute maximum capacity of available matches.

##  Installation & Local Execution

### System Requirements
* Python 3.8 or higher.
* Pre-bundled standard `tkinter` UI development environments.

### Execution Command Pattern
1. Clone this repository locally to your directory:
   ```bash
   git clone [https://github.com/wardazaheer80/campus-peer-tutoring-system.git](https://github.com/wardazaheer80/campus-peer-tutoring-system.git)
```
Open your shell context inside the folder and run:

```bash
python main.py
```
## Application Screenshots

### Main Dashboard 
<img width="1050" height="865" alt="Screenshot 2026-07-05 052453" src="https://github.com/user-attachments/assets/26a2e054-e5d5-4d84-87e0-ca63a9b96dfd" />
<img width="1920" height="1020" alt="Screenshot 2026-07-05 065419" src="https://github.com/user-attachments/assets/79836b34-1241-43de-b742-262f8cb64713" />
<img width="1920" height="1020" alt="Screenshot 2026-07-05 065732" src="https://github.com/user-attachments/assets/23a8c51b-ea43-49dd-8adf-1d0a60b952b2" />


### Live Evaluation Result 

<img width="1920" height="1020" alt="Screenshot 2026-07-05 070754" src="https://github.com/user-attachments/assets/0fa10eb2-f10c-4a7a-b2f1-399ffdab3457" />



