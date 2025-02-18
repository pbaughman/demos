^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package lifecycle
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.8.0 (2019-09-26)
------------------
* Fix lifecycle_service_client namespace (`#369 <https://github.com/ros2/demos/issues/369>`_)
* Contributors: Cameron Evans

0.7.6 (2019-05-30)
------------------

0.7.5 (2019-05-29)
------------------
* Update asciinema recordings (`#360 <https://github.com/ros2/demos/issues/360>`_)
* Use rate instead of thread::sleep to react to Ctrl-C (`#348 <https://github.com/ros2/demos/issues/348>`_)
* Contributors: Dirk Thomas, Karsten Knese

0.7.4 (2019-05-20)
------------------
* Add lifecycle rostest (`#336 <https://github.com/ros2/demos/issues/336>`_)
* Contributors: Michel Hidalgo

0.7.3 (2019-05-10)
------------------

0.7.2 (2019-05-08)
------------------
* changes to avoid deprecated API's (`#332 <https://github.com/ros2/demos/issues/332>`_)
* Corrected publish calls with shared_ptr signature (`#327 <https://github.com/ros2/demos/issues/327>`_)
* Contributors: William Woodall, ivanpauno

0.7.1 (2019-04-26)
------------------

0.7.0 (2019-04-14)
------------------
* Updated for NodeOptions Node constructor. (`#308 <https://github.com/ros2/demos/issues/308>`_)
* Contributors: Michael Carroll

0.6.2 (2019-01-15)
------------------
* Added readme.rst (`#300 <https://github.com/ros2/demos/issues/300>`_)
* Contributors: Karsten Knese

0.6.1 (2018-12-13)
------------------

0.6.0 (2018-12-07)
------------------
* Cleaned up lifecycle demo (`#283 <https://github.com/ros2/demos/issues/283>`_)
* Updated for refactoring in rclcpp (`#276 <https://github.com/ros2/demos/issues/276>`_)
* Added semicolons to all RCLCPP and RCUTILS macros. (`#278 <https://github.com/ros2/demos/issues/278>`_)
* Fixed typo in comment (`#270 <https://github.com/ros2/demos/issues/270>`_)
* Contributors: Chris Lalancette, Karsten Knese, Yutaka Kondo

0.5.1 (2018-06-28)
------------------

0.5.0 (2018-06-27)
------------------
* Converted launch files to the new launch style. (`#262 <https://github.com/ros2/demos/issues/262>`_)
* Updated to support remapping arguments to python nodes by passing unused arguments to rclpy from argparse. (`#252 <https://github.com/ros2/demos/issues/252>`_)
* Updated to handle change in signature to ``get_service_name``. (`#245 <https://github.com/ros2/demos/issues/245>`_)
* Updated launch files to account for the "old launch" getting renamespaced as ``launch`` -> ``launch.legacy``. (`#239 <https://github.com/ros2/demos/issues/239>`_)
* Updated service client demos to handle multiple requests. (`#228 <https://github.com/ros2/demos/issues/228>`_)
* Contributors: Geoffrey Biggs, Kevin Allen, Shane Loretz, William Woodall, dhood
