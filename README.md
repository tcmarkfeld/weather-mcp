# Weather MCP Server

A Model Context Protocol (MCP) server that provides weather information tools using the National Weather Service API.

## Features

- **Weather Alerts**: Get active weather alerts for any US state
- **Weather Forecast**: Get detailed weather forecasts for any location using latitude/longitude coordinates

## Tools

### GetAlerts
Get weather alerts for a US state.
- **Parameter**: `state` - The US state to get alerts for
- **Returns**: Active weather alerts including event type, area, severity, description, and instructions

### GetForecast  
Get weather forecast for a location.
- **Parameters**: 
  - `latitude` - Latitude of the location
  - `longitude` - Longitude of the location
- **Returns**: Detailed weather forecast with temperature, wind conditions, and forecast details

## Data Source

This server uses the National Weather Service API (api.weather.gov) to retrieve weather data.
