# _Real-Time-Memory-Allocation-Tracker_
Real-Time Memory Allocation Tracker is an interactive tool that monitors and manages memory allocation dynamically using best-fit and worst-fit strategies.
It provides real-time visualization of memory usage, fragmentation, and system performance for efficient allocation tracking. 
Key Features:
1. Dynamic Allocation: Users request memory; the system assigns optimal blocks using Best-Fit or Worst-Fit strategies.

2. Smart Deallocation: Freeing memory merges adjacent blocks to minimize fragmentation, updating visualization in real-time.

3. Live Memory Visualization: A dynamic bar graph displays allocated (red) and free (green) memory, with labeled block IDs.

4. Fragmentation Insights: Tracks internal (unused space) and external (scattered free blocks) fragmentation for efficiency analysis.

5. Strategy Comparison: Evaluates Best-Fit vs. Worst-Fit by running allocation cycles and selecting the optimal method.

6. System Monitoring: Displays real-time CPU & RAM usage, highlighting top memory-consuming processes with psutil.
