# WhatsApp Group Member Remover

A Python script to automate the removal of members from WhatsApp groups using Selenium. This tool is especially useful for managing large groups where manual removal is impractical.

## Features

- Automate the process of removing members from WhatsApp groups.
- Supports multiple group management.
- Uses Selenium WebDriver to interact with WhatsApp Web.

## Requirements

- Python 3.x
- Selenium
- ChromeDriver (managed via `webdriver-manager`)
- Google Chrome

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/sagar-18/whatsapp-group-member-remove.git
   cd whatsapp-group-member-remove

2. **Set Up a Virtual Environment**

   ```bash
   git clone https://github.com/sagar-18/whatsapp-group-member-remove.git
   cd whatsapp-group-member-remove

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt

4. **Download ChromeDriver**

ChromeDriver is managed automatically by webdriver-manager. Ensure ChromeDriver is correctly set up for your version of Chrome.

## Usage

1. **Update Script**

   Open `whatsapp-group-member-remove.py` and update the `group_name` variable with the name of your WhatsApp group:

   ```python
   group_name = "your-group-name"  # Replace with the actual group name

2. **Run the Script**

   Make sure you are logged into WhatsApp Web in your browser and have the correct profile set up. Then run the script:

   ```bash
   python whatsapp-group-member-remove.py


The script will:
   Find the group by name.
   Open the Group Info.
   Iterate over the members and remove each one.


## Note: 

The script assumes you have the default WhatsApp Web (WA Business) layout. XPath selectors might need adjustments if WhatsApp updates their UI.




