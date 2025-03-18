# RevWhoix Web Interface

A beautiful, premium web interface for the RevWhoix tool, allowing you to perform reverse WHOIS lookups using WhoisXML API.

## Features

- Clean, modern UI with smooth animations
- Responsive design that works on all devices
- Real-time domain filtering
- Copy domains to clipboard
- Export domains as CSV
- Pagination for large result sets

## Installation

1. Make sure you have Python installed (3.6+)
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Make sure you have your WhoisXML API key set up in `~/.config/whoisxml.conf`

## Usage

1. Start the web server:

```bash
python app.py
```

2. Open your browser and navigate to `http://127.0.0.1:5000/`
3. Enter a keyword (organization name, email address, etc.) and click Search
4. View and interact with the domain results

## Screenshots

![RevWhoix Web Interface](https://i.imgur.com/placeholder.png)

## Credits

Built on top of the [RevWhoix CLI tool](https://github.com/devanshbatham/revwhoix) by Devansh Batham.
