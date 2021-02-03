# Lucky-Draw-Gaming-Service

*Objective* - Lucky Draw Gaming Service

Design & Implement a service which allows users to get Lucky Draw Raffle tickets
and use one lucky draw raffle ticket to participate in a lucky draw game.

*Functional Requirements*:-

- Design an API which allows users to get the raffle tickets. This API can be
consumed in a lot of ways like We can call this API after the user has placed
an Order.
- Design an API which shows the next Lucky Draw Event timing & the
corresponding reward. For example - Lucky Draw can run everyday at 8AM.
Reward on say 10th Feb is Phone, 11th Feb is Washing Machine etc
- Design an API which allows users to participate in the game. Once a user
has participated with a raffle ticket, she shouldn’t be able to participate
again in the same event.
- Design an API which lists all the winners of all the events in the last one
week.
- Compute the winner for the event and announce the winner


*The Project*:-
This project will allow users to participates in a Raffle using a web application. All the data will be store in a smart contract in the Blockchain (Ethereum).

*Smart Contract*:-
Register tickets. Validate unique email address.

The Smart Contract will have an owner which will be able to:
*Setup*:-

1.Raffle date.

2.Prize (initially just a text description. Real money in the future automatically paid by the contract).

3.Close the tickets sale.

4.List ticket's owners emails.

5.Draw a ticket.

6.Re-draw ticket if previous ticket's owner is not present. Mark previous ticket as drawn annuled

*Limitations*:-
The Smart Contract will be deployed in a test-net by the Raffle owner
