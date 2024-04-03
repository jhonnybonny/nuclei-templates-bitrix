# nuclei-templates-bitrix
This repository contains nuclei templates for scanning websites built on CMS Bitrix.
## Usage
1. Clone this repository to your local machine:
```bash
git clone https://github.com/jhonnybonny/nuclei-templates-bitrix.git
cd nuclei-templates-bitrix
```
2. Install nuclei if you haven't already. Refer to the [nuclei documentation](https://nuclei.projectdiscovery.io/docs/installation/) for installation instructions.
3. Run nuclei with the Bitrix templates on a list of targets specified in TARGETS.txt:
```bash\n"
nuclei -t . -l TARGETS.txt
```
Replace `TARGETS.txt` with your list of target URLs or IP addresses.
Or, you can run nuclei with the Bitrix templates on a specific URL:
```bash
nuclei -t . -u https://example.com
```
Replace `https://example.com` with the URL of the website you want to scan.
## Customization
You can customize the templates or add new ones according to your requirements. Refer to the [nuclei documentation](https://nuclei.projectdiscovery.io/docs/writing-templates/) for writing custom templates.
## Contributing
Contributions are welcome! If you have new templates or improvements to existing ones, feel free to open a pull request.
## License
This project is licensed under the [MIT License](LICENSE).
