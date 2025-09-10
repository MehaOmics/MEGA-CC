## MEGA-CC 
For generating phylogenetic tree for large dataset MEGA-CC is a good choice
## Installing MEGA-CC
- Download megacc older version from https://www.megasoftware.net/ (New version is not compatible with Compute canada server)
- After downloading transfer it to compute canada server.It will create a folder "usr" in the same folder with 4 different sub folders
- Go to lib64 folder
- change the permissions of the megacc file to make it executable: chmod +x megacc

## Input file
- Alignment file (.meg) from MEGA desktop version
- The MEGA Analysis Options file (.mao) from MEGA desktop. This file has information about the type of phylogenetic analysis (e.g., Maximum Likelihood, Neighbor Joining),Substitution model and Bootstrap values
