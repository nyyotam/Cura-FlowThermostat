Cura FlowThermostat recently started giving strange temperatures. Looking into it, it turns out new versions of Cura sometimes gives out high feedrates spikes, which exceed the "max" feedrate calculated by the FlowThermostat. 

To counter that, my quick and dirty solution - is to simply ignore any feedrate which is above the max feedrate calculated. This makes the "print speed" entry from the user critical. But, it ensures protection from the above strange Cura behavior.

Default profile for this version of the plugin is PLA, where it might be of most use. In the plugin code you will find the values for Nylon.