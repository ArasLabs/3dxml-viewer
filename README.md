# 3Dxml Viewer

This package contains a custom viewer to enable the launch of the 3DXML layer from Aras Innovator.

## History

This project and the following release notes have been migrated from the old Aras Projects page. 

Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/3dxml-viewer/releases/tag/v1) | Initial Release

#### Supported Aras Versions

Project | Aras
--------|------
[v1](https://github.com/ArasLabs/3dxml-viewer/releases/tag/v1) | 9.1, 9.2

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **custom-search-mode** import packages

### Install Steps

#### Code Tree Installation

1. Backup your code tree and store the archive in a safe place.
2. Copy the 3dxml.html file in your local `..\3dxml-viewer\` folder
3. Navigate to the root of your install directory and paste this file to `\Innovator\Client\scripts\viewers\`
+ By default your root directory is 	`C:\Program Files\Aras\Innovator`

#### Database Installation

1. Backup your database and store the BAK file in a safe place.
2. Login to Aras Innovator as an administrator
3. Navigate to Administration->File Handling->FileTypes
4. Create a new FileType
	+ Ext: 3dxml
	+ Mime Type: application/octet-stream
5. Navigate to Administration->File Handling->Viewers
6. Create a new Viewer
	+ Name: 3dxml
	+ Path: `./viewers/3dxml.html`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Original idea by Yoann Maingon (@YoannArasLab). Created by Thomas Skogen.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE) for license rights and limitations.
