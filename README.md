# hangul
AngularJs2 help tool

Hangul is a simple BASH script that helps to create AngularJs2 project, and edit components.

Usage:
Copy the 'hangul' file to '/usr/bin/' or '/usr/local/bin/':

sudo cp ./hangul /usr/local/bin

Change the access mode:

sudo chmod +x /usr/local/bin/hangul

Now, you can use the terminal command 'hangul'.

Shortcuts:

	new-project NAME
		create a new AngularJS2 project.
	-np Name
		create a new AngularJS2 project. (similar to 'new-project' command)

	install-ambient
		install the project previously created (only use if something went wrong ocurred in 'new-project' command)

	open-project
		open 'index.html' on emacs.

	create-component SELECTOR CLASSNAME 
		create a component with 'selector' name and 'class' name.
	-cc SELECTOR CLASSNAME
		create a component with 'selector' name and 'class' name. (similar to 'create-component' command)
	
	edit-component SELECTOR
		edit a previosuly created component on emacs (ts, htm and css).
	-ec SELECTOR
		edit a previosuly created component on emacs: ts, htm and css. (similar to 'edit-component' command)

	remove-component SELECTOR
		remove all files that compounds the component.
	-rc SELECTOR
		remove all files that compounds the component. (similar to 'remove-component' commands)

	create-directive SELECTOR CLASSNAME 
		create a directive with 'selector' name and 'class' name.
	-cd SELECTOR CLASSNAME
		create a directive with 'selector' name and 'class' name. (similar to 'create-directive' command)
	
	edit-directive SELECTOR
		edit a previosuly created directive on emacs.
	-ed SELECTOR
		edit a previosuly created directive on emacs. (similar to 'edit-directive' command)