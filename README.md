SimpleIDE
=========

An IDE for GOAL based on JEdit.
This actually is the wrapper that also contains other modules essential for the SimpleIDE.
Please check the IDE module.


Usage
=====

 * Download the jar 
 * Double click the jar to run it 

Release Procedure
=============

Ensure your ~/.m2/settings.xml file is as follows:

```
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
                          http://maven.apache.org/xsd/settings-1.0.0.xsd">
	<servers>
		<server>
   			<id>github</id>
   			<username>YOUR_USERNAME</username>
   			<password>YOUR_PASSWORD</password>
		</server>
	</servers>
</settings>
```

Then call:

```
mvn deploy
```

Note that you must have a public name and e-mail address set on GitHub for this to work correctly (https://github.com/settings/profile)
