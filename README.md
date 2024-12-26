# NAME : G ASWINI
# REG.NO. : 24000247
# EXPERIMENT 6 : IMPLEMENTATION OF SERIAL IN SERIAL OUT SHIFTREGISTER

# AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY :

A Serial-In Serial-Out (SISO) shift register is a sequential logic circuit used to store and shift data serially. It operates by taking one bit of input data at a time through a serial input line, which is loaded into the first stage of the register with each clock pulse. The data is shifted sequentially through a series of flip-flops, each representing a stage of the register, with the number of flip-flops determining the register's capacity. At every clock pulse, the content of each flip-flop is transferred to the next, and the final stage outputs the data serially through a serial output line. The process continues until all the input bits have been shifted through and outputted. SISO shift registers are commonly used for tasks such as data serialization, deserialization, temporary data storage, and signal delay. Their simplicity and minimal data line requirement make them ideal for applications where serial data handling is necessary, though their sequential nature can make them slower compared to parallel data processing methods.

# SISO shift Register :

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

# PROCEDURE : 

1. Launch Quartus on your computer and create a new project: Go to File → New Project Wizard.
 Specify the project name, directory, and top-level entity name (e.g., SISO).
 2. Create the JK Flip-Flop Circuit and implement the SISO by writing VHDL/Verilog code. Go to
 File → New → Select Verilog File.
 Editing SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/README.md at main · Aswini51/SERIAL-IN-SERIAL-OUT-SHIFTREGIS…
 3. Compile the Project Click on Processing → Start Compilation. Fix any syntax or schematic errors
 if present.
 4. Simulate the Circuit: Go to Tools → University Program VWF. Define the inputs for sin, and CLK
 in the waveform editor. Run the simulation and observe the waveforms.
 5. Verify the Results

# TRUTH TABLE : #

![WhatsApp Image 2024-12-12 at 2 31 13 PM](https://github.com/user-attachments/assets/7fd6bbbd-13ba-47ec-b486-a702f5458da8)

# PROGRAM :

![Screenshot 2024-12-12 133630](https://github.com/user-attachments/assets/9bec7405-96b7-4b1e-a776-e5a9bfb41edc)

# RTL : 

![Screenshot 2024-12-12 133717](https://github.com/user-attachments/assets/320e6447-6a70-42c3-9616-60e8b15987ac)

# TIMING DIGRAMS FOR SISO SHIFT REGISTER :

![Screenshot 2024-12-12 135814](https://github.com/user-attachments/assets/ea784c34-fccd-44d6-9653-08377d876c46)

# RESULTS :

 Implementation of SISO Shift Register using verilog and validating their functionality using their
 functional tables is verified.
