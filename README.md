# MXEN3002 Mechatronics Automation project
THIS REPOSITORY IS ONLY TO BE USED FOR PORTFOLIO PURPOSES
### Date completed
21/05/2024, completed 70/70 marks.
- For integration, whenever an error occurs on the prime station, the slave stations down the line go into pause mode, not error mode.
- For SCADA, station 3 shows the states of the blocks but does not have a smooth animation with time like the example video.

### Running final version
Use SCADA programs for final project viewing.
The intgration was done before SCADA station, and SCADA is not required to run to run any programs although there were changes to the program after marks recieved that fix edge case errors found later on.
Would need to change the SCADA files flag on station 1 for requesting workpiece to not be perma on, so that there is proper communication between station 1 and 2, this was removed as was testing SCADA for individual stations only.
### Running SCADA files
Need to create a new SCADA Ignition file and then import the SCADA file over it, this probably wouldn't work either way if the tags and all profile settings for each station are not in the Ignition tags library or have been deleted from the website profiles themselves.
To make this work use the SCADA onramp file in blackboard. Would need to export the global variables or use the txt file in each SCADA folder to use for tags.
