# Protocol Labs Directory

The Protocol Labs Directory helps network members orient themselves within the network by making it easy to learn about other teams and members, including their roles, capabilities, and experiences.

This repository serves as the index for all information regarding setting up, running and contributing to the directory services including 

- [frontend](https://github.com/memser-spaceport/pln-directory-portal-v2) for all end user directory UI, 
- [backend](https://github.com/memser-spaceport/pln-directory-portal) for all directory backend APIs
- [backoffice](https://github.com/memser-spaceport/pln-directory-portal) for admin related frontend UI

## Setting up directory in local

The directory frontend and backend should be running as individual services communicating through REST. 
The frontend is a standalone NextJS based service
The backend (NestJS) and backoffice(NextJS) reside in same monorepo (will be revamped soon)

At a minimum you need both frontend and backend to be up and running in your local and backoffice is optional if you are not going to do any admin related activities like approving a member or team join request.

### Setting up frontend

Follow the instructions mentioned [here](https://github.com/memser-spaceport/pln-directory-portal-v2)

### Setting up backend and backoffice

Follow the instructions mentioned [here](https://github.com/memser-spaceport/pln-directory-portal)

## Contributing to directory (any service)

Follow the contribution guidelines mentioned [here](https://github.com/memser-spaceport/pln-directory-portal)

## Opening any feature requests / bug reports

Create a new issue in this repository with proper labels (if applicable). Our team will review, identify the appropriate area and move accordingly

## License

All the services fall under the [GNU General Public](https://github.com/memser-spaceport/protocol-labs-directory/blob/main/LICENSE) license.