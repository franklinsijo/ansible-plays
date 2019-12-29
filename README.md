### Ansible Plays
Random Collection of ansible tasks for Windows.

**1. read_event_logs**
```sh
ansible-playbook windows/read_event_logs.yml -i hosts --extra-vars='{"NumEvents":integer, 
																	"ProviderName":"string",
																	"ID":"CommmaSeperatedIntegers",
																	"Level":"CommmaSeperatedIntegers",
																	"StartTime":"WindowsDateFormat",
																	"EndTime":"WindowsDateFormat"
																	}'
```