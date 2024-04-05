I've added some datasets for 2 different PLC models (Siemens and AB (Allen-Bradley)). There are 3 types of dataset:
  1) Datasets with the raw mapping conditions (MC1, MC2, etc) for each PLC register at a given point in time (including timestamps). There are some        baseline files with the mapping conditions for normal behaviour, and files for individual attack scenarios.
  2) Datasets for average mapping condition deviations for each attack type (static and dynamic). In these datasets, each line is a single attack         scenario that involved either a dynamic or static attack on one of the PLC models. I used these datasets for the attack classification part.
  3) I've also included a PCAP file of some Siemens S7Comm traffic which is the application protocol that Siemens PLCs use to represent data in network    communications. I can provide additional PCAPs if you need.

Happy to discuss any of this next week and go through the data in more detail.
