Welcome to chatwoot-arm64 repo

On your first run, please keep in mind that database prepare is required.

To do that run the command:

$ docker compose run --rm chatwoot-app bundle exec rails db:chatwoot_prepare

and finnaly:

$ docker compose up -d

Access: http://localhost:3000 or http://127.0.0.1:3000

Reference: https://www.chatwoot.com/docs/self-hosted/deployment/docker
