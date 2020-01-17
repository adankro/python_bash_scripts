
# python_bash_scripts
Useful scripts for python users.

1.virtual environments handlers:
shortcuts to create or delete environments and register or un register the alias.

These scripts are for mac-os I will add the linux version soon.
pre-steps:

1.-install python versions

2.-install virtual environment pip librarie.:
  -pip install virtualenv


*setup the setup script create alias for newenv and deleteenv on .bash_profile
and create .environments folder on user home if not exist to storage the virtuals enviroments.
$:source setup
Now you can use the newenv to create new a new virtual environment and it going to add to the .environments
newenv name python_version
after it you can use the environment name to activate it.

to delete an environment an unregister it from .bash_profiles just use:
deleteenv env_name
confirm and the folder and alias will be removed.



