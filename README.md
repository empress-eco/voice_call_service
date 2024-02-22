<div align="center">
![Project Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
<h1 align="center">Voice Call Service: Empowering Customer Interaction</h1>
<p align="center">
Voice Call Service is an innovative application extension that simplifies call management and enhances customer interaction.
<br />
<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/voice_call_service/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/voice_call_service/issues">Request Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
Voice Call Service is a comprehensive ticketing solution extension tailored for any Empress, Empress, or Custom App. It enables effortless tracking of inbound and outbound calls, designed specifically for businesses seeking to streamline customer interactions and optimize call management.

### 🌟 Key Features
- Ticket creation on incoming calls
- Agent creation with various statuses (On Call, On Break)
- Click-to-call feature from tickets
- Detailed log generation for each call

## Getting Started

### Prerequisites
To get started, you'll need a Empress, Empress or Custom App where the Voice Call Service can be configured.

### Installation
Use the following steps to get the Voice Call Service running in your environment:

```sh
# Clone the repository
git clone https://github.com/empress-eco/voice_call_service.git

# Navigate to the repository
cd voice_call_service

# Install the app
bench get-app digital_sewa https://github.com/empress-eco/voice_call_service.git --branch version-14
bench --site {site_name} install-app digital_sewa
```

### Usage
After installing the extension, configure it by copying the token from your Servetel account and pasting it in the dialer settings authorization. Create agents in Servetel, ensuring the same data is created on the ERP side. When a call is made to the caller ID, a new DS ticket will be created, or an existing one will be updated.

## Contributing
We warmly welcome your contributions! Here's how you can contribute:

- Fork the project
- Create a feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

We also extend our gratitude to all our users for their invaluable feedback and suggestions. Your contributions help us continuously improve, making Voice Call Service better for everyone.