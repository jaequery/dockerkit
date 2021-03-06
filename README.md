# composekit
A Node.js script to work with docker repositories.

# Installation

   ```sh
   $ npm install -g composekit
   $ composekit install
   ```
   
   Just follow the instructions

# Usage

   ```sh
   $ composekit
   composekit: A simple docker-based project starter

   Usage: composekit install|on|off|up|uninstall

   composekit install   - Install docker, docker-compose, docker-machine on the machine
   composekit on|off    - Turn on|off the docker service
   composekit clone     - Clone a github project (eg. honeybadger) and update the VIRTUAL_ENV variable in docker-compose.yml
   composekit up        - Issue docker-compose up -d
   composekit uninstall - Uninstall composekit from the machine
   composekit test      - Test the operation of composekit on your machine

   ```

# Example

```
composekit clone jaequery/jasis mywebsite
cd mywebsite
docker-compose up
```

Voila, head over to http://mywebsite.docker to view your launched website!



