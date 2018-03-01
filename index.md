
# Workspace Aware Online Grasp Planning

#### Iretiayo Akinola, Jacob Varley, Boyuan Chen  and Peter Allen


![Visualization of cross sections of the precomputed reachable space for a Fetch Robot and Staubli Arm with Barrett Hand.](./images/fetch_staubli.pdf)


### Abstract
This work provides a framework for a workspace aware online grasp planner. This framework greatly improves the performance of standard online grasp planning algorithms by incorporating a notion of reachability into the online grasp planning process.  Offline, a database of hundreds of thousands of unique end-effector poses were queried for feasability.  At runtime, our grasp planner uses this database to bias the hand towards reachable end-effector configurations. The bias keeps the grasp planner in accessible regions of the planning scene so that the resulting grasps are tailored to the situation at hand. This results in a higher percentage of reachable grasps, a higher percentage of successful grasp executions, and a reduced planning time. We also present experimental results using simulated and real environments.


### Links

- Paper
- Bibtex
- Code for Reachability space generation
- Reachability Space Data for Fetch Robot and Staubli-Barrett Hand


### Video

[![Reachability_Aware_Grasping_Video](https://img.youtube.com/vi/7OqQOIV26RY/0.jpg)](https://youtu.be/7OqQOIV26RY)
