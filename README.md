# :space_invader: xpost-by-karma-threshold

A [bot](https://www.reddit.com/r/RequestABot/comments/h79nxv/a_bot_that_automatially_crossposts_every_post/) that automatially crossposts every post where a user has less than the required karma threshold to a different subreddit

## Usage

### Basic
1. Copy/Paste the `.env` and `bot` file to your local environment
2. Add environment variables as needed in `.env`
3. Provision your your base libraries as instructed [here](https://www.reddit.com/r/RequestABot/comments/cyll80/a_comprehensive_guide_to_running_your_reddit_bot/)
4. run `python bot`

### Advanced
1. Clone repo `git clone git@github.com:nickatnight/xpost-by-karma-threshold.git`
2. `cd xpost-by-karma-threshold`
3. Add environment variables as needed in `.env`
4. Provision your your base libraries [here](https://www.reddit.com/r/RequestABot/comments/cyll80/a_comprehensive_guide_to_running_your_reddit_bot/)
5. run `python bot`

### Elite
1. Clone repo `git clone git@github.com:nickatnight/xpost-by-karma-threshold.git`
2. `cd xpost-by-karma-threshold`
3. Add environment variables as needed in `.env`
4. Install [Docker](https://www.docker.com/products/docker-desktop)
2. `docker build -t xpost-by-karma-threshold:latest .`
3. `docker run --env-file .env xpost-by-karma-threshold:latest`
