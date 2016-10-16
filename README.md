# Magento 2 Code Generator Tool

## Installation

0. Download `.phar` file:

    `wget https://github.com/staempfli/magento2-code-generator/releases/download/<version>/mg2-codegen.phar` 

0. Make the `.phar` file executable:

    `chmod +x ./mg2-codegen.phar` 

0. If you want to use the command globally on your system:

    `sudo cp ./mg2-codegen.phar /usr/local/bin/mg2-codegen` 

## Usage

0. Go to your module root folder

0. List all templates: `./mg2-codegen.phar template:list` 

0. Generate template: `./mg2-codegen.phar template:generate <template>` 

**NOTE**:
    
* This commands mut be executed on the root module folder where the `registration.php` file is. 

* When creating a new `module`, you must create first the module parent folder and execute the command from there.

## Demo

![Video Demo](docs/img/video-demo.gif)

You can also watch a more detailed video demo in youtube:

* [Create a CRUD EAV Module in just 5 minutes](https://www.youtube.com/watch?v=f8qBnOIRIs4)
    
## Create new Templates
    
### Clone and Install project
 
For that you cannot use the `.phar` binary, so you need to install the project:

* [Clone and Install](docs/clone-install.md)
    
### Contribute with new templates

* If you want to contribute with new templates, just do the following:

    0. Create a new template following the manual: [How to create templates](vendor/staempfli/universal-code-generator/docs/createTemplates.md)
    
### Private Templates

If current templates do not fill your needs, you can easily create your own templates. Just follow the manual:

* [How to create private templates](vendor/staempfli/universal-code-generator/docs/privateTemplates.md)
    
## Prerequisites

- PHP >= 5.6.*

