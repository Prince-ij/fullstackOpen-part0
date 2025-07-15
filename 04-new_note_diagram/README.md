sequenceDiagram
    participant Client
    participant Server

    Client->>Server: My Submit button has been clicked\nI send you a POST to update your data
    Server-->>Client: Alright buddy, redirecting you with a 302\nGo there and make a GET
    Client->>Server: Thanks dude, I have made a GET there
    Server-->>Client: Hey, your new page is ready
    Note right of Client: Client browser gets the new page
