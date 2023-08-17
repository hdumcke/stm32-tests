# stm32-tests

This is for testing only

## Preparation

On Ubuntu 22.04 install the tool chain:

 1. git clone https://github.com/hdumcke/multipass-orchestrator-configurations.git
 2. ./multipass-orchestrator-configurations/stm32-dev/build.sh

## Instructions
 1. git clone --recurse-submodules https://github.com/hdumcke/stm32-tests
 2. cd stm32-tests
 3. make -C libopencm3 # (Only needed once)
 4. make -C blink
