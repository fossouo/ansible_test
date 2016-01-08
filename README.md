### ansible_test

In this project i will start the installation of java 8 using ansible

### first of all create a directory representing ansible project 

	|- group_vars (folder containing variable need in all the project there is need you can set the proxy_env variable)
	|
	|- roles (this foler contain the different roles or group of tasks need to be run)
	|
	|--	oraclejava8
	|	
	|----tasks 
	|	
	|----vars (variable need in a specific role here it is java oracle installation)
	|	
	|----templates (file need in the project as oracle key)
	|	 
	|	(and finally you have the playbook file)
	|	
	|- playbook.yml
