
1. ```apt update```
2. ```apt install openssh-server```
3. ```sudo apt-get remove docker docker-engine docker.io containerd runc```
4. ``` sudo apt-get update```
5. ```sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
    ```
6. ```curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg```
   
7. ```echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null```

8. ```sudo apt-get update```
9. ``` sudo apt-get install docker-ce docker-ce-cli containerd.io```
10. ```sudo systemctl enable docker.service```
11. ``` sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose```
12. ```sudo chmod +x /usr/local/bin/docker-compose```
13. ```adduser mist```
    1.  <password>
    2.  leave all blank
14. ```sudo groupadd docker```
15. ```sudo usermod -aG docker mist```
16. ```wget https://github.com/mistio/mist-ce/releases/download/v4.5.5/docker-compose.yml```
17. ```docker-compose up -d```
18. ```curl -fsSL https://pkgs.tailscale.com/stable/ubuntu/focal.gpg | sudo apt-key add -```
19. ```curl -fsSL https://pkgs.tailscale.com/stable/ubuntu/focal.list | sudo tee /etc/apt/sources.list.d/tailscale.list```
20. ```sudo apt-get update```
21. ```sudo apt-get install tailscale```
22. ```sudo tailscale up --authkey tskey-29ef3b518c4a551a08c562c6```
23. ```su - mist```
24. ```cd /home/mist/mist-deploy/settings```
25. ```nano settings.py```
26. 
```python
#replace CORE_URI="http://localhost" with dns name
CORE_URI="https://mist.brentgruber.com"
```