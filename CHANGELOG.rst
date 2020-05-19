^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rmw
^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2020-05-12)
------------------
* Remove MANUAL_BY_NODE liveliness API (`#227 <https://github.com/ros2/rmw/issues/227>`_)
* Improved Quality declarations (`#225 <https://github.com/ros2/rmw/issues/225>`_)
* Quality declarations for rmw and rmw_implementation_cmake (`#205 <https://github.com/ros2/rmw/issues/205>`_)
* Add tests for untested public functionality (`#203 <https://github.com/ros2/rmw/issues/203>`_)
* Contributors: Alejandro Hernández Cordero, Ivan Santiago Paunovic, Stephen Brawner

0.9.0 (2020-04-24)
------------------
* Delete superfluous empty line (`#222 <https://github.com/ros2/rmw/issues/222>`_)
* Fix linter warning (`#224 <https://github.com/ros2/rmw/issues/224>`_)
* Rename rosidl_message_bounds_t (`#223 <https://github.com/ros2/rmw/issues/223>`_)
* Adding doxygen documentation and READMEs to packages (`#204 <https://github.com/ros2/rmw/issues/204>`_)
* Service timestamps (`#217 <https://github.com/ros2/rmw/issues/217>`_)
* Add API for taking a sequence of messages (`#212 <https://github.com/ros2/rmw/issues/212>`_)
* Add timestamps to message info (`#214 <https://github.com/ros2/rmw/issues/214>`_)
* Add build dep on rosidl_runtime_c to work with CMake < 3.13 (`#221 <https://github.com/ros2/rmw/issues/221>`_)
* Fix missing target dependency on rosidl_runtime_c (`#220 <https://github.com/ros2/rmw/issues/220>`_)
* Export targets in addition to include directories / libraries (`#218 <https://github.com/ros2/rmw/issues/218>`_)
* Document destroy_node may assume correct destruction order (`#216 <https://github.com/ros2/rmw/issues/216>`_)
* security-context -> enclave (`#211 <https://github.com/ros2/rmw/issues/211>`_)
* Rename rosidl_generator_c namespace to rosidl_runtime_c (`#213 <https://github.com/ros2/rmw/issues/213>`_)
* Added the right dependency rosidl runtime c instead of rosidl generator c (`#198 <https://github.com/ros2/rmw/issues/198>`_)
* Use one participant per context API changes (`#189 <https://github.com/ros2/rmw/issues/189>`_)
* Add comment about RMW_RET_UNSUPPORTED for loaned_message. (`#208 <https://github.com/ros2/rmw/issues/208>`_)
* Support for ON_REQUESTED_INCOMPATIBLE_QOS and ON_OFFERED_INCOMPATIBLE_QOS events (`#193 <https://github.com/ros2/rmw/issues/193>`_)
* Move rmw\_*_event_init() functions to rmw_implementation (`#202 <https://github.com/ros2/rmw/issues/202>`_)
* Rename rmw_topic_endpoint_info_array `count` to `size`, and initialize it (`#196 <https://github.com/ros2/rmw/issues/196>`_)
* Code style only: wrap after open parenthesis if not in one line (`#195 <https://github.com/ros2/rmw/issues/195>`_)
* Update development version after merging `#186 <https://github.com/ros2/rmw/issues/186>`_ (`#194 <https://github.com/ros2/rmw/issues/194>`_)
* Adding required structs and methods to get a list  of publishers or subscribers with their respective qos (`#186 <https://github.com/ros2/rmw/issues/186>`_)
* Contributors: Alejandro Hernández Cordero, Dirk Thomas, Ingo Lütkebohle, Ivan Santiago Paunovic, Jaison Titus, Karsten Knese, Miaofei Mei, Michael Carroll, Mikael Arguedas, Shane Loretz, William Woodall, Stephen Brawner, Tomoya Fujita

0.8.1 (2019-10-23)
------------------
* Use return_loaned_message_from (`#192 <https://github.com/ros2/rmw/issues/192>`_)
* Add function to enable localhost communication only from env var (`#190 <https://github.com/ros2/rmw/issues/190>`_)
* Zero copy api (`#185 <https://github.com/ros2/rmw/issues/185>`_)
* Add call to bump dev version to the upcoming version 0.8.1 (`#191 <https://github.com/ros2/rmw/issues/191>`_)
* Add pub/sub option structures to support rmw specific payload feature (`#187 <https://github.com/ros2/rmw/issues/187>`_)
* Contributors: Brian Marchi, Dirk Thomas, Karsten Knese, William Woodall

0.8.0 (2019-09-24)
------------------
* Added specific return type for non existent node (`#182 <https://github.com/ros2/rmw/issues/182>`_)
* Added function for getting clients by node (`#179 <https://github.com/ros2/rmw/issues/179>`_)
* Added get_actual_qos() feature to subscriptions (`#177 <https://github.com/ros2/rmw/issues/177>`_)
* Added ``RMW_QOS_POLICY_LIVELINESS_UNKNOWN`` enum (`#175 <https://github.com/ros2/rmw/issues/175>`_)
* Contributors: Jacob Perron, M. M, ivanpauno

0.7.1 (2019-05-08)
------------------

* Implement QoS: liveliness, deadline, lifespan (`#171 <https://github.com/ros2/rmw/issues/171>`_)
* Rmw preallocate (`#160 <https://github.com/ros2/rmw/issues/160>`_)
* Add new QoS policy data types to rmw (`#173 <https://github.com/ros2/rmw/issues/173>`_)
* Contributors: M. M, Michael Carroll, Ross Desmond

0.7.0 (2019-04-13)
------------------
* Add function to get publisher actual qos settings (`#169 <https://github.com/ros2/rmw/issues/169>`_)
* fix checking boolean variable which might contain a string (`#165 <https://github.com/ros2/rmw/issues/165>`_)
* change parameter events to use KEEP_LAST (`#162 <https://github.com/ros2/rmw/issues/162>`_)
* Fix typo error (`#164 <https://github.com/ros2/rmw/issues/164>`_)
* pass context to wait set, and provide fini function for context (`#163 <https://github.com/ros2/rmw/issues/163>`_)
* minor notes explaining rmw_qos_profile_t (`#156 <https://github.com/ros2/rmw/issues/156>`_)
* Contributors: Dirk Thomas, Lalit Begani, Mike Lautman, William Woodall, ivanpauno

0.6.1 (2018-12-06)
------------------
* Add node graph functions (`#158 <https://github.com/ros2/rmw/issues/158>`_)
* refactor init to allow options to be passed and to not be global (`#154 <https://github.com/ros2/rmw/issues/154>`_)
* Methods to retrieve matched counts on publisher and subscriber (`#155 <https://github.com/ros2/rmw/issues/155>`_)
* use uint8_t instead of char for serialized message (`#161 <https://github.com/ros2/rmw/issues/161>`_)
* Contributors: Karsten Knese, Michael Carroll, Ross Desmond, William Woodall

0.6.0 (2018-11-16)
------------------
* use new error handling API (`#153 <https://github.com/ros2/rmw/issues/153>`_)
* Add semicolons to RCLCPP and RCUTILS macros. (`#150 <https://github.com/ros2/rmw/issues/150>`_)
* Include node namespaces in get_node_names() (`#148 <https://github.com/ros2/rmw/issues/148>`_)
* add missing doc for parameter (`#149 <https://github.com/ros2/rmw/issues/149>`_)
* rcutils_serialized_message -> rcutils_char_array (`#146 <https://github.com/ros2/rmw/issues/146>`_)
* rmw serialized to rcutils serialized (`#145 <https://github.com/ros2/rmw/issues/145>`_)
* rcutil -> rcutils (`#147 <https://github.com/ros2/rmw/issues/147>`_)
* get serialization format (`#143 <https://github.com/ros2/rmw/issues/143>`_)
* Contributors: Chris Lalancette, Karsten Knese, Michael Carroll, Mikael Arguedas, William Woodall

0.5.0 (2018-06-23)
------------------
* use rcutils allocator in allocators.c to avoid direct use of malloc/free (`#140 <https://github.com/ros2/rmw/issues/140>`_)
* check the return value of rcutils_snprintf (`#138 <https://github.com/ros2/rmw/issues/138>`_)
* _raw function (`#125 <https://github.com/ros2/rmw/issues/125>`_)
* Merge pull request `#137 <https://github.com/ros2/rmw/issues/137>`_ from ros2/misra_fixup
* Change #if to #ifdef.
* add function to parse key-value user_data (`#132 <https://github.com/ros2/rmw/issues/132>`_)
* Add validation functions accepting string length (`#135 <https://github.com/ros2/rmw/issues/135>`_)
* Clarify that NULL blocks forever in rmw_wait (`#134 <https://github.com/ros2/rmw/issues/134>`_)
* Enable setting log levels in DDS implementation (`#124 <https://github.com/ros2/rmw/issues/124>`_)
* Optimize namespace node and topic validation (`#130 <https://github.com/ros2/rmw/issues/130>`_)
* Contributors: Dirk Thomas, Ethan Gao, Karsten Knese, Michael Carroll, Shane Loretz, Sriram Raghunathan, William Woodall
