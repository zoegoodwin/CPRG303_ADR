Navigation |
[Application Type](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/App_Type.md) |
[UI Framework](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/UI_Framework.md) |
[Backend Language](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Backend_Language.md) |
[Permissions](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Permissions.md) |
[Data Storage](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Data_Storage.md) |
[Additional](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/Additional.md) |

# UI Framework

## Status

React Native proposed.

## Context

- **Team Skill Base:** The team already being familiar with JavaScript means learning and implementing React Native will be more efficient.
- **Application Type:** As outlined in the [Application Type document](https://github.com/zoegoodwin/CPRG303_ADR/blob/main/App_Type.md) this will be a hybrid application, which React Native easily supports via UI libraries.
- **Scalability:** Per the client, the ability to scale up the application as their business grows is a requirement. React Native can also support this aspect.
- **Maintainability:** Widespread use in the application development industry and a strong support community means there will be many resources available for React Native in the forseeable future.

## Decision

React Native will be used for the applications UI framework.

## Consequences

React Native upgrades and package compatibility might cause issues because React Native's support ecosystem isn't as established when compared to native platforms.
