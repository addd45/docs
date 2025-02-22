---
id: index
title: NetDaemon Version 3
---

NetDaemon provides the capability to write home automations for Home Assistant in C#. Version 3 is a rewrite of current V2 runtime. We decided to introduce some breaking changes. The reason is we wanted to make the product long-term good experience for both users and contributor. We beleive this design will accomplish this goal.

## About NetDaemon version 3
This version is in beta state and is under development. It is stable but it could be breaking. It will be nuget version >= `22.2.x` and uses the docker image `netdaemon/netdaemon3`.
Only supported automation API in NetDaemon 3 is using `HassModel` i.e. injecting the `IHaContext` **not** the base class `NetDaemonRxApp`

## Migrating from version 2
If you are a current user of version 2 of NetDaemon runtime please see [migrating from version 2 runtime](v3/app_model/moving_from_v2.md)
:::caution Warning

We are still adding a lot of features so expect things to change.  

:::

The daemon core runtime is distributed as a Home Assistant add-on or as docker container. You can as an alternative deploy your own instance using the template project. Please see [the getting started](v3/started/installation.md) documentation for setup.

:::info
Please note that you need to restart the add-on every time you change a file. C# needs to compile the changes.
:::

## Issues

If you have issues or suggestions of improvements, please [add an issue](https://github.com/net-daemon/netdaemon/issues)

## Discuss the NetDaemon

Please [join the Discord server](https://discord.gg/K3xwfcX) to get support or if you want to contribute and help others.

If you prefer discussing using [github discussions](https://github.com/net-daemon/netdaemon/discussions) your are welcome to post questions and feature requests there. Bugs are reported as issues.





