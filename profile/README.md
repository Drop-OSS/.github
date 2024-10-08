## Drop
Drop is an open source game distribution platform.

## Philosophy
Drop is free, open and flexible. As game distribution has a massive array of use-cases, Drop needs to be able to extended and developed for easily. 

## Features

Drop is in it's early stages, so most of this is planned

### Authentication
Drop will support:
 1. Simple login (username/password)
 2. Invitation-based registration
 3. SSO (various providers, or generic)
 4. SSO specific requirements (i.e. part of specific Discord server, particular email domain name, etc)
 5. Multi-provider sign in (can use multiple different methods)
 6. Third-party client sign in & access (for desktop, mobile and other clients)

### Games
Drop will support any format of game, and handles multiple platforms.
 1. Native games for Windows & Linux
 2. First-class support for Wine/Proton in Linux
 3. Custom-install scripts/dependency installation & checking

### P2P / Distributed networking
Drop clients have built-in distributed networking APIs. This means:
 1. Aggregate game downloads
 2. Co-ordinated P2P networking & Remote LAN play over tunnel
 3. Remote Play

All this, while being incredibly secure and safe to expose to the internet. 
