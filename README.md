# Ansible Plays
Random Collection of ansible tasks for Windows and Linux.

## Windows
1. read_event_logs
	ansible-playbook windows/read_event_logs.yml -i hosts --extra-vars='{"NumEvents":integer, 
																		 "ProviderName":"string",
																		 "ID":"CommmaSeperatedIntegers",
																		 "Level":"CommmaSeperatedIntegers",
																		 "StartTime":"WindowsDateFormat",
																		 "EndTime":"WindowsDateFormat"
																		}'
