sequenceDiagram
    participant client
    participant server

    client->>server:  My Submit button has been clicked, I send you a post to update you data
    server->>client: Alrigth buddy, redirecting you with a 302, go there and make a get
    client->>server: Thanks dude, I have made a get there
    server->>client: Hey, your new page is ready
Note right of client: Client Browser gets the new page
