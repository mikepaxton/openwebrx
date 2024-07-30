# Transmission in Docker for CyberDeck Project

## Prerequisites
- Docker installed on your Raspberry Pi
- Docker Compose installed on your Raspberry Pi

## Sources:
 - https://hub.docker.com/r/linuxserver/transmission

## Instructions
### Step 1: Clone the Repository
```
git clone https://github.com/mikepaxton/Transmission.git
cd transmission
```

### Step 2: Edit docker-compose.yml
- Change the port if needed.  In this example 8170 is the opened hosts port and 9091 is the containers port number.
- Verify both PUID and GUID by typing ID at a terminal prompt.
- Change TZ to match your local country and timezone.
- Modify volumes to reflect the locations of your download and watch folders

### Step 3: Edit .env file
- Add both your desired username and password for the default account.

### Step 4: Run docker compose and verify container runs with no errors
`docker compose up`


### Step 5: If no errors, stop the container
`Ctrl + c`

## Additional Information


