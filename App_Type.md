Navigation |
[Application Type](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/App_Type.md) |
[UI Framework](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/UI_Framework.md) |
[Backend Language](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Backend_Language.md) |
[Permissions](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Permissions.md) |
[Data Storage](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Data_Storage.md) |
[Additional](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Additional.md) |

# Application Type

## Status

Hybrid Application Proposed


## Context

- **Offline Mode:** To save data locally, hybrid apps can make use of local storage and frameworks. The device can sync with the server once it has reconnected to the internet. The client's offline browsing and order history requirements would be met.
- **Push Notifications:** For push notification providers, hybrid application frameworks offer plugins and integrations. Push notifications can therefore be readily implemented.
- **Payments:** Most payment gateways provide services hybrid apps can use. On both the Android and iOS platforms, hybrid application frameworks can enable safe transactions by using plugins.
- **Analytics:** Analytics programs can be integrated with hybrid applications. User behavior can be tracked and assessed using plugins or libraries.
- **Image Sizes:** Hybrid applications can make use of caching and picture compression techniques to optimize performance.
- **Localization:** Localization is supported by hybrid frameworks, so the application can use a single codebase to adapt to various languages. 


## Decision

Creating a hybrid application for the client will best meet the supplied requirements.


## Consequences

A hybrid application may not perform as well as a native application due to the client's media-heavy requirement. Slow loading times and higher memory and device storage usage may be an issue.
