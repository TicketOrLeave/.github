# TicketOrLeave

TicketOrLeave is a modern ticket management system built with Next.js, NextAuth, Server Actions, Fatapi, and PostgreSQL. It provides event organizers with powerful tools for managing ticket sales and attendee data, while offering attendees a seamless experience for discovering and purchasing tickets to events.

## Features

- **Event Management**: Create, customize, and manage events effortlessly through an intuitive interface.
- **Ticket Sales**: Set ticket prices, create seating arrangements, and generate secure QR codes for ticket validation.
- **Attendee Management**: Keep track of attendee data, including ticket purchases and seating preferences.
- **Authentication**: Secure user authentication powered by NextAuth for organizers and attendees.
- **Real-time Updates**: Receive real-time updates on ticket availability and event details.
- **Email-integration**: Receive updates on tickets and organization via email.

## Technologies Used

- **Next.js**: A React framework for building server-rendered and statically-generated web applications.
- **NextAuth**: An authentication library for Next.js applications, providing easy integration with various authentication providers.
- **Server Actions**: Custom server-side logic for handling complex business logic and data processing.
- **Fatapi**: A versatile API framework for building robust backend services.
- **PostgreSQL**: A powerful open-source relational database for storing event and attendee data.

## Demo

### Check out the live demo of TicketOrLeave [here](http://mn-developer.com:3051).

## Getting Started

<!-- ### Prerequisites

- Node.js and npm installed on your machine
- PostgreSQL database instance -->

### Installation

1. Create and navigate a directory contains the server and client of the project
```bash
mkdir TicketOrLeave
cd TicketOrLeave
```


2. Clone the repositories:
```bash
git clone https://github.com/TicketOrLeave/.github
git clone https://github.com/ticketOrLeave/client.git
git clone https://github.com/ticketOrLeave/server.git
```

3. open the docker compose file and add your env variables
```bash
mv .github/docker-compose.yaml .
vim docker-compose.yaml
```

4. Run Docker compose:

```bash
docker-compose up --build
```

## Contributing

Contributions are welcome! If you'd like to contribute to TicketOrLeave, please fork the repository, create a new branch, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors
- [Mahmoud Hamdy](https://github.com/TutTrue)
- [Emad Anwer](https://github.com/EmadAnwer)
- [Mario Nageh](https://github.com/MarioNageh)