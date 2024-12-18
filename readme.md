


# lib_Verdaccio

Use this project to have a virtual NPM repository serving most of the needed packages for your Convertigo projects to run Convertigo Studio on an Internet less machine .

# Usage

* Install the project
* run the NgxApp to install dependencies
* then go in the project directory and run 

	```
	./_private/ionic/node_modules/verdaccio/bin/verdaccio --config ./config.yaml
	
	```

This will run the local NPM repository registry.

 * Edit your home directory .npmrc file and add in it 
 
	 ```
	 registry=http://localhost:4873/
	 ```
 
This will instruct Convertigo NPM client to connect to your local registry instead of the unavailable Internet one
 
 
 




For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Library](#mobile-library)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Verdaccio=https://github.com/convertigo/c8oprj-lib-verdaccio.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Verdaccio=https://github.com/convertigo/c8oprj-lib-verdaccio/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Verdaccio__ project


## Mobile Library

Describes the mobile application global properties



