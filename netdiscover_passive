#!/bin/bash

# Clear the screen for a clean interface
clear

# Display the Introxt logo (if available)
cd Logo && ./introxt_logo && cd ..

# Prompt the user to specify the network interface
echo "Enter Your Interface:"
read inf

# Scan the network using netdiscover on the provided interface
netdiscover -i $inf -p
