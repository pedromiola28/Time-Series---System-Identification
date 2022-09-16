# Time-Series---System-Identification

This is a notebook where I analyze data generated by a Simulink simulation where I apply a certain excitation signal in a mass-spring-damper system. 

The ideia is to understand and predict the behavior of the system in terms of position based on the force that is applied.

To do this, I used a NARX Neural Network (with SysIdentPy: https://sysidentpy.org/examples/narx_neural_network/) and a LSTM Neural Network, comparing both results.

The next steps are to see if the same model can predict with different excitation signals.
