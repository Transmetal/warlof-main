<h1 align="center">
  <br>
  Warlof
  <br>
</h1>

<h4 align="center">Low Bandwidth Distributed Denial-of-service attack ToolKit.</h4>

<hr>

### Warlof is a Low Bandwidth Distributed Denial-of-service attack (DDoS) Toolkit. You can use it to attack on a web server with multiple sockets. You can customize how many requests you wanna send.

<br>

### Main Features
- DDoS Attack
- Send request in HTTPS also.
- Advance Error Handeling.
- Customize request numbers.
- Multiprocessing support

<br>

### Documentation
### install
```yaml
git clone https://github.com/Transmetal/warlof-main
cd warlof
bash setup.sh
python3 warlof.py --help
```


#### Usage

```yaml
┌──(habib㉿kali)-[~/Desktop/warlof]
└─$ python3 warlof.py -h                  

             __       __                                                                                                
            (, )  |  /         /)    /)                                                                                 
               | /| / _   __  // ___//                                                                                  
               |/ |/ (_(_/ (_(/_(_)/(_                                                                                  
               /  |               /)                                                                                    
                                 (/                                                                                     
              @thenurhabib                                                                                              
                                                                                                                        
~ Low Bandwidth Denial-of-service attack (DDOS) Toolkit ~                                                               
    
usage: ⏬⏬

Warlof  - Help Menu

positional arguments:
  host                  - Domain Name or IP Address.
                                                                                                                        
optional arguments:                                                                                                     
  -h, --help            show this help message and exit                                                                 
  -p PORT, --port PORT  Domain/IP Port Number                                                                           
  -s SOCKETS, --sockets SOCKETS                                                                                         
                        Number of Requests.                                                                             
  -v, --verbose         Show attack details in terminal.                                                                
  -x, --useproxy        Use SOCKS5 proxy for connecting.                                                                
  --proxy-host PROXY_HOST                                                                                               
                        SOCKS5 proxy host.                                                                              
  --proxy-port PROXY_PORT                                                                                               
                        SOCKS5 proxy port                                                                               
  --https               Use HTTPS for the requests.                                                                     
  -ua, --randuseragents                                                                                                 
                        Randomizes user-agents with requests.                                                           
  --sleeptime SLEEPTIME                                                                                                 
                        Sleep time for every request..                                                                  
                                                                                                                                                     
```
<br>

### Example
```bash 
python3 warlof.py example.com
python3 warlof.py example.com -v
python3 warlof.py example.com -p 80
python3 warlof.py example.com --https
python3 warlof.py example.com --sleep 5
```


<br>
