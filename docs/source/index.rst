.. Bipype documentation master file, created by
   sphinx-quickstart on Sun Nov 27 16:39:36 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Bipype's documentation!
==================================

Short description
-----------------

Bipype is a very useful program, which prepare a lot of types of bioinformatics analyses.
There are three input options: amplicons, WGS (whole genome sequencing) and metatranscriptomic data. If amplicons are input data, then bipype does reconstruction and pairs merging. After that biodiversity is searching. There are two types of searching depending on the amplicons types (ITS or 16S).
If WGS are chosen, then bipype finds the SA coordinates of the input reads and generates alignments in the SAM format given single-end reads, aligns reads to reference sequence(s).
All of these analyses will be shown with Krona program, which allows to show hierarchical data with pie charts.


bipype stands for **bi**\ oinformatics-**py**\ thon-**p**\ ip\ **e**.

Chapters
-----------------

.. toctree::
   :maxdepth: 4

   proposed_analysis
   more_detailed_description_of_bipype_workflow.rst
   command_line_options.rst
   appendixes.rst
