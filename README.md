# Django-Files-Generator
This Excel VBA program generate Django py files for the whole project
specified in the "Environment" Sheet.
The Data Models of the each APP that makes up the project is specified 
inthe "APP_xxxxxx" Sheet (xxxxx: App Name).
There contains the following sheets:
 -Environmet			The project specifications with Initiation Button	
 -App_Temp			The template sheet for creating 'App_xxxx" Sheet										
 -App_Sample			A sample sheet of "App_xxxxx"						
 -Diagram			Document describing  Generating and Deploying Sequence of this VBA project														
 -App			Work sheet for generation py files of each App										
 -Prjct			Work sheet for generation py files of Project								
 -Tmpl			Template for the py files ( When modify , there need very care )														
 -html			Template for the py "template" files ( When modify , there need very care )	
The attached folder "django" must be setteled in the same folder as this djangoGenerator Excel file.
Also sample specifications on this Gennerator (djangoGenerator0_0Sample.xlsm) and whose generating results of the django specifications py files are attached.
