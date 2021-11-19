Automating Pooling for Different Sequencers:
Purpose: To Automate calculations for different genome sequencing needs

Goals:

-Create a script that will calculate how to evenly or unevenly pool samples for different sequencers

-Provide GUI drop down menu of sequencer options for user to chose from (all have different total read capacities and loading requirements, so selection must then be linked to those details in some way -- library/dictionary/ect)

-Give total concentration of that final library to determine dilution needs, if any

-Asks if user wants phix and what percentage, then calculate how many reads go to phix, and how many leftover for samples

-Asks user how many libraries going on

-Asks for number of samples per library, number of reads per sample, ng/ul, % of library between 200-1000 base pair length, base pair length average

-From input, will calculate MW, nmol/ul, nM, total number of reads needed, and proportion of the lib/total

-Will ask user what minimum pipetting value they want to provide

-After the user enters in all libraries and their respective information the script will calculate volume to input (uL) but if that volume is under the minimum pipetting value, will recalculate so proportionally input is greater than that minimum.

-Will also provide instructions on barcoding directions depending on sequencer

-Finally, will calculate dilutions or total volume to provide per sequencer requirements

-Perhaps at the end there is another GUI which allows you to chose a library to change numbers for, i.e. "which library do you want to change?" and then "what pooling aspect do you want to change?"
