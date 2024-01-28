# Space Weather bot for Telegram

## What for?
This bot suggests convenient API/Telegram bot implementation to get space weather and spacecraft data plots..

## Functional requirements
* 

### Features
* User can get space weather data plots using Telegram bot commands.
* ...

### UI
* Telegram bot interface.
* ...

## Tech requirements

### Tech stack
* [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
* [Python 3.x](https://www.python.org/downloads/)
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) client library
* [PostgreSQL](https://www.postgresql.org/download/)

### SLA
* 99.9% uptime

### Users
* <?> users per day on release

### Storage
Database is used to store user data and bot settings as well as space weather data. 
PostgreSQL is used as a database engine.

#### Space weather data
* Approximate size of the space weather data on beginning of 2024 is <?> Gb.
* Number of records is <?> M.
* Yearly growth is <?> Gb and <?> M records.

## Data providers
* National Oceanic and Atmosferic Administration (NOAA); 
* National Aeronautics and Space Administration (NASA);
* Кисловодская Горная астрономическая станция Главной (Пулковской) астрономической обсерватории РАН (ГАС ГАО РАН);

#### Storage size requirements
* 250 Gb on release;
* 250 Gb per year.
