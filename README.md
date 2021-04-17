# MP_Neuron

This repository contains the implementation of mp neuron model.

McCulloch (neuroscientist) and Pitts (logician) proposed a highly simplified computational model of the neuron in 1943. MP neuron model is also known as linear threshold gate model.

### Mathematical model
![Image of model](https://github.com/akshat-20/MP_Neuron/blob/main/model.png)

where:  g aggregates the inputs 
        function f takes a decision based on this aggregation
        
The inputs can be excitatory or inhibitory
y = 0 if any xi is inhibitory, else
g(x1, x2, ..., xn) = g(x) = Xn
i=1
xi
y = f(g(x)) = 1 if g(x) ≥ θ
= 0 if g(x) < θ
• θ is called the thresholding parameter
• This is called Thresholding Logic
