********************
Diffusion Prevalence
********************


The Diffusion Prevalence plot compares the delta-trends of all the statuses allowed by the diffusive model tested.

Each trend line describes the delta of the number of nodes for a given status iteration after iteration. 

.. autoclass:: ndlib.viz.bokeh.DiffusionPrevalence.DiffusionPrevalence
.. automethod:: ndlib.viz.bokeh.DiffusionPrevalence.DiffusionPrevalence.__init__(model, iterations)
.. automethod:: ndlib.viz.bokeh.DiffusionPrevalence.DiffusionPrevalence.plot(width, height)


Below is shown an example of Diffusion Prevalence description and visualization for the SIR model.

.. code-block:: python
    :linenos:

    import networkx as nx
    from bokeh.io import show
    from ndlib.viz.bokeh.DiffusionPrevalence import DiffusionPrevalence


    # Visualization



.. figure:: diff_prevalence.png
   :scale: 80 %
   :align: center 
   :alt: SIR Diffusion Prevalence Example

   SIR Diffusion Prevalence Example.