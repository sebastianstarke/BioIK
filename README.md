BioIK Asset for Unity3D
======================================================
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/title.png">

Download
------------
The source code for this project in Unity3D (C#) can be obtained via: https://www.assetstore.unity3d.com/en/#!/content/67819

Description
------------
This project was started as part of my M.Sc. thesis, and later continued as a research associate at the University of Hamburg.
The algorithm solves the inverse kinematics problem on generic kinematic geometries by means of memetic evolutionary computation - combining genetic algorithms, particle swarm optimisation and the L-BFGS-B algorithm for nonlinear gradient-based optimisation. For information, see the graph below.

<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/cycle.png" width="100%">

The following pictures demonstrate the performance of the algorithm in application scenarious on different robot and character geometries. The typical optimisation time for randomly sampled and reachable joint configurations is between 1-10ms, which is significantly faster than related evolutionary methods, along with higher robustness and scalability than pure gradient-based techniques. The method can solve multiple kinematic chains simultaneously, and fully incorporates joint limits and rotational as well as translational joint types. Concurrently, collision-avoidance and functional couplings between joints as well as some other goals can be considered via adding predefined objectives as terms for the global cost function.
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/1.png" width="100%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/2.png" width="33%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/3.png" width="33%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/4.png" width="33%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/5.png" width="100%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/7.png" width="100%">
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/8.png" width="100%">

The table below shows the resulting performance values compared to related methods for numerical IK.
<img src ="https://github.com/sebastianstarke/BioIK/blob/master/images/eval.png" width="100%">

The research was published at several scientific conferences, including IEEE ROBIO 2016, IEEE CEC 2017 and IEEE IROS 2017, so I would be glad if you reference it in case of using it for academic work.

For any questions you might have or bugs you find, feel free to contact me! I am happy to help and to improve the software.

