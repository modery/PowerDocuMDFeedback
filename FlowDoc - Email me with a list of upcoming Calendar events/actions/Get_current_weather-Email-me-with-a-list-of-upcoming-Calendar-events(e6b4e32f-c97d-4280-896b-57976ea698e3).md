﻿# Flow Documentation \- Email me with a list of upcoming Calendar events

| Flow Name                  | Email me with a list of upcoming Calendar events |
| -------------------------- | ------------------------------------------------ |
| Flow Name                  | Email me with a list of upcoming Calendar events |
| Flow ID                    | e6b4e32f\-c97d\-4280\-896b\-57976ea698e3         |
| Documentation generated at | Tuesday, 8 November 2022 2:00 pm                 |
| Number of Variables        | 5                                                |
| Number of Actions          | 28                                               |

- [Overview](../index-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md)
- [Connection References](../connections-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md)
- [Variables](../variables-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md)
- [Triggers & Actions](../triggersactions-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md)

## Get\_current\_weather

| Property   | Value                                                                                              |
| ---------- | -------------------------------------------------------------------------------------------------- |
| Name       | Get\_current\_weather                                                                              |
| Type       | ApiConnection                                                                                      |
| Connection | [![msnweather](../msnweather32.png) MSN Weather](https://docs.microsoft.com/connectors/msnweather) |

### Inputs

| Property       | Value                                                                                                                                                                                                                                                                                                                            |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| test           | test                                                                                                                                                                                                                                                                                                                             |
| host           | <table><tr><td>api</td><td><table><tr><td>runtimeUrl</td><td>https://flow-apim-europe-001-francecentral-01.azure-apim.net/apim/msnweather</td></tr></table></td></tr><tr><td>connection</td><td><table><tr><td>name</td><td>@parameters('$connections')['shared_msnweather']['connectionId']</td></tr></table></td></tr></table> |
| method         | get                                                                                                                                                                                                                                                                                                                              |
| path           | /current/@{encodeURIComponent(items('Apply_to_each')?['Location'])}                                                                                                                                                                                                                                                              |
| queries        | <table><tr><td>units</td><td>Imperial</td></tr></table>                                                                                                                                                                                                                                                                          |
| authentication | @parameters('$authentication')                                                                                                                                                                                                                                                                                                   |

### Next Action(s) Conditions

| Next Action                                                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Set\_CalendarEvents\_variable \[Failed\]](Set_CalendarEvents_variable-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md) |
| [Compose\_Weather \[Succeeded\]](Compose_Weather-Email-me-with-a-list-of-upcoming-Calendar-events(e6b4e32f-c97d-4280-896b-57976ea698e3).md)                       |
