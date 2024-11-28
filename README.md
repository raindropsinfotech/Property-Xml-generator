# Property XML Feed Generator

**Property XML Feed Generator** is a WordPress plugin that enables you to export and import property details in XML format. It simplifies real estate data management with a user-friendly interface and supports large file operations.

---

## Features
- Export property details to an XML feed.
- Import property details from XML files.

---

## Requirements
- **PHP Version**: >= 7.1  
- **MySQL Version**: >= 5.4  
- **Max Execution Time**: >= 600  
- **Memory Limit**: >= 128M  
- **Post Max Size**: >= 48M  
- **Upload Max Filesize**: >= 48M  
- **WordPress Version**: >= 4.6  

---

## Installation
1. Download the plugin ZIP file.  
2. In your WordPress admin panel, go to **Plugins > Add New**.  
3. Click **Upload Plugin**, select the ZIP file, and click **Install Now**.  
4. After installation, activate the plugin.

---

## Configuration
1. Navigate to **Property XML Feed > Settings** in the WordPress admin panel.  
2. Add Settings data here.  

### Change XML Fields:
1. Go to **Files**.  
2. Open the **Config.php** file, for example: **/test1/wp-content/plugins/property-xml-feed/config.php**.  
3. Update **$xml_structure** variable.
---

## Usage
### Export XML Feed:
1. Go to **Property XML Feed > Export**.  
2. Match with the XML fields.  
3. Click **Generate XML Feed** to create the XML file.

### Import XML Feed:
1. Go to **Property XML Feed > Import**.  
2. Enter the XML Feed Url.  
3. Click **Import XML Feed** and review the logs for results.

---

## Troubleshooting
### Common Issues:
- **Slow feed generation**: Ensure your server meets the requirements and increase memory limits.  
- **Import fails for large files**: Update `post_max_size` and `upload_max_filesize` in your PHP configuration.

---

## Changelog
- **v1.0.0**  
  - Initial release with export and import functionalities.

---

## Support
For any issues or inquiries, contact us at [developer@raindropsinfotech.com].
