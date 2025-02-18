^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package demo_nodes_cpp
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.8.0 (2019-09-26)
------------------
* Adding visibility macros to demos (`#381 <https://github.com/ros2/demos/issues/381>`_)
* Demos using composition (`#375 <https://github.com/ros2/demos/issues/375>`_)
* Contributors: Siddharth Kucheria

0.7.6 (2019-05-30)
------------------

0.7.5 (2019-05-29)
------------------
* Update to use new parameter option names (`#355 <https://github.com/ros2/demos/issues/355>`_)
* Contributors: William Woodall

0.7.4 (2019-05-20)
------------------

0.7.3 (2019-05-10)
------------------
* Added the ``parameter_blackboard`` demo to ``demo_nodes_cpp`` to make some tutorials easier. (`#333 <https://github.com/ros2/demos/issues/333>`_)
* Contributors: William Woodall

0.7.2 (2019-05-08)
------------------
* changes to avoid deprecated API's (`#332 <https://github.com/ros2/demos/issues/332>`_)
* Corrected publish calls with shared_ptr signature (`#327 <https://github.com/ros2/demos/issues/327>`_)
* Migrate launch tests to new launch_testing features & API (`#318 <https://github.com/ros2/demos/issues/318>`_)
* Contributors: Michel Hidalgo, William Woodall, ivanpauno

0.7.1 (2019-04-26)
------------------
* Updated to declare parameters. (`#241 <https://github.com/ros2/demos/issues/241>`_)
* Contributors: Shane Loretz

0.7.0 (2019-04-14)
------------------
* Moved away from deprecated rclcpp APIs. (`#321 <https://github.com/ros2/demos/issues/321>`_)
* Added launch along with launch_testing as test dependencies. (`#313 <https://github.com/ros2/demos/issues/313>`_)
* Updated for NodeOptions Node constructor. (`#308 <https://github.com/ros2/demos/issues/308>`_)
* Contributors: Emerson Knapp, Michael Carroll, Michel Hidalgo

0.6.2 (2019-01-15)
------------------

0.6.1 (2018-12-13)
------------------

0.6.0 (2018-12-07)
------------------
* Added semicolons to all RCLCPP and RCUTILS macros. (`#278 <https://github.com/ros2/demos/issues/278>`_)
* Removed parameter node, all nodes take parameter by default now (`#265 <https://github.com/ros2/demos/issues/265>`_)
* Added example of registering custom parameter validation callbacks (`#273 <https://github.com/ros2/demos/issues/273>`_)
* Removed imu_listener node (`#272 <https://github.com/ros2/demos/issues/272>`_)
* Refined demo_nodes_cpp source codes (`#269 <https://github.com/ros2/demos/issues/269>`_)
* Fixed typo in comment (`#268 <https://github.com/ros2/demos/issues/268>`_)
* Removed rosidl deps as this package doesnt generate any messages (`#264 <https://github.com/ros2/demos/issues/264>`_)
* Fixed no return code for main() in several files (`#266 <https://github.com/ros2/demos/issues/266>`_)
* Contributors: Chris Lalancette, Mikael Arguedas, Yutaka Kondo, testkit

0.5.1 (2018-06-28)
------------------

0.5.0 (2018-06-27)
------------------
* Reduced the publishing of the allocator_tutorial to 100Hz. (`#257 <https://github.com/ros2/demos/issues/257>`_)
  * Signed-off-by: Chris Lalancette <clalancette@openrobotics.org>
* Removed the now obsolete ros2param executable, use ``ros2 param`` instead. (`#251 <https://github.com/ros2/demos/issues/251>`_)
* Fixed a potiential nullptr dereference issue in ``demo_nodes_cpp``. (`#242 <https://github.com/ros2/demos/issues/242>`_)
* Added demo nodes which use the new serialized message typed publishers and subscriptions. (`#185 <https://github.com/ros2/demos/issues/185>`_)
* Added a new-style launch file for the talker and listener demo nodes, called ``talker_listener.launch.py``. (`#244 <https://github.com/ros2/demos/issues/244>`_)
* Updated launch files to account for the "old launch" getting renamespaced as ``launch`` -> ``launch.legacy``. (`#239 <https://github.com/ros2/demos/issues/239>`_)
* Updated to handle refactor of the ``ParameterVariant`` class. (`#237 <https://github.com/ros2/demos/issues/237>`_)
* Updated to account for the fact that the ROS Parameter services starts automatically now. (`#236 <https://github.com/ros2/demos/issues/236>`_)
* Added some uses of parameter arrays to the ``set_and_get_parameters`` demo. (`#235 <https://github.com/ros2/demos/issues/235>`_)
* Contributors: Chris Lalancette, Dirk Thomas, Karsten Knese, Mikael Arguedas, Shane Loretz, William Woodall, cshen
