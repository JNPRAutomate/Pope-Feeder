# Pope-Feeder
A API driven web service to easily feed data into Juniper's SecIntel service

# API


/api/v1/host/<name>

| Method | Description |
|:-------|:----------------------|
| GET    | Gets the current host |
|POST    | Creates a new host with the specified name |
|PUT     | Updates the hosts metadata with the given name |
| DELETE | Removes the current host from the feed |

/api/v1/feed/<name>?format=<type>

| Method | Description |
|:-------|:-----------|
| GET | Returns the feed, CSV format is the default |

|Type| Description |
|:---|:-----|
| csv | returns feed in CSV format, default |
| json | returns feed in JSON format |
| xml | returns feed in XML format |
