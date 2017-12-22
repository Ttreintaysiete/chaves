# chaves
Cheap Hacky Audio/Video - Glitch VGA synth based on jonasbers.com/chav/

This is a WIP, and PCBs have not fully tested, if you want to contribute send a build to your favorite pcb provider and give us any feedback.

Pending...

* will generate a bom
* building guide

## Chaves

Its a glitch video synth bassed on CHA/V as stated, but with lots of controls and patcheable pins with the intentions of doing a mini-modular video glitch synth.

Like in the original CHA/V it has 6 VCOs, with selectables ranges, sync sources, frequency and effects outputs (thanks to the coupling caps). Here is a schematic of a single voice

![single oscillator schematic](images/single_oscillator_diagram.png)

* The __syncbus__ can be either connected to the vsyn or hsync of the VGA tester. This will send the selected sync to the jumperpins near the beggining of the Oscillator so you can either select each oscillator to be connected to this sync bus or not to be free running.
* Since we are using pinheaders you can use patcables from any point of the pcb so anthoer oscillator can __modulate__ the sync of a specific oscillator...
* Every voice output can be connected to any of the RGA VGA inputs with patchables, or can be patched somewhere else, to create complex patterns