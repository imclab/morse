
Media
=====

Videos
------

+------------------------------------------+------------------------------------------+
|                                          |                                          |
|         .. vimeo:: 27862570              |        .. vimeo:: 23244699               |
|            :width: 400                   |           :width: 400                    |
|                                          |                                          |
|  Some examples of integration between    |  Using ROS RVIZ vizualisation tool to    |
|  MORSE and ROS in human-robot interaction|  display the video stream of a simulated |
|  context.                                |  camera                                  |
+------------------------------------------+------------------------------------------+
|                                          |                                          |
|         .. vimeo:: 22246759              |        .. vimeo:: 19258005               |
|            :width: 400                   |           :width: 400                    |
|                                          |                                          |
| Here, a robot builds a 2.5D terrain model|  MORSE can take care of navigation if    |
|  map from simulated stereo-cameras, and  |  you do not want to manage this part.    |
|  uses it to navigate.                    |                                          |
+------------------------------------------+------------------------------------------+
|                                          |                                          |
|         .. vimeo:: 27862605              |        .. vimeo:: 9825826                |
|            :width: 400                   |           :width: 400                    |
|                                          |                                          |
|  MORSE can be used to test human-robot   |  Several robots following each others.   |
|  interaction scenarii, where a human     |  Each robot streams its camera, here     |
|  is controlled as in a video game.       |  with YARP.                              |
+------------------------------------------+------------------------------------------+

More videos are available on the `Blender for Robotics Vimeo group 
<http://vimeo.com/groups/blenderandrobotics>`_.


Screenshots
-----------

+------------------------------------------+------------------------------------------+
| .. figure:: ../media/caylus.jpg          |  .. figure:: ../media/indoors_sick.jpg   | 
|    :width: 422                           |                                          |
|                                          |     Real-time simulation of a SICK       |
|    Simulation of ground-air cooperation. |     laser range finder in an indoors     |
|                                          |     environment.                         |
+------------------------------------------+------------------------------------------+
| .. figure:: ../media/outdoor_example.jpg |  .. figure:: ../media/ocean.jpg          | 
|                                          |     :width: 422                          |
|                                          |                                          |
|    An ATRV in an outdoor scenario.       |     Cooperation between an helicopter    |
|                                          |     and a submarine for mine hunting.    |
|                                          |                                          |
+------------------------------------------+------------------------------------------+
| .. figure:: ../media/hri.jpg             |  .. figure:: ../media/morse_interface.jpg| 
|    :width: 422                           |     :width: 422                          |
|                                          |                                          |
|    Simulation of human-robot             |     The MORSE interface (crude Blender   |
|    interaction: the robot tracks the     |     :-) )                                |
|    posture of the human.                 |                                          |
+------------------------------------------+------------------------------------------+

MORSE related academic publications
===================================

- `Modular Open Robots Simulation Engine: MORSE <http://homepages.laas.fr/gechever/Documents/paper-icra.pdf>`_, ICRA 2011::

    @InProceedings{morseICRA2011,
        author = {G. Echeverria and N. Lassabe and A. Degroote and S. Lemaignan}
        title = {Modular OpenRobots Simulation Engine: MORSE}
        booktitle = {Proceedings of the IEEE ICRA},
        year = {2011}
    }

- Presentation of MORSE at the Blender Conference 2010:
  `slides <http://homepages.laas.fr/gechever/BlenderConference/BC_morse.pdf>`_ and
  `video <http://www.youtube.com/watch?v=BGDfbi28s14#t=20m20s>`_
- Presentation at the `European Robotics Forum 2011 <http://www.eurobotics-project.eu/cms/index.php?idcat=40>`_:
  `general overview of MORSE <http://homepages.laas.fr/gechever/Documents/ERF-MORSE-presentation.pdf>`_ and
  `MORSE-ROS implementation <http://homepages.laas.fr/gechever/Documents/morse_ros.pdf>`_