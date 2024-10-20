# Download and Segregate Files Based on Name from Github

## Project Overview
This project is part of the Udacity RPA Nanodegree program (Project 1) that focuses on sorting annual reports using UiPath automation. The workflow is designed to download and segregate files based on their names using robotic process automation.

## Built With
- UiPath Studio (Version 20.4.3.0)

## Dependencies
- BalaReva.ZipUnzip.Activities (2019.4.1)
- UiPath.Excel.Activities (2.8.6)
- UiPath.Mail.Activities (1.8.6)
- UiPath.System.Activities (20.4.0)
- UiPath.UIAutomation.Activities (20.4.2)

## Project Features
- Automated file downloading
- File segregation based on naming conventions
- Support for handling Excel operations
- Email automation capabilities
- ZIP/UNZIP functionality

## Prerequisites
1. UiPath Studio (Version 20.4.3.0 or later)
2. Windows Operating System
3. Microsoft Excel

## Installation
1. Clone this repository
2. Open the project in UiPath Studio
3. Ensure all required dependencies are installed (they should install automatically through the project.json)
4. The main workflow is located in `Main.xaml`

## Project Configuration
The project includes the following runtime configurations:
- Auto-dispose: Disabled
- Pausable: Enabled
- User Interaction: Required
- Persistence Support: Disabled
- Expression Language: VisualBasic

## Usage
1. Open the project in UiPath Studio
2. Configure any necessary settings or paths
3. Run the `Main.xaml` workflow

## Privacy & Security
The project is configured to exclude logging of:
- Private data
- Password-related information

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
- Udacity RPA Nanodegree Program
- UiPath Community

--
*This project is part of the Udacity RPA Nanodegree Program.*
