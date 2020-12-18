.. _conf_file:

Hierarchy of Configuration File
===============================

All the modules used in an algorithm can be easily set in the configuration file
with *yaml* format. 

.. code-block:: text

    engine:
        type:
    algorithm:
        type:
        ...
        backbone:
            type:
            ...
        neck:
            type:
            ...
        head:
            type:
            ...
        ...
    train_cfg:
    test_cfg:
    train_pipeline:
    val_pipeline:
    test_pipeline:
    data:
        type:
        ...
    runtime:
        

.. _management:

Management of Modules
=====================

some description here.