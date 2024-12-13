Description about the screenshots as per the sequnce number of the uploaded images:
1. Installing the Bionic Beaver of UBUNTU on the virtual system using Oracle Virtual Box.
2. Checking for gedit Text editor, installing gedit through terminal line code.
3. Opening the gedit text editor and typing in the code.
4. Running " riscv64-unknown-elf-gcc -01 -mabi=lp64 -march=rv64i -o output.o Hello.c , where output.o is the output objective file and Hello.o is the input file.
5. Getting the instruction set for the microcontroller.
6. The code for the Hello.c input file mentioned above and the instruction set output.
7. Running the code: " cd Desktop/work/tools/openlane_working_dir/openlane then the output is followed by " docker " as an input followed by " ./flow.tcl -interactive".
8. Running the code: " package require openlane 0.9" followed by "prep -design picovr32a" ,skywater " sky-130" processing node of which the microcontroller is built using.
9. Running the code " run_synthesis"
10. Running the code " run_floorplan" , this will give us the floorplan idea of the microprocessor
11. In a new terminal window, Running the code which will give us the "eog design" of the floorplan we got from the previous step. This gives us the '.png' file of the floorplan.
12. The floorplan png image.
13. Running the code: "run_placements"
14. The png image of the microcontroller design after placing the design on to the floorplan.
    
