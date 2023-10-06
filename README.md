```plaintext
# Banking System in C Using System Calls

This is a simple banking system implemented in C, utilizing system calls for file operations. The system consists of three main components: `initialize`, `server`, and `client`.

## Initialization
To reset all data in the files, run the following command:
```
./initialize
```

## Server
The server component has `printf` statements for logging purposes, so it should not be run in the background. You can start the server with the following command:
```
./server
```

## Client
Use the client component to interact with the banking system. To run the client, use the following command:
```
./client
```

## Usage

### Admin

1. Log in as an admin with the password 'aditya'.

2. Create a new user account. 
   - An account ID will be assigned.
     - For example, `P 1` for the first user.
     - `S 1` for the second user (if it's a single user account, there will be no second user).
   - By default, the password for the newly created account will be set to the user name.

### User

1. Log in as a user using the user ID and password.
   - Example user ID: `P 1` (the 'P' indicates a primary user).

Please ensure you follow these steps to use the banking system effectively. If you have any questions or encounter issues, refer to the README for guidance.

Feel free to modify this README file to include additional instructions or information specific to your implementatio
```
