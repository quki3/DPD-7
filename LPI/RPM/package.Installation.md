	*	SEARCH
- searches are performed using 
- `yum seach package_name` or `dnf search package_name`
- let's say you want to display some text in more irreverent way, but you are not sure about the package that can perform that task, RPM commands accept descriptive terms
- `yum search speaking cow`
	*	INSTALL
- after finding a suitable package at the repository it can be installed with
- `yum install package_name` or `dnf install package_name`
	* REMOVAL
- All the commands accept the remove keyword to unistall
- `sudo yum remove package_name`
