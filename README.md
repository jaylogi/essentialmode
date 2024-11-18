# EssentialMode

## Support development
Hey, thank you very much for trying out my software. If you'd like to support continued development I'd very much appreciate if you'd pledge any amount to: https://www.patreon.com/gdevelopment

## Description
EssentialMode is a FiveM resource which is used to bring a central management interface for other resources. It handles player data saving like their money, groups and roles and makes these easily usable by other resources.

## Features
- Advanced permission system
- Easily create new commands which can interface with EssentialMode
- Logging for every action if enabled
- Clean readable code
- Attempt at OOP for easy usage

## Installation
Please follow this guide: https://docs.kanersps.pw/docs/essentialmode/installation

## Make sure to set the following convars on the top of your server.cfg
##set es_enableCustomData 1
##add_ace resource.essentialmode command.sets allow
##add_ace resource.essentialmode command.add_principal allow
##add_ace resource.essentialmode command.add_ace allow

##set es_permissionDenied "Pesky rat! You don't have permission for this!!"
##set es_startingCash 100000
##set es_startingBank 0
##set es_enableRankDecorators 1
##set es_moneyIcon "$"
##set es_nativeMoneySystem 0
##set es_commandDelimeter "/"
##set es_enableLogging 1

## Documentation
Documentation for EssentialMode can be found at: https://docs.kanersps.pw/docs/essentialmode/

# Rent a server with EssentialMode pre-installed!
Go to https://zap-hosting.com/EssentialMode and use code `kanersps-a-2529` for 10% off on all products for life! They will even install EssentialMode for you!
