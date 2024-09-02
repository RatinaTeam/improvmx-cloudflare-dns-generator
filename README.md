# ImprovMX and Cloudflare DNS Records Generator

## Overview
The **ImprovMX and Cloudflare DNS Records Generator** is a simple web-based tool that allows users to quickly generate DNS configuration files for domains using ImprovMX for email forwarding and Cloudflare for DNS management. By entering a domain name, the tool creates a `.txt` file containing all the necessary DNS records, including SOA, MX, TXT (SPF), and CNAME (DKIM, DMARC) records.

## Features
- **Domain Input**: Enter any domain name to generate the DNS records file.
- **Automated File Generation**: Download a `.txt` file pre-filled with DNS records tailored for ImprovMX and Cloudflare.
- **Comprehensive DNS Records**: Includes SOA, MX, TXT, and CNAME records formatted for easy editing and deployment.
- **Informative Template**: The generated file includes instructions and references, ensuring it is easy to update and use in production.

## How to Use
1. Clone the repository , open index.html on browser
2. Enter your domain name in the input field.
3. Click the "Generate .txt File" button.
4. A .txt file with the DNS records will be automatically downloaded.