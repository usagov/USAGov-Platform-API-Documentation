# USAGov Platform API Documentation

## On This Page

*   [About the API](#about-the-api)
*   [About the Data](#about-the-data)
*   [Accessing the API](#accessing-the-api)
*   [API Methods](#api-methods)

## About the API

The USAGov Platform API serves as a central source of content for the GSA CMP System. It programmatically returns all of the information contained in the directory, or you can query the API to return just a subset of the available information.

If you are using the USAGov Platform API and have questions, feedback, or want to tell us about your product, please [e-mail us](mailto:usagov-developers@gsa.gov).

## About the Data

There is no schedule for data updates; we update data continually, and as needed. Early versions of the API may have incomplete and inconsistent data. We are working to continually develop the data in our directory records.

If you have suggestions about what types of data you would like to see in the USAGov Platform API, please [e-mail us](mailto:usagov-developers@gsa.gov).

## Accessing the API

Our USAGov Platform API is accessible via HTTP GET requests and does not require a login or API key to use.

The base URL for the API is https://platform-api.usa.gov/api/v1/usagov/. Append the API call and format you’d like to make to this URL.

Currently, two output formats are available:

1.  JSON (such as https://platform-api.usa.gov/api/v1/usagov/directory_records.json)
2.  JSONP (such as https://platform-api.usa.gov/api/v1/usagov/directory_records.jsonp?callback=callmemaybe). When requesting JSONP, you should include a callback parameter with the name of the callback function you would like called.

For the purposes of this documentation, only JSON sample calls and results will be shown.

### API Result Formats

The USAGov Platform API returns results in json, with an optional callback parameter to enable jsonp support.

## API Data Models

To see the full reference for each individual model, see our [reference page](https://github.com/usagov/USAGov-Platform-API-Documentation/wiki/API-Data-Models).
