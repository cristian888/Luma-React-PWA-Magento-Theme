# Luma-React-PWA-Magento-Theme

<img src="https://raw.githubusercontent.com/Genaker/Luma-React-PWA-Magento-Theme/master/web/images/logo.jpeg" alt="Magento React Theme"/>

Blazing-Fast  Default Magento Luma theme on ReactJS UI components PWA features and better performance 

# Installation 
```
 composer require genaker/theme-react-luma --ignore-platform-reqs
 mysql -e "select * from theme"
 bin/magento config:set --scope="default" "design/theme/theme_id" 4 #whatever id you have
```

# Dependencies:

Magento React Theme uses Magento React integration extension (https://github.com/Genaker/reactmagento2/) as a dependency. Extension will be added automaticaly if to install via Composer.

For the best performace You shuld use:
* CSS optimiser tool: (not publicly available)
* Improved Magento FPC: (not publicly available)
* Magento Mictoservices: Laragento/Laragento, PyGento/Python3, NodeJento/NodeJS
* Magento Opcache React GUI: https://github.com/Genaker/Magento2OPcacheGUI
* PWA Magento Extension:https://github.com/Genaker/Magento2PWA
* Magento Open Source Terraform AWS Cloud: https://github.com/Genaker/TerraformMagentoCloud
