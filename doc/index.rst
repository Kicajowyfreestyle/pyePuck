.. ePuck.py documentation master file, created by
   sphinx-quickstart on Mon Jun  6 11:11:55 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ePuck.py's documentation
====================================

:Version: |release|

The aim of this library is to provide access to the ePuck robots through a bluetooth connection. Thus, you can write a program that read from the ePuck's sensors and write in their actuators, This will allow us to create advanced programs that can develop a wide variety of complex tasks. It is necesary that the ePuck has installed the Webot's fimware 1.4.2 or 1.4.3. You can find this fantastic simulator on this site: http://www.cyberbotics.com/

This library is written in Python 2.6, and you can import it from any program written in Python  (same version or later). In addition to this, you will also need two extra libraries:

* Python Bluetooth or Pybluez
* Python Image Library (PIL)

In this package you will find some examples of how to use this library.

You may expetience some problems when you work with your ePuck, We recommend you take into consideration the following special characteristic: we use a bluetooth communciation, therefore our bandwith is limited and we cannot expect to do too many tasks in short time; i.e:  If you put the wheels speed to max and want to make a quick process of the images, you will know what I'm saying. So remember, you are processing in your computer, not on the ePuck, and you need to take the sensors data and write on the actuators values on the ePuck

For further information and updates visit http://www.itrblabs.eu

.. toctree::
	:maxdepth: 2
	
	installation
	examples
	api



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

