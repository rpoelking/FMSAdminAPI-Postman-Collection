# FMSAdminAPI Postman Collection
 API calls to manage your FileMaker Server installation

 **Requires FMS 19** 
 Some calls may require version later.
 These API calls cover up through version 19.4

 Author: Rob Poelking
 Last Updated: 2021-11-24

Recommended that you set up an environment with the following variables
| Variable | Description |
| -------- | --------------------------------------- |
| {{server}} | The host for your server installation | 
| {{version}} | v1, v2, or vLatest |

The following variables are declared with pre-request scripts
| Variable | Description |
| -------- | --------------------------------------- |
| {{username}} | The administrator user name used to log into the server |
| {{password}} | Password to log into the server |
| {{client_id}} | Identifies a logged in user |
| {{machine_id}} | References a web worker on your server network |

The following variables are declared with test scripts
| Variable | Description |
| -------- | --------------------------------------- |
| {{token}} | Created with the "Request Access Token" call and is used for all successive calls for authentication |


