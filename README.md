Magento Live Templates
===============================

##Installation
Place `Magento.xml` in your PHPStorm live template directory.  For more information see [http://www.jetbrains.com/phpstorm/webhelp/live-templates.html]().  

####Windows
Copy `Magento.xml` to 
`<your home directory>\.<product name><version number>\config\templates`

#### MacOS
Copy `Magento.xml` to `~/Library/Preferences/WebIDE<version number>/templates`

#### Linux
Copy `Magento.xml` to `~/.WebIDE<version number>/config/templates`

## Magento Live Templates
This config defines some live templates to speed up Magento development.  To view the list of templates available for an open file simply use the shortcut **CTRL + J** **(CMD + J on Mac)**.

The templates supports:  

- Config XML
- Layout XML
- Templates
- Translation
- Setup

##Examples

	
	mage::gch = <?php echo $this->getChildHtml('$VAR'); ?>
	
	
![](http://ss.wearejh.com/jWfCGmfiPB.gif)


	mage::__ = $this->__('$STRING');	
	
	
![](http://ss.wearejh.com/yCimlbK7D8.gif)
