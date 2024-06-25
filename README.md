# Mini mitmproxy PoC


## Introduction

This is a very simple and short PoC (Proof of Concept) of the mitmproxy CLI utility. There is no code involved in this test.
Here, I configured the browser to point to the mitmproxy and then ran the mitmproxy to start capturing all the traffic.
Both are running on the same PC

## Objectives

1. Interception of HTTP and HTTPS traffic by running mitmproxy in a local PC


## Scope of the PoC

1. Both browser and mitmproxy are running on the same PC.

2. The CA certificate used was the provided by the mitmproxy utility. 

3. The mitmproxy's CA certificate was deployed on the firefox browser.

4. Test a https site with no login

5. Test a https site with login and capture the credentials.


## What do I need to run this PoC

1. To see all the intercepted traffic you will need the mitmproxy. So, install it by doing:
	sudo apt install mitmproxy


## How to run this PoC

1. Deploy on the browser the CA cert provided by the mitmproxy utility. Check /home/user/.mitmproxy folder

2. on the browser configure proxy settings point to port 8080. There our mitmproxy will be listening.

3. Start browsing sites on your browser
 
4. Launch the mitmproxy with the following line:

	mitmproxy


## Files

*./Mini-mitmproxy-PoC/*

*01-browser-certificate_settings.png*

*02-browser-proxy_settings.png*

*03-mitmproxy-browser-cyberChef-01.png*

*04-mitmproxy-browser-cyberChef-cert_details-02.png*

*05-mitmproxy-cyberChef-traffic-01.png*

*06-mitmproxy-cyberChef-original_cert_details-01.png*

*07-mitmproxy-imperv-01.png*

*08-mitmproxy-imperv-02.png*

*09-mitmproxy-imperva_login_sniffing_cert_details-01.png*

*09-mitmproxy-imperva_login_sniffing_details-01.png*

*09-mitmproxy-imperva_login_sniffing_traffic-01.png*

*README.md*

***Notes:***
1. All png files are screenshots taken during the testings that 
proof that this PoC works 

	
## HAPPY INTERCEPTION!!!	:-)

	
	
	
	
	
	

