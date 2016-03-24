# Drush

Some useful basic commands

#### Modules
```Shell
drush dl moduleName   # install the module "moduleName" in: sites/all/modules/contrib
```
```Shell
drush pm-uninstall moduleName   # uninstall the module "moduleName"
```

```Shell
drush en moduleName   # enable the module "moduleName" 
```
```Shell
drush pm-disable moduleName   # disable the module "moduleName" 
```

#### Related to the module "Features" 
Note: the module "Features" needs to be installed
If you have created a feature, and made modifications on it after that, you can update your feature folder
without downloading it manually from the admin backoffice, with the command:
```Shell
drush features-update featureSystemName  # update the feature with the system name "featureSystemName" 
``` 