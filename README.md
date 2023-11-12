# TorIRC

TorIRC is a robust and secure solution for setting up an IRC server over the TOR network, enhanced with a Filegator file server for simplified file transfers. This project combines the power of InspIRCd and Filegator, ensuring a secure and private communication platform that is easy and fast to deploy.

## Features

- **InspIRCd IRC Server:** A modular and flexible IRC server housed in Docker for secure and anonymous communication over TOR.
- **Filegator File Server:** An integrated file server for fast and secure file transfers, making file sharing within the IRC network seamless.
- **TOR Network Support:** Full TOR network integration for enhanced privacy and security.

## Getting Started

To get started with TorIRC:

1. **Clone the Repository:** Clone this repository to your local machine.
2. **Configure Services:** Modify the configuration files for InspIRCd, TOR, and Filegator as per your requirements.
3. **Deploy with Docker:** Use Docker Compose to deploy the services.

```bash
git clone https://github.com/woo200/tor-irc.git
cd ./tor-irc
sudo docker compose up --build
```

## Prerequisites

- Docker and Docker Compose installed on your machine.
- Basic understanding of Docker, TOR, and IRC server configurations.

## Usage

- After deployment, connect to the IRC server using an IRC client configured to route through the TOR network. (Hexchat w/ tor proxy reccomended)
- Access the Filegator interface through the provided .onion address (port 8080) for file transfers.

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under an MIT license. See the LICENSE file for details.