.. _overviewstages: 

Overview of Stages
^^^^^^^^^^^^^^^^^^^^

LigaData Flare provides you with the ability to utilize data sources as nodes for various stages such as origins, processors, segments and destinations to serve various use cases.

A brief description of each stage where nodes can be used is shared below:

+--------------+-------------------------------------------------------------------------------------------------------------+
| Type         | Description                                                                                                 | 
+==============+=============================================================================================================+
| Origin       | Define the data systems that be used as a source for running the pipeline                                   |
+--------------+-------------------------------------------------------------------------------------------------------------+
| Processors   | Define the type of data processing that needs to be performed within the pipeline                           |
+--------------+-------------------------------------------------------------------------------------------------------------+
| Segments     | Group of steps available for pipeline/ segment of a pipeline templates/ some parts of pipeline can be saved |
+--------------+-------------------------------------------------------------------------------------------------------------+
| Destinations | Define the target for the pipeline                                                                          |
+--------------+-------------------------------------------------------------------------------------------------------------+

.. Note::
    * All the fields marked with an asterisk (*) are mandatory to fill.
    * To use more than one source of data, it is recommended to use the Origin Merger.
    

.. figure::  example.png
    :align:   center  

You can also refer to the :ref:`Settings <settings>` 

.. warning::
    Once defined, the pipeline type i.e, data or cache pipeline cannot be edited later.

.. admonition:: Info

    For detailed information about the data nodes, refer to the **Stage documentation** section.


Edit Role
============

To edit a role, follow the steps below:

1. Click on the **edit** icon under the **Actions** column, corresponding to the role to be edited. A dialog box will appear on the screen.
2. Make the required changes. 

* To use more than one source of data, it is recommended to use the 'Origin Merger'

.. code-block::

    SELECT * FROM mytable

The ``Data Protection audit`` page lists down the paths to the backup successfully created as a result of the data protection policy. It also includes all the relevant information required by the user to locate the backup file.


