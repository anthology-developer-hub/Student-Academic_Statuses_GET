# Student_AcademicStatuses_GET

## Description
This API collection fetch data from the 'AcademicStatuses' entity set, returns a list of all academic statuses or details about a specific ID.

## Prerequisites
Postman - latest version

## Installation
To install POSTMAN, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## Authentication
Both endpoints require Basic Authentication. You need to provide your username and password in the request.

## API Enpoints

The `Api_Export.json` file contains the following APIs:

- `GET /ds/campusnexus/AcademicStatuses`: Returns a list of all academic status records.
- `GET /ds/campusnexus/AcademicStatuses({Id})`: Loads academic status details for the given Id.

## Usage

After importing the `Api_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$DOMAIN`: Student Server FQDN
- `$USERNAME`: Your username here
- `$PASSWORD`: Your password here
