zabbix-agent [![Build Status](https://travis-ci.org/xcezx/ansible-zabbix-agent.svg?branch=master)](https://travis-ci.org/xcezx/ansible-zabbix-agent)
========

install and configutation zabbix-agent

Role Variables
--------------

- `zabbix_agent_install_packages`
- `zabbix_agent_Alias`
- `zabbix_agent_AllowRoot`
- `zabbix_agent_BufferSend`
- `zabbix_agent_BufferSize`
- `zabbix_agent_DebugLevel`
- `zabbix_agent_EnebleRemoteCommands`
- `zabbix_agent_HostMetadata`
- `zabbix_agent_HostMetadataItem`
- `zabbix_agent_Hostname`
- `zabbix_agent_HostnameItem`
- `zabbix_agent_Include`
- `zabbix_agent_ListenIP`
- `zabbix_agent_ListenPort`
- `zabbix_agent_LoadModule`
- `zabbix_agent_LoadModulePath`
- `zabbix_agent_LogFile`
- `zabbix_agent_LogFileSize`
- `zabbix_agent_LogRemoteCommands`
- `zabbix_agent_MaxLinesPerSecond`
- `zabbix_agent_PidFile`
- `zabbix_agent_RefreshActiveChecks`
- `zabbix_agent_Server`
- `zabbix_agent_ServerActive`
- `zabbix_agent_SourceIP`
- `zabbix_agent_StartAgents`
- `zabbix_agent_Timeout`
- `zabbix_agent_UnsafeUserParameters`
- `zabbix_agent_UserParameter`

Dependencies
------------

- `xcezx.zabbix-repository`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xcezx.zabbix-agent }

License
-------

BSD
