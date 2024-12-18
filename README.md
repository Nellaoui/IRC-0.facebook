# IRC Server (0.Facebook.com) 🌐

A C++ Internet Relay Chat (IRC) server implementation that allows real-time messaging and channel management.

## 📝 Overview

This IRC server is a complete implementation of a chat system that supports multiple clients, authentication, channels, and private messaging. Built with C++, it focuses on non-blocking I/O operations and network protocol implementation.

## 🌟 Features

### Core Functionality
- Multi-client support
- User authentication system
- Real-time messaging
- Channel management
- Operator privileges
- Private messaging system

### Supported Commands

| Command | Description |
|---------|-------------|
| `NICK` | Set or change user nickname |
| `USER` | Set username and realname at connection start |
| `JOIN` | Join specified channel(s) |
| `PRIVMSG` | Send private messages to users or channels |
| `KICK` | Force remove a user from a channel |
| `INVITE` | Invite users to a channel |
| `TOPIC` | View or change channel topics |
| `MODE` | Set/remove channel or user modes |
| `KILL` | Close connection between client and server (Operator only) |
| `LIST` | View list of channels and their information |
| `MOTD` | View server's "Message of the Day" |
| `NAMES` | View nicknames in a channel |
| `OPER` | Obtain IRC operator privileges |
| `PART` | Leave specified channel(s) |
| `PASS` | Set connection password |
| `PING` | Check connection status |
| `QUIT` | Terminate client connection |
| `NOTICE` | Send notices to users or channels |

### Channel Modes
- `b` - Ban mask
- `k` - Channel key
- `m` - Moderated channel
- `o` - Operator privilege
- `p` - Private channel
- `s` - Secret channel
- `t` - Topic settable by channel operator only
- `v` - Voice privilege

### User Modes
- `i` - Invisible
- `o` - Operator status

## 🚀 Getting Started

### Prerequisites
- C++ compiler
- Make
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nellaoui/IRC-0.facebook.git
cd IRC-0.facebook
```

2. Build the project:
```bash
make
```

### Usage

1. Start the server:
```bash
./ircserv <port> <password>
```
Example:
```bash
./ircserv 6667 mypassword
```

⚠️ **Note**: This is a server implementation. You'll need an IRC client to connect and test the functionality.

## 💻 Connecting with a Client

1. Use any standard IRC client (e.g., HexChat, irssi)
2. Configure your client to connect to:
   - Server: localhost (or server IP)
   - Port: (your specified port)
   - Password: (your specified password)

## 🔒 Security Features

- Password-protected server access
- Operator authentication system
- Channel operator privileges
- Ban system implementation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is part of the 42 School curriculum. Please check with 42's policy regarding code usage and distribution.

## 👥 Authors

- [@Nellaoui](https://github.com/Nellaoui)

## 🙏 Acknowledgments

- 42 School for the project requirements
- IRC protocol documentation
- All contributors to the project
