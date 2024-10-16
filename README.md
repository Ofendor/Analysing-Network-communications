<a href="https://www.linkedin.com/in/emilio-mardones" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn Badge" width="24" height="24" />
</a>
<p style="color: #1e203b; font-size: 16px; font-weight: bold;">Analysing Network Communications</p>

<pre><code style="color: #ff3f31;">Portfolio Activity 1 - DNS and ICMP Traffic Analysis</code></pre>
The tasks showcased in these activities were provided by the Google Cybersecurity Professional Course 2024. All portfolio items represent fictional companies, IP addresses, websites, and emails, used strictly for educational purposes; and provided hands-on experience in real-world cybersecurity practices.  

<p style="color: #1e203b; font-size: 16px; font-weight: bold;">Activity Overview</p>
In this project, I used the information provided by a network protocol analyser to examine DNS and ICMP traffic, focusing on identifying potential security threats. By analysing IP addresses in the TCP/IP model, I gained valuable insight into suspicious data packets and learned how to detect and mitigate risks in a network traffic. 

<p style="font-size: 12px; font-style: italic; color: #4a4a4a;">
  This project reflects my growing expertise in network security and protocol analysis, and my commitment to building a strong foundation for a future cybersecurity career.
</p>

<pre style="background-color: #232256; font-size: 10px;"><code style="color: white;">
<span style="color:#15d314;">13:24:32.192571</span> IP <span style="color:#ff3f31;">192.51.100.15.52444</span> > <span style="color:#ff3f31;">203.0.113.2</span>.domain: 35084+ A? plantbasedrecipes.com. (24)
<span style="color:#15d314;">13:24:36.098564</span> IP <span style="color:#ff3f31;">203.0.113.2</span> > <span style="color:#ff3f31;">192.51.100.15</span>: <span style="color:#fbd266;">ICMP</span> <span style="color:#ff3f31;">203.0.113.2</span> udp port 53 unreachable length 254
<span style="color:#15d314;">13:26:32.192571</span> IP <span style="color:#ff3f31;">192.51.100.15.52444</span> > <span style="color:#ff3f31;">203.0.113.2</span>.domain: 35084+ A? plantbasedrecipes.com. (24)
<span style="color:#15d314;">13:27:15.934126</span> IP <span style="color:#ff3f31;">203.0.113.2</span> > <span style="color:#ff3f31;">192.51.100.15</span>: <span style="color:#fbd266;">ICMP</span> <span style="color:#ff3f31;">203.0.113.2</span> udp port 53 unreachable length 320
<span style="color:#15d314;">13:28:32.192571</span> IP <span style="color:#ff3f31;">192.51.100.15.52444</span> > <span style="color:#ff3f31;">203.0.113.2</span>.domain: 35084+ A? plantbasedrecipes.com. (24)
<span style="color:#15d314;">13:28:50.022967</span> IP <span style="color:#ff3f31;">203.0.113.2</span> > <span style="color:#ff3f31;">192.51.100.15</span>: <span style="color:#fbd266;">ICMP</span> <span style="color:#ff3f31;">203.0.113.2</span> udp port 53 unreachable length 150
</code></pre>

<p style="color: #1e203b; font-size: 16px; font-weight: bold;">Key Takeaways</p>
