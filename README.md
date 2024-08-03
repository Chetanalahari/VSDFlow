# VSDFlow
## Day 0

### Install Yosys

#### Yosys is a Verilog HDL synthesis tool. This means that it takes a behavioural design description as input and generates an RTL, logical gate or physical gate level description of the design as output. Yosys’ main strengths are behavioural and RTL synthesis.

$ sudo apt-get update

$ git clone https://github.com/YosysHQ/yosys.git

$ cd yosys

$ sudo apt install make (If make is not installed ,install it)

$ sudo apt-get install build-essential clang bison flex
libreadline-dev gawk tcl-dev libffi-dev git
graphviz xdot pkg-config python3 libboost-system-dev
libboost-python-dev libboost-filesystem-dev zlib1g-dev

$ make config-gcc

$ make

$ sudo make install

<img width="429" alt="image" src="https://github.com/user-attachments/assets/56ee140f-3948-4352-a7ec-4787843e3890">


### iverilog

$ sudo apt-get install iverilog

<img width="397" alt="image" src="https://github.com/user-attachments/assets/4c3d4240-1a52-474b-8b3b-1af524da6aa6">

### gtkwave

sudo apt-get update

sudo apt install gtkwave

<img width="574" alt="image" src="https://github.com/user-attachments/assets/7edf13db-e248-4153-af7e-5e47627cb532">

## Day 1 - Introduction to Verilog RTL Design and Synthesis

In RTL design, the adherence to specifications is verified through simulation using a tool called a simulator. For this course, the simulator used is Icarus Verilog (Iverilog). The design refers to the actual Verilog code or set of codes that implement the intended functionality to meet the required specifications.

A testbench is used to apply stimulus, or test vectors, to the design to check its functionality. The simulator operates by monitoring changes in input signals; when an input changes, the corresponding output is evaluated. If there are no changes in the input, the output remains unchanged, as the simulator continuously checks for variations in input values to determine the resultant outputs.

### Block diagram of Test Bench






