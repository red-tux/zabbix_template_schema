# zabbix_template_schema
Schema Definition file for writing Zabbix templates using VS Code and other tools

To use in VS code install the YAML extension from Red Hat.

Clone the reppo to a location on your system

Edit your local settings.json file and add a section "yaml.schemas".  The follwoing is an example

````
    "yaml.schemas": {
        "file:///home/anelson/zabbix/templates/zabbix_template_schema.json": "/*"
    }
}
````
