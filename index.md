
# Workspace Aware Online Grasp Planning

#### Iretiayo Akinola, Jacob Varley, Boyuan Chen  and Peter Allen



![Workspace Aware Online Grasping Framework.](./images/Full_Pipeline.png)



### Abstract
This work provides a framework for a workspace aware online grasp planner. This framework greatly improves the performance of standard online grasp planning algorithms by incorporating a notion of reachability into the online grasp planning process.  Offline, a database of hundreds of thousands of unique end-effector poses were queried for feasability.  At runtime, our grasp planner uses this database to bias the hand towards reachable end-effector configurations. The bias keeps the grasp planner in accessible regions of the planning scene so that the resulting grasps are tailored to the situation at hand. This results in a higher percentage of reachable grasps, a higher percentage of successful grasp executions, and a reduced planning time. We also present experimental results using simulated and real environments.

<hr />

### Video

<iframe width="854" height="480" src="https://www.youtube.com/embed/smuwr-jV0wA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


<hr />
### Links

- Paper: This work was submitted to IROS 2018. Arxiv link [here](https://arxiv.org/abs/1806.11402)
- Top level workspace [here](http://github.com/CRLab/reachability_aware_grasping_ws.git)
- Code for Reachability space generation [here](http://github.com/CRLab/reachability_space_generation.git)
- Reachability Space Data for [Fetch Robot](http://github.com/CRLab/fetch_reachability_config.git) and [Staubli-Barrett Hand](https://github.com/CRLab/staubli_barrett_reachability_config.git)


![Visualization of cross sections of the precomputed reachable space for a Fetch Robot and Staubli Arm with Barrett Hand.](./images/fetch_staubli.png)
