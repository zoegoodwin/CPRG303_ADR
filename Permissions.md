Navigation |
[Application Type](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/App_Type.md) |
[UI Framework](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/UI_Framework.md) |
[Backend Language](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Backend_Language.md) |
[Permissions](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Permissions.md) |
[Data Storage](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Data_Storage.md) |
[Additional](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Additional.md) |

# Permissions

## Status

Internet access, network status, and push notifications proposed.

## Context

- **Internet Access:** Connect to the client's server to synchronize application data, update loyalty information, and manage orders.
- **Network Status:** The application needs input on device connectivity so it can trigger the offline mode feature if needed.
- **Push Notifications:** Will enable the end user's device to receive notifications about offers, products, and order updates.

## Decision

Requiring device permissions for internet access, network status, and push notifications in the application.

## Consequences

End users may worry about privacy if too many permissions are requested by the application, so only permissions explicitly required by the client have been listed.
