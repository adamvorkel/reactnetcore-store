# reactnetcore-store

## Database

### SQL Server

The backend tries to connect to a sqlserver database running on the local machine with the system admin db account 'sa' and password 'Passw0rd'.
Obviously connecting in this way would be very bad for production, but is ok for development temporarily.

## Dockerizing plans

Currently a sqlserver docker container can be used for development with port mapping to the default port.
The plan is to dockerize the entire stack

- API
- Client
- Database (sqlserver)
