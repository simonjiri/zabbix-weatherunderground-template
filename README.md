# zabbix-weatherunderground-template
# Weather Underground

## Description

This template is meandata from your meteostation from weather underground api usinh Zabbiz HTTP agent.
this was made for fun and to learn creating zabbix templates.

## How to use

Import the template file ***zabbix-weatherunderground-template.yml*** in Zabbix. 😅
Those macros need to be configured:

- ***{$API_KEY}***: Your  API key from weather underground.
- ***{$STATION_ID}***: Username of View Only user.
- ***{$FORMAT}***: json / yml .
- ***{$UNITS}***: Units: Imperial (English) - e Metric - m Metric SI - s Hybrid UK - h. Defauult m
- ***{$URL}***: Default https://api.weather.com/v2/pws/observations/current.
