.. default-role:: py:obj

.. include:: ../README.rst

.. default-role:: any

.. literalinclude:: ../src/rtmixer.h
   :language: c

API Documentation
-----------------

.. automodule:: rtmixer

.. autoclass:: Mixer
   :members: play_buffer, play_ringbuffer, actions, cancel, wait
   :undoc-members:

.. autoclass:: Recorder
   :members:
   :undoc-members:

.. autoclass:: MixerAndRecorder
   :members:
   :undoc-members:

.. autoclass:: RingBuffer
   :inherited-members:

.. only:: html

   Index
   -----

   :ref:`genindex`
