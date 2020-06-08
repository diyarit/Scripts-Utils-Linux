# Scripts-Utils-Linux
Utilities set for Linux. # Utilities
## du.sh
Script that shows the top 10 directories with their consumption on disk.
### How to use
	wget https://raw.githubusercontent.com/wnpower/Scripts-Utils-Linux/master/du.sh && chmod 755 du.sh
	./du.sh /path_a_verificar
	
## fix_journald.sh
Script that repairs journald (symptom: services do not log in correctly).
### How to use
	wget https://raw.githubusercontent.com/wnpower/Scripts-Utils-Linux/master/fix_journald.sh && chmod 755 fix_journald.sh
	./fix_journald.sh

## vps/fix_var_run_symlinks.sh
Did you mean: Script que reparar bug de cPanel cuando se reinicia un servicio mostrando "Too many levels of symbolic links".
109/5000
Script that repairs cPanel bug when restarting a service showing "Too many levels of symbolic links".
### How to use
	wget https://raw.githubusercontent.com/wnpower/Scripts-Utils-Linux/master/vps/fix_var_run_symlinks.sh && chmod 755 fix_var_run_symlinks.sh
	./fix_var_run_symlinks.sh
