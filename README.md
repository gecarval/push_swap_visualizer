# Push Swap Visualizer
This is a project written in C using the MiniLibX as the API which shows the behavior of the operations on the project push swap.

To execute the push_swap_visualizer go to directory of  the visualizer, after doing make on both your push_swap and the visualizer, and the use the command on the terminal:
ARG=($(seq -1000 1000 ; shuf -i 1-100)) ; ./YOUR_DIR/push_swap $ARG > ./result.txt ; ./push_swap_visualizer $ARG

Where the 'ARG' variable as the range of numbers you will introduce on both executables.
NOTE: the script is on 'zsh'
