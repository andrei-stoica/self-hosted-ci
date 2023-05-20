# Self Hosted environment for coding
A quick docker compose to spin up tools for hosting your own git environment.

# Starting up

Copy `example.env` to `.env` and fill in all secrets.
Refer to Drone-CI documentation on
[server](https://docs.drone.io/server/overview/) and 
[runner](https://docs.drone.io/runner/overview) for more information.

Run with docker copose
```sh
docker compose up -d
```

## Roadmap
- [X] CI environment (Done)
- [ ] Git server (Gitea) - need to migrate current install to docker environment
