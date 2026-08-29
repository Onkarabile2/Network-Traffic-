# Filtering Packets
## overview
- Assists you to Focus on specific Network Traffic that's needed to analyse traffic.
- Display filters let you narrow down traffic by IP, Protocol, Port, Flags, or packet content so that you only focus on what's important.
## importance of filters in Wireshark for real world experiences
# Security Monitoring
- filters such as tcp.analysis.retransmisson or icmp.type ==3 to detect unsual packet behaviour that may signal a scan or attack.
  # Troubleshot
  - Network Engineers rely on tcp.flags.syn ==1 to verify connection initiation or http.response.code == 404 to troubleshoot broken web links
# DNS or Web Debugging
- Filters like dns.resp.name == domain.com and http.request.method == "GET" help diagnose failed DNS resolutions or monitor HTTP behavior.
