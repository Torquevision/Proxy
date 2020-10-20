# Proxy
How you can use Proxy Globally 

Follow the format of Proxy : PROXY_FORMAT  = Username:password@IP:port

Commands to apply Proxy:

1. Open Terminal and type : $sudo nano /etc/environment
                            Add Following Lines:
                              http_proxy = "http://PROXY_FORMAT"
                              https_proxy= "https://PROXY_FORMAT"
                              ftp_proxy  = "ftp://PROXY_FORMAT"
                              no_proxy  = "localhost"
                              
2. Save the File and REBOOT your System / Server r
3. Hit $curl http://checker.soax.com/api/ipinfo
  
