# :robot_face: xpost-by-karma-threshold

A base project for creating Reddit bots

## Usage
1. Clone repo `git clone git@github.com:nickatnight/xpost-by-karma-threshold.git`
2. `cd xpost-by-karma-threshold`
3. Add environment variables as needed in `.env`

### Without Docker
- Assuming you've read provisioning basic libs in your local environment [here](https://www.reddit.com/r/RequestABot/comments/cyll80/a_comprehensive_guide_to_running_your_reddit_bot/)
- run `python bot`

### With docker
- Install [Docker](https://www.docker.com/products/docker-desktop)
- `docker build -t xpost-by-karma-threshold:latest .`
- `docker run --env-file .env xpost-by-karma-threshold:latest`
