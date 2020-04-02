## Features
* Improve reference resolving and code completion for Python, XML and JavaScript files in Odoo</li>
* Improve Odoo XML formatter
* Improve structure view for model class
* Quick search and navigate to any XML ID in Odoo project
* ...

## Usage
1. Install this plugin from [Jetbrains Plugins Repository](https://plugins.jetbrains.com/plugin/13499-pycharm-odoo/)
or download and install latest version at [here](https://github.com/trinhanhngoc/pycharm-odoo/releases).
2. Clone [Odoo Stubs](https://github.com/trinhanhngoc/odoo-stubs) and attach to your project to improve code completion.
3. Install [XPathView](https://plugins.jetbrains.com/plugin/12478-xpathview--xslt) to improve code completion in XML inheritance views.
4. A sample project structure that supports multiple odoo versions:
![Project Structure](images/project-structure.png)

## Screenshots
#### Python
![Model name completion](images/model-name-completion.png)

![Go to model declaration](images/go-to-model-declaration.png)

![Model member completion](images/model-member-completion-1.png)

![Model member completion](images/model-member-completion-2.png)

![Model member completion](images/model-member-completion-3.png)

![Field path completion](images/field-path-completion.png)

![XML ID completion](images/xml-id-completion.png)

#### XML
![XML completion](images/xml-completion.png)

#### JavaScript
![JavaScript completion](images/js-completion.png)

## Screencast
https://www.youtube.com/watch?v=SMqepH2A4_4

## Troubleshooting

If the module is installed and configured correctly but you still don't have any autocompletion, it's probably due to Pycharm index caches.

Try running the `Invalidate Caches / Restart` action, this should rebuild index caches from scratch and hopefully fix the issue.
