# Network Traffic Visualization

Visualize network traffic using Python, Wireshark, and Google Maps. Capture packets, extract IPs, map locations, and display data in KML format.

## Prerequisites
- Python 3.x, Wireshark, GeoLiteCity Database
- Python libraries: `dpkt`, `socket`, `pygeoip`

## Installation

git clone https://github.com/your-username/network-traffic-visualization.git
cd network-traffic-visualization
pip install dpkt pygeoip


## Usage
1. Capture traffic in Wireshark and export as .pcap.
2. Place `wire.pcap` in the project root.
3. Run:

      python main.py
   
5. Import the generated .kml into [Google My Maps](https://www.google.com/mymaps).

## License
MIT License - see [LICENSE](LICENSE) for details.

