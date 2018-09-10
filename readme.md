# Randomly generating a PCB name plate
![Final result](final_result.jpg?raw=true "Final result")

Using Python to generate randomly placed pads and translate into the DipTrace ASCII format. I'm pretty sure this does not actually follow the DipTrace standard, but the results are good enough to use as a name plate.
For details, see http://jdtengineering.nl/electronics/creating-a-pcb-name-plate-using-python-and-diptrace


### Dependencies
Python 3.6 (for f-strings)
jupyter
matplotlib

### How to use
- Run generate_pcbs.ipynb
- Generate a PCB
- Import into DipTrace
- Run DipTrace autorouter to generate the traces
- (optional) Remove traces where you want to put text
- (optional) Place drill holes
- Generate gerbers with DipTrace
- Send gerbers out for production