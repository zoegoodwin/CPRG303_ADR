Navigation |
[Application Type](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/App_Type.md) |
[UI Framework](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/UI_Framework.md) |
[Backend Language](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Backend_Language.md) |
[Permissions](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Permissions.md) |
[Data Storage](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Data_Storage.md) |
[Additional](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Additional.md) |

# Data Storage

## Status

What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?

## Context

- **Security:** Ensure and maintain end users' trust and business by encrypting stored data and communicated data.
- **User Behaviour:** Use a third-party cloud-based storage solution to manage and analyze user purchasing data.
- **User Data:** Use a third-party cloud-based storage solution to manage users' shipping, billing, order, and payment data.
- **Product Data** Use a third-party cloud-based storeage solution to manage product information and media, inventory levels, and pricing information.

## Decision

Investigate the above mentioned third-party solutions and consult with the client on costs.

## Consequences

Costs increase with scaling up, integrations with the application may be difficult, data breaches of third-party storage services, and varying data privacy laws across borders can all cause headaches.
