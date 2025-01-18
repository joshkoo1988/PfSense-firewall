<h1>Home Network Setup</h1>

<h2>Description</h2>
Bellow you will find the step by step process I took to create and configure my entire home network behind a PfSense firewall which includes masking outbound traffic through PIA VPN. pihole will be used as an attempt to block unwanted ad's on my entire network. I will be using HaProxy and acme along with my GoDaddy domain and CloudFlare to create a safe secure access to my self-hosted services which will also use full cloudflare encryption,run on HTTPS, and have a SSL certificate.
<br/>


<h2>Hardware</h2>
- <b>VNOPN Micro Firewall</b>
- <b>Managed Switch</b>

<h2>Router & Firewall</h2>
- <b>PfSense</b>
- <b>acme</b>
- <b>pihole</b>
- <b>haproxy</b>
- <b>pia vpn</b>

<h2>Domain & internet security</h2>
- <b>GoDaddy domain</b>
- <b>CloudFlare</b>

<h2>Program walk-through:</h2>

1. Create a boot disk for PfSense using one of the following tools.<br>
  - https://etcher.balena.io/ - https://rufus.ie/downloads/ <br>

2. Open PfSense through bios on target device<br>
  - Plug your newly created boot disk into a USB slot on your target device.<br>
  - Turn on PC and enter bios (Del key for mine) and load up your boot disk on the target device.<br>
3. 
