*This project has been created as part of the 42 curriculum by llupache.*

# NetPractice

## Description
NetPractice is a general practical exercise designed to introduce the basics of computer networking. The goal of this project is to configure small-scale simulated networks to make them function properly. Throughout 10 levels of increasing complexity, the project requires configuring IP addresses, subnet masks, routing tables, and default gateways to establish correct communication between various devices while avoiding overlapping subnets and routing loops.

## Instructions
To run the training interface and complete the project, follow these steps:

1. Download the project files and extract them into a folder of your choice.
2. Run the `run.sh` script in that folder. This shell script will launch a local web server and open the NetPractice page in your web browser. *(If the script does not function properly, you can manually run `python3 -m http.server 49242` and navigate to `http://localhost:49242`)*.
3. Enter your login (`llupache`) in the training interface to use your personal configuration.
4. Complete the 10 levels by modifying the unshaded configuration fields until the network reaches all goals successfully.
5. **Exporting configurations:** Before moving to the next level, you must export your configuration by clicking the **Get my config** button.
6. **Submission requirements:** You must submit exactly 10 exported configuration files (one file per level). Place all 10 files directly at the root of your Git repository.

## Resources
This project required studying and understanding the following networking concepts:
* TCP/IP addressing
* Subnet masks and VLSM (Variable Length Subnet Masking)
* Default gateways and routing tables (Forward and reverse ways)
* Routers and switches
* OSI layers

**References:**
* Classic networking documentation and online subnetting tutorials.
* Internal peer discussions and testing.

**Use of AI:**
* AI was used as a conversational tutor to help clarify complex theoretical networking concepts, such as the mathematical logic behind subnetting with variable-length subnet masks (from /18 to /30), understanding routing loops, and the difference between public and private IP ranges. 
* AI was not used to generate the final configuration files, but rather to break down the problem-solving process and analyze overlapping subnets during the learning phase.