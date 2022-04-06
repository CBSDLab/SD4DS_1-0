# Accessing HPC

This exercise covers accessing the Case Wester Reserve University (CWRU) High Performance Computing (HPC) cluster, starting inteactive sessions in RStudio and Jupyter, and cloning GitHub repositories.  

# Exercises

The easiest way to access the CWRU HPC is through the OnDemand accessed through a browser by going to https://ondemand.case.edu/pun/sys/dashboard. The OnDemand interface provides a variety of tools from starting interactive sessions in RStudio and Jupyter to scheduling batch jobs. The OnDemand dashboard can be accessed with a valid CWRU ID and 2-factor authentication (no VPN is required). Access to specific clusters and resources depends on additional authorizations (e.g., through a class or research group). 

## 1. Starting an interactive RStudio session on the HPC

To start an interactive RStudio session on the CWRU HPC with minimal resources (requesting minimal resources shortens the time for the interactive session to be started): 

1. Go to the CWRU HPC OnDemand portal: https://ondemand.case.edu/pun/sys/dashboard/
2. Select Interactive Apps from the menu and then choose RStudio Server (highest version).
3. Enter the Slurm account for accesing the HPC.
4. Select "cpu nodes".
5. Set the session to 1 hour (later on, for more complex or longer sessions, it may be neccesary to set this to a longer duration). Note that the session will automatically end if exceeded the scheduled duration. 
6. Select the core to minimum of 1 core. 
7. Set memory requested to the 4 GB. 
8. Launch the sesssion. 
9. Connect to RStudio server when the session begins. 

To see a screen video of this sequence, go to https://youtu.be/MsXNLPs97TM.

## 2. Starting an interactive Jupyter session on the HPC

To start an interactive RStudio session on the CWRU HPC with minimal resources (requesting minimal resources shortens the time for the interactive session to be started): 

1. Go to the CWRU HPC OnDemand portal: https://ondemand.case.edu/pun/sys/dashboard/
2. Select Interactive Apps from the menu and then choose Jupyter Notebook.
3. Enter the Slurm account for accesing the HPC.
4. Select "cpu nodes".
5. Set the session to 1 hour (later on, for more complex or longer sessions, it may be neccesary to set this to a longer duration). Note that the session will automatically end if exceeded the scheduled duration. 
6. Select the core to minimum of 1 core. 
7. Set memory requested to the 4 GB. 
8. Launch the sesssion. 
9. Connect to Jupyter when the session begins. 
10. Click the New menu (top-right) and selected "Python 3". 

To see a screen video of this sequence, go to https://youtu.be/8j67NdWnmEg.
