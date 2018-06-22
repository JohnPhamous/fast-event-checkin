# Fast Event Check In

## Planning

- [ ] Use [Auth0's Webtask](https://webtask.io/make) for Express and MongoDB
  - Users can create events
    - Events will have a QR code and an event code
  - Users can see who has checked into their event
- [ ] Create a front end
  - Users can create an account (username/NetID)
  - Users can scan a QR code provided by an organizer to check in
  - Users can enter in a code provided by an organizer to check in
  - When a user signs in, their location and username/NetID are sent to Webtask

## App Flow
![Flow](https://i.imgur.com/0ReLZY0.png)
