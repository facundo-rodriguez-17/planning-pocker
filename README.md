# Epidemic Sounds Assignment - Collaborative planning app

## The settings

In order to estimate how complex a task is for a team of developers to complete, a common
technique that is used is called "planning poker".

- Each developer gets to vote on a task by giving their estimate as a point.
- The set of points you can cast your vote on is usually a predefined set of arbitrary numbers, something like this: 0, 1/2, 1, 2, 3, 5, 8, 13.
- The higher the number, the more complex the task is to complete.

When everyone has cast their votes, the team can have a discussion about what points the different team members have given to a task.

This application should allow the team members to vote on a "task" and visualize the results of the vote in real-time.

The users of the application should be able to do the following:

- Create a poll. A user creates a poll and can share this with other people (this could for example be a code or a link).
- Join a pre-existing poll created by you or someone else. You should be able to cast your vote on different points in a predefined set (0, 1/2, 1, 2, 3, 5, 8, 13). A user can only vote once, but is permitted to change their vote.
- Visualize the results in real-time of a poll: Anyone should be able to see the results of a poll. If user A is casting a vote "2", user B should in real-time be able to see that the point "2" has a value of 1.


## The solution

Pre-requirements:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Running tests

```bash
$ make test
```

### Starting project with docker

```bash
$ make up
```

When finished, open your browser and navigate to [localhost](http://localhost/).

to stop the containers

```bash
$ make down
```

### Running locally

Pre-requirements:
- Python 3.7.2
- Node 14.15.4 y NPM 6.14.10 [Downlod](https://nodejs.org/en/)

```bash
$ make start
```
And in another terminal
```bash
$ make run_front
```


## TODO
- Refresh token
- List poll participants
- Define when poll is finished
- Task filters
- Reverse proxy
