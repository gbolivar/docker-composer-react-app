# React Application with Docker Compose and Make

This repository contains a React application containerized using Docker and Docker Compose for easy setup and deployment.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Docker (version 20.x or later)
- Docker Compose (version 2.x or later)

## Installation

Clone this repository:

```bash
git clone git@github.com:gbolivar/docker-composer-react-app.git
cd docker-composer-react-app
```
## Code 
copy your source code to the following path:
```bash
mv /app/myApp frontend 
``` 

## Build the Docker containers:

```bash
# Execute container
docker-compose up -d --build

```
## Usage
### Access the application in your browser:
[LocalHost:3055](http://localhost:3055/)


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html)