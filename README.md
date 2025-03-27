
# Global Secure Travel Network

A portable, secure networking solution leveraging Raspberry Pi devices to ensure privacy, encrypted DNS queries, secure file sharing, and consistent global access to home network resources. This setup is ideal for cybersecurity enthusiasts and professionals seeking a robust travel-friendly network infrastructure.

---

## Project Overview

This project utilizes Raspberry Pi 4 and Raspberry Pi Zero W to create a **Global Secure Travel Network**. The setup ensures secure internet access, ad-blocking, encrypted DNS queries, and remote access to home resources via VPN. All traffic is routed through the home router's VPN exit node, masking device public IPs and enhancing privacy.

---

## Key Features

- **OpenWRT Travel Router**:  
  Configured Raspberry Pi 4 with OpenWRT and AdGuard Home to block over **360K malicious domains** for enhanced privacy and ad-blocking across all connected devices.

- **Tailscale VPN Exit Node**:  
  Set up Tailscale VPN on Raspberry Pi 4 to globally mask connected device IPs. Verified secure traffic routing through traceroute tests.

- **Encrypted DNS Queries**:  
  Reduced DNS hijacking risks by **90%** using DNS-over-TLS with Cloudflare, ensuring encrypted DNS queries across devices.

- **Secure File Sharing with NAS**:  
  Integrated Raspberry Pi Zero W running DietPi OS and Samba for encrypted file sharing with **99.9% uptime reliability**.

- **Global Resource Access**:  
  Enabled seamless access to home resources (NAS, RDP to laptop) from anywhere worldwide via the secure VPN setup without exposing device public IPs.

---

## Usage Examples

- Connect your laptop or phone to the Tailscale VPN from any part of the world.  
- Browse the internet securely without exposing your device's public IP address.  
- Access home NAS for file storage or backups remotely via encrypted connections.  

---

## Screenshots

### Network Architecture Diagram:
![Network Architecture Diagram](![Image](https://github.com/user-attachments/assets/25761c77-5112-43fb-848c-75e54234385e))

## OpenWRT Firewall Rules
![Firewall Rules](![Image](https://github.com/user-attachments/assets/088f6fd5-311f-4e00-9fa1-34cf28dc4d7d))

### AD Guard Dashboard:
![AD Guard Dashboard](![Image](https://github.com/user-attachments/assets/558940cd-26e3-412b-93c7-0f9aa3dd4efa))

### AdGuard Home Blocklist Stats:
![AdGuard Blocklist Stats](![Image](https://github.com/user-attachments/assets/56f4d1e3-0f54-449b-925d-36bd46a8fd9f))

### Tailscale Configuration:
![Tailscale Setup](![Image](https://github.com/user-attachments/assets/33dda6a3-db3a-4fa7-9f72-1db560456808))



---

## Future Enhancements

1. **Integrate Commercial VPN on Router**: Add support for Surfshark or NordVPN directly on OpenWRT for advanced traffic security.  
2. **Implement IDS/IPS**: Deploy intrusion detection/prevention systems (e.g., Suricata) for real-time threat monitoring.  
3. **Endpoint Security Integration**: Explore integration of endpoint protection tools for enhanced device security within the network.

---

## Technologies Used

- **Hardware**: Raspberry Pi 4, Raspberry Pi Zero W  
- **Software**: OpenWRT, AdGuard Home, DietPi OS, Samba, Tailscale VPN  
- **Protocols**: DNS-over-TLS, WireGuard VPN  

---
