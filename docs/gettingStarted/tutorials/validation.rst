
Validation Matrix
=================

.. _validation_matrix:

This section provides validation information for robosapiensIO toolkit features across different example implementations and use cases.

.. |ok| image:: ../../assets/ok.png
   :height: 2ex
.. |nok| image:: ../../assets/_nok.png
   :height: 2ex
.. |uk| image:: ../../assets/thinking.png
   :height: 2ex

Feature Validation Matrix
-------------------------

The following matrix shows the validation status of robosapiensIO features across the use cases finalized in D5.4:

.. csv-table:: Feature Validation Status
   :file: validation.csv
   :header-rows: 1
   :class: longtable
   :widths: 12, 16, 22, 12, 12, 12, 12

Legend
------

* |ok| **Supported/Working**: Feature is fully implemented and tested
* |nok| **Not Supported**: Feature is not yet implemented, not working, or not used in this project
* |uk| **Under Investigation**: Feature status is being evaluated

Use Cases
---------

Each column merges all example projects and versions of the same use case: a feature is marked |ok| if it is supported in at least one of them.

* **HelloWorld (TurtleBot4 LiDAR occlusion)**: Merges the hello world, hello worldv2 and Distributed Deployment examples with the TurtleBot 4 simulator (UAntwerp) and the final TurtleBot4 LiDAR occlusion case (AU)
* **Ship motion prediction (NTNU)**: Ship motion prediction, merging the earlier version and the final D5.4 version (in-place LSTM retraining with a separate Legitimate stage, connected to K-Sim)
* **Robot arm screw assistant (DTI)**: Self-adaptive detector-model switching under changing lighting, deployed on simulation, light-box rig and shop-floor cell
* **Multi robot human detection (PAL)**: Fleet-level adaptation with a ROS2 boundary adapter

Testing Framework
-----------------

All examples and tutorials are validated using our continuous integration pipeline to ensure they work as expected.

.. note::
   For detailed validation results, please refer to the project's CI/CD pipeline results.
