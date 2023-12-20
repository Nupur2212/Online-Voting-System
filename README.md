# Online Voting Portal

This project is an implementation of an Online Voting Portal in C, utilizing linked lists to manage voter details and votes. The system allows users to cast their votes for different candidates and includes an admin panel for managing voter details, monitoring vote counts, and adding new voters.

## Features

- **Voting System:** Users can cast their votes for various candidates.
- **Admin Panel:** Admins can view vote counts, the list of voters, and manage voter details.
- **Security:** Voter authentication through Aadhar ID to ensure a secure voting process.
- **Winner Declaration:** The system declares the winner based on the highest number of votes.

## How to Use

1. **Main Logs:**
    - Enter `1` to access the main logs.
    - Options available in main logs:
        - **Vote Entry (Option 1):** Users can give their votes by providing their Aadhar ID.
        - **Admin Panel (Option 2):** Access to administrative functions.
        - **Winner (Option 3):** Displays the current winner.
        - **Exit (Option 4):** Exit the portal.

2. **Voter Insert:**
    - Users need to enter their Aadhar ID.
    - After three unsuccessful attempts, the portal will be closed for security reasons.

3. **Admin Panel:**
    - Admins can perform the following functions:
        - View vote counts.
        - View the list of voters.
        - View the list of voters who have not given their votes.
        - Insert details of a new voter.
        - Exit the admin panel.

4. **Winner:**
    - Displays the current winner based on the highest number of votes.

## Linked List Implementation

The project utilizes linked lists to efficiently manage voter details and votes.
