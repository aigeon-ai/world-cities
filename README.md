markdown
# World Cities MCP Server

## Overview

The World Cities MCP server provides a powerful and flexible tool for retrieving city, state, and country information based on user-defined search criteria. This service is designed to aid developers in integrating geographic search functionality into their applications with ease. Leveraging a robust database, the MCP server ensures accurate and up-to-date information for various geographic entities.

## Features

- **Flexible Search Criteria**: The server allows users to search for cities, states, or countries using a simple query. The search function is versatile and can be tailored to specific needs by utilizing the `searchby` parameter, which narrows results to either city, state, or country.

- **JSON Response Format**: All search results are returned in a JSON format, making it easy to integrate with modern applications and services.

- **Freemium Pricing Model**: The server operates on a freemium model, offering a basic tier at no cost, with additional paid tiers for users requiring more advanced features or higher usage limits.

- **High Performance**: With a popularity rating of 9.4 and a 99% service level, the server is both reliable and efficient, with an average latency of 1216ms.

## Usage

### Query Tool

The core tool provided by the World Cities MCP server is the Query tool, which allows users to search for geographic entities based on a minimum of three characters in the query string. This tool is essential for applications requiring the lookup of cities, states, or countries.

#### Tool Details

- **Function Name**: Query
- **Description**: Use this tool to search for a city, state, or country that matches the query string provided.
- **Parameters**:
  - `query`: A mandatory string parameter with at least three characters, representing part of the name of a city, state, or country.
  - `searchby`: An optional string parameter to specify whether the search should be limited to "city", "state", or "country".

### Planned Features

- **Enhanced Search Control**: Future updates will include options to control the scope of the search, allowing users to select whether to search among cities, states, countries, or any combination thereof.

- **Additional Data Points**: Upcoming features will include the ability to retrieve country codes and phone codes, with options to select specific data points to be returned.

## Support and Feedback

Users are encouraged to open support tickets for any issues such as incorrect information or missing data. Feedback and suggestions for new features are also welcome to ensure the server meets user needs effectively.

This README provides a comprehensive overview of the World Cities MCP server and its capabilities. For any further inquiries or assistance, please reach out through the support channels provided.