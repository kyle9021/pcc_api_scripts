# README

## Assumptions

You're using ubuntu 20.04

## Instructions
* Step 1: `git clone https://github.com/Kyle9021/pcc_api_scripts`
* Step 2: `cd pcc_api_scripts`
* Step 3: `nano container_start_report.bash` and replace `<USERNAME>`, `<PASSWORD>`, `<IP_ADDRESS/HOSTNAME:PORT>` with the appropriate values from your pcc console. 
* Step 4: Install jq if you dont have it `sudo apt update && upgrade -y` then `sudo apt install jq`
* Step 5: `bash container_start_report.bash`

The report will be in a text file called report.text. This is a very simple low-level script that should be used for demo/poc purposes. Written in Bash for portability. 

Please be sure to check out the offical [PAN development site](https://prisma.pan.dev/) for Prisma Cloud 
