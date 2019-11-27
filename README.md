# Final Project - 50.012 Networks

## data
Data collected for all three trials of our main experiment (end-to-end + compartmentalized latency measurement), as well as a trial measuring the processing delay of our GamingAnywhere server.

## experiment_automation
This is a simple AutoHotKey automation script used to calculate the end-to-end delay in the GamingAnywhere cloud gaming system. The script is meant to be run on the client device, and does the following:
- Maximizes the client program
- Simulates an Esc button press, and logs the time at which the button was pressed
- Logs the time at which the game menu appears by tracking a pixel near the centre of the screen

The timestamps are accurate to a hundredth of a millisecond. The script is based on [skrommel's PixelNotifier](https://www.dcmembers.com/skrommel/download/pixelnotifier/).
