Welcome to MatSim Laboratory Excercise (OV_01)!

This VM image contains everything you need for the lab excercise: MatSim, Via, Eclipse.

The configuration files for MatSim are in the /home/matsim/Work/config directory.

Note on MatSim: it may stop with a java error that says JAXBException. This is harmless for us, because at that point the output files we need have already been written out.

How to use Via:
- first, you need to apply for a free license on their homepage, download the license.xml.zip they send you in email, when Via asks for a license, seelct this file, and click the close button in the bottom right corner
- after MatSim has run your simulation, you need to import the output files into Via: on the left pane switch to the data sources (the icon with three grey pages), and drag&drop the following files there from the file manager: output_network.xml.gz, iters/it.0/0.events.xml.gz
- from the menu select File/Add Layer, and in the dialog select Network, check if it has found the output file it needs, then click the Add button at the bottom, now you should see the network in the main screen (zoom out with the mouse wheel)
- use Add Layer again, in the dialog select Vehicles from Events, click Add
- on the left pane switch to the layers (the icon with three colored sheets), and in the Vehicles part click Load Data, now in the bottom the timeline should have times on it, and you can grab its handle to control the time
- if you want to see the results of another simulation, you may unload the data in Via and load the new ones, but I found it much easier to just close Via and restart from the beginning

For excercise 2 the maven project in Eclipse is already created, and the necessary java source files have been downloaded and added to the project. You only need to edit them in the marked locations.

In excercise 2 you need to place your vehicle start-stop locations on your map. To see what the coordinates are, open the network generated in 2.1 with Via, and you can see the coordinates at the mouse cursor above the map. 


