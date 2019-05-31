tmgsyn.mod is an implementation of a model of short-term synaptic 
plasticity using NEURON's model description language NMODL.

The model has been described by Tsodyks and collaborators in 
publications that include
  Tsodyks, M., Pawelzik, K., Markram, H.
  Neural networks with dynamic synapses.
  Neural Computation 10:821-835, 1998
and
  Tsodyks, M., Uziel, A., Markram, H.
  Synchrony generation in recurrent networks with
  frequency-dependent synapses.
  J. Neurosci. 2000 RC50.

This demonstration is patterned after Fig. 1A-C in the Neural 
Computation paper, except that the synapse is implemented with 
a conductance change, whereas Tsodyks et al. assumed that the 
synapse acted as a current source.


NOTES:

1.  The important part of this package of files is the synaptic 
mechanism, not the "cells."  The synaptic mechanism is reusable 
in models of biophysical neurons.  The "cells" are merely 
single-compartment passive models whose sole purpose is to serve 
as leaky integrators.

2.  The presynaptic stimulus and its connection to the synaptic 
mechanism were implemented with NEURON's Artificial Cell and 
Network Builder tools.  For tutorials about how to use these tools, 
and information about NEURON's model description language NMODL, 
see the Documentation page at NEURON's WWW site 
( http://www.neuron.yale.edu/ )
especially the FAQ link on that page.

3.  If you are interested in other models of short term synaptic 
plasticity, see ModelDB for an implementation of the model 
described by
  Varela, J.A., Sen, K., Gibson, J., Fost, J., Abbott, L.R., 
  and Nelson, S.B.. 
  A quantitative description of short-term plasticity at 
  excitatory synapses in layer 2/3 of rat primary visual cortex.
  Journal of Neuroscience 17:7926-7940, 1997.
(search under author's name, or under topics such as "synaptic 
plasticity").


Contact ted.carnevale@yale.edu if you have questions about 
this implementation of the model described by Tsodyks et al..
