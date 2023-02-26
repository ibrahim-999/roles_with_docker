# Robusta Task

### Requirements:

- docker
- docker-compose

### Seeded data:

- [Please view the seeded data guide](SEEDED.md)

### Postman collection:

- [Please use this link to download the postman collection](https://www.getpostman.com/collections/5786d8e2e442cd249db5)

### Installation:

1.  Clone this repository
2.  `cd docker`
3.  `sh app_install.sh`


### Usage:

- ##### Start the app:

1.  `cd docker`
2.  - `sh app_start.sh`

    - starts nginx web server: http://localhost:8088
    - starts mysql server: (port 3306)

- ##### Stop the app:

1.  `cd docker`
2.  `sh app_stop.sh`

- ##### Executing commands inside the app container:

1.  `cd docker`
2.  `sh attach_terminal.sh`
