



```
apt update && apt install sudo curl
```

```
curl -fsSL https://get.docker.com -o get-docker.sh
bash ./get-docker.sh
```

Test it
```
docker run hello-world
```

https://noted.lol/setup-and-install-docker-in-a-promox-7-lxc-container/


```
curl -so wazuh-agent-4.3.11.deb https://packages.wazuh.com/4.x/apt/pool/main/w/wazuh-agent/wazuh-agent_4.3.11-1_amd64.deb && sudo WAZUH_MANAGER='192.168.88.12' WAZUH_AGENT_GROUP='default' dpkg -i ./wazuh-agent-4.3.11.deb
```
