.. qaserver-tips documentation master file, created by
   sphinx-quickstart on Wed Jan  1 16:52:40 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Doing tests on Elekta linacs
============================

This page contains some notes about doing interesting tests on Elekta linacs with `pyQAserver <https://github.com/brjdenis/qaserver>`_. The notes deal mostly with aspects of the linac that are important for radiosurgery: focal spot position, XVI calibration, MLC calibration, couch axis calibration.

.. warning::
	The content on this site is based on my personal experience. It was not reviewed or approved by anybody. The notes are provided "as is", and use them "at your own risk". So, beware. And read this disclaimer before you read further: :doc:`disclaimer`.



Last change: |today|.

.. toctree::
	:maxdepth: 2

	starting.rst
	winstonlutz.rst
	xvi.rst
	focalspot.rst
	picketfence.rst
	disclaimer.rst
