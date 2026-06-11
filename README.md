# CCNA Practice Questions

A simple and responsive website containing practice questions for the Cisco Certified Network Associate (CCNA) exam. The content is organized according to the official CCNA 200-301 exam domains, making it easy to focus on specific topics and strengthen your networking knowledge.

## Features

* Domain-wise CCNA practice questions
* Clean and responsive user interface
* Easy navigation between exam topics
* Lightweight static website
* Suitable for self-study and exam preparation

## Available Domains

| Domain                       | Description                                               |
| ---------------------------- | --------------------------------------------------------- |
| Network Fundamentals         | Core networking concepts, protocols, and architectures    |
| Network Access               | Switching concepts, VLANs, STP, and wireless fundamentals |
| IP Connectivity              | Routing concepts and IP routing technologies              |
| IP Services                  | DHCP, DNS, NAT, NTP, QoS, and other network services      |
| Security Fundamentals        | Network security concepts and device hardening            |
| Automation & Programmability | SDN, APIs, automation, and controller-based networking    |

## Project Structure

```text
.
├── Automation & Programmability.html
├── IP Connectivity.html
├── IP Services.html
├── Network Access.html
├── Network Fundamentals.html
├── Security Fundamentals.html
├── index.html
├── vercel.json
├── LICENSE
└── README.md
```

## Getting Started

### Clone the Repository

```bash
git clone <your-repository-url>
cd ccna-dumps
```

### Run Locally

Open `index.html` in your browser:

```bash
xdg-open index.html
```

Or use a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This project is configured for deployment on Vercel.

Deploy using:

```bash
vercel
```

Or import the repository directly into the Vercel dashboard.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Vercel

## Disclaimer

This project is intended for educational and practice purposes only. CCNA and Cisco are trademarks of Cisco Systems, Inc. This project is not affiliated with or endorsed by Cisco.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Made with ❤️ for CCNA learners.
