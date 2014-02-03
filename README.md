Copyright (c) Autodesk, Inc. All rights reserved 

Permission to use, copy, modify, and distribute this software in
object code form for any purpose and without fee is hereby granted, 
provided that the above copyright notice appears in all copies and 
that both that copyright notice and the limited warranty and
restricted rights notice below appear in all supporting 
documentation.

AUTODESK PROVIDES THIS PROGRAM "AS IS" AND WITH ALL FAULTS. 
AUTODESK SPECIFICALLY DISCLAIMS ANY IMPLIED WARRANTY OF
MERCHANTABILITY OR FITNESS FOR A PARTICULAR USE.  AUTODESK, INC. 
DOES NOT WARRANT THAT THE OPERATION OF THE PROGRAM WILL BE
UNINTERRUPTED OR ERROR FREE.
 
 
Inventor-Attribute-Helper
=======================
An Inventor VB.NET AddIn that helps you view and edit the attributes and attribute sets inside a document.
The project also contains AttributeHelperReadMe.pdf which provides information about its usage.

The installer part of the project in the <strong>"Installer"</strong> subfolder named <strong>"AttributeHelper.iss"</strong> is using <strong>"Inno Setup"</strong>:
http://www.jrsoftware.org/isinfo.php <br />
Note: also select <strong>"Inno Setup Preprocessor"</strong> when installing <strong>"Inno Setup"</strong> if you want to use the <strong>"AttributeHelper.iss"</strong> installer project

Registry free install mechanism for Inventor AddIn's was introduced in Inventor 2012 (v16). The *.addin file of the project however is set for releases 2013 and higher, so if you want to enable it for 2012, you would need to modify the installed AddIn's <strong>"C:\ProgramData\Autodesk\Inventor Addins\Attribute Helper\Autodesk.AttributeHelper.Inventor.addin"</strong> file so that it contains <strong>&lt;SupportedSoftwareVersionGreaterThan&gt;15..&lt;/SupportedSoftwareVersionGreaterThan&gt;</strong>

--------
Written by Brian Ekins <br />
http://www.autodesk.com/adn  

