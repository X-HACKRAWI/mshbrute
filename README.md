# mshbrute
mshbrute.sh ==> *This script does three functions. first it accepts shodan_api_key ,shodan_query usernames , passwords and then it automates the process of supplying the parameters to metasploit to provide you with a file.csv containing all ip address with information. Second it parses the file.csv to obtain only IP Addressses and save them into a file called hostsPerLine.txt. Thirdly, it performs a bruteforce attack on the hosts obtained from metasploit with a specific service.

![Screenshot_2021-04-12_00-30-24](https://user-images.githubusercontent.com/49913818/114329139-a0864900-9b0c-11eb-838f-8c38ac830e23.png)


Usage : Usage : 'API' 'QUERY' 'Workspace' usernames.list passwords.list 'service'
