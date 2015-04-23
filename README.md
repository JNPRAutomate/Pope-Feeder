# Pope-Feeder
A API driven web service to easily feed data into Juniper's SecIntel service

# API


/api/v1/host/<name>

| METHOD | Description |
|:-------|:----------------------|
| GET    | Gets the current host |
|POST    | Creates a new host with the specified name |
|PUT     | Updates the hosts metadata with the given name |
| DELETE | Removes the current host from the feed |
