Waste Detection System
----------------------

.. automodule:: waste_detection_system
   :members:
   :undoc-members:
   :show-inheritance:

.. _tll:

.. note ::
    About the ``transfer learning level``:
        - TLL = 0 : train the model from scratch (all layers)
        - TLL = 1 : use transfer learning and train only the model's classification and regression heads
        - TLL = 2..5 : use fine-tuning and train the model's heads as well as some more layers