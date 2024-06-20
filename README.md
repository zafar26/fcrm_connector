
## Frappe CRM Connector
Frappe CRM Connector is an Open Source integration tool designed to connect Frappe CRM with ERPNext seamlessly,


## Installation
1. [Install bench](https://github.com/frappe/bench).
2. [Install ERPNext](https://github.com/frappe/bench#installation).
3. [Install Frappe CRM](https://github.com/frappe/crm?tab=readme-ov-file#local-setup).
4. Once ERPNext, Frappe CRM is installed, add the FCRM Connector app to your bench by running

    ```sh
    $ bench get-app https://github.com/zafar26/fcrm_connector.git
    ```
4. After that, you can install the fcrm_connector app on the required site by running
    ```sh
    $ bench --site sitename install-app fcrm_connector
    ```

#### License

mit
