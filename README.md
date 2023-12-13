# Function Generator

![Function Generator](Images/Enclosure%201.jpg)

The above shown device is an analog function generator capable of generating sinusoidal, triangular, saw tooth, and PWM signals with variable amplitudes, frequencies, and duty cycles.

The function generator was completely designed using analog components only since the design was done as a partial fulfillment for EN2091: Laboratory Practice and Projects in the Semester 3 curriculum of the Department of Electronic and Telecommunication Engineering, University of Moratuwa.

The following are the specifications of the function generator we designed.

<ul>
<li> Amplitude range: <b>0V - 10V </b></li>
<li> Frequency range: <b>20Hz - 20kHz </b></li>
<li> PWM duty cycle range: <b>1% - 99% </b></li>
<li> Minimum load: <b>50Ω </b></li>
</ul>

Other than that the function generator has the following features.

<ul>
<li> Can power using a DC adapter above 24V. </li>
<li> Supports four types of waves namely <b> Triangular</b>, <b>Saw Tooth</b>, <b>Pulse Width Modulated (PWM)</b>, and <b>Sinusoidal</b> waves.
<li> Can add a DC shift to the waveforms. </li>
<li> Push button for directly enabling square waves (50% duty PWM). </li>
<li> Colored "banana sockets" for easy output of the generated signal. </li>
</ul>

Initial design and simulations were done using LTspice, and NI Multisim softwares and then came to the <a href="Images/Breadboard Implementation.jpg">breadboard implementation</a>.

After finalizing the design, the <a href="PCB Design/PCB_Final_Design.jpg">PCB</a> was carefully designed using Altium Designer. The <a href="Enclosure Design/Enclosure Final Design.jpg">enclosure</a> was initially sketched using Blender and then modeled using SOLIDWORKS, while Canva in used for designing <a href="Enclosure Design/Top Surface Sticker Design.pdf">the sticker</a> for the top surface.

For further details on sub-circuit designing, component selection, and other details of the project, refer the <a href="Final Report.pdf">Final Report</a>.