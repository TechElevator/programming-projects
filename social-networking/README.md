# Social Networking

Build a console-based social networking application, similar to Twitter.

## Scenarios

### User Posts a Message

A message is posted to a user's timeline by typing `<user-name> -> <message>`.

    > Alice -> The weather is beautiful today.
    > Bob -> Shoot! We lost!
    > Bob -> Good game though!

### Reading a User's Timeline

A user's timeline showing messages that they post can be viewed by typing in their name `<user-name>`.

    > Alice
    >   The weather is beautiful today. (5 minutes ago)
    > Bob
    >   Good game though! (1 minute ago)
    >   Shoot! We lost! (2 minutes ago)


### Following Another User

A user can subscribe to another user's timeline by typing `<user-name> follows <another-user>`. To view that user's list of aggregated messages, their wall, type `<user-name> wall`.

    > Charlie -> I'm going for a walk today. Anyone want to join?
    > Charlie follows Alice
    > Charlie wall
    >   Charlie - I'm going for a walk today. Anyone want to join? (30 seconds ago)
    >   Alice - The weather is beautiful today. (5 minutes ago)

    > Charlie follows Bob
    > Charlie wall
    >   Charlie - I'm going for a walk today. Anyone want to join? (55 seconds ago)
    >   Bob - Good game though! (1 minute ago)
    >   Bob - Shoot! We lost! (2 minutes ago)
    >   Alice - The weather is beautiful today. (5 minutes ago)

## General Requirements

1. The application must use the console for input and output.
2. The following commands are supported by the application:
    * **posting:** `<user-name> -> <message>`
    * **reading:** `<user-name>`
    * **following:** `<user-name> follows <another-user>`
    * **wall:** `<user-name> wall`
