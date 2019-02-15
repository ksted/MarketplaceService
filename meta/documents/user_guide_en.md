# Service Helper
 
The Service Helper makes it easier for you to offer services on plentyMarketplace by using the ticket system built into plentymarkets. It replaces the need for external webhooks.
 
## Getting started and requirements
 
To use this plugin, you must offer a service on plentyMarketplace. For more information on how to offer services, see the **Further reading** section below. You must also create at least one role, one type and one status in the ticket system. For more information on how to create them, see [here](https://knowledge.plentymarkets.com/en/crm/using-the-ticket-system#700).

After purchasing this plugin, install and activate it. For more information on how to install plugins, see [here](https://knowledge.plentymarkets.com/en/plugins/plugin-sets#adding-plugins).
 
## Plugin configuration
 
After installing the plugin, open the configuration by clicking on its name. Do not change the route in the **Webhook URL** tab. If you change it here, you must change the corresponding part of the **webhookURL** in your service plugin's plugin JSON.

In the **Ticket** tab, enter the IDs of the role, type and status you created earlier. Furthermore, enter the IDs of the users you want to have access to the tickets created when a customer purchases your service. You can find a user's ID by going to **System » Settings » User » Accounts** and clicking on the user's name.

**Save** the settings.

## Further reading

For more information on how to offer your own services, see:
 
* [Services requirements](https://developers.plentymarkets.com/marketplace/services-requirements)
* [Service plugin tutorial](https://developers.plentymarkets.com/tutorials/service-plugin)
 
## License
 
This project is licensed under the GNU AFFERO GENERAL PUBLIC LICENSE - see the [LICENSE.md](/LICENSE.md) file for details.