# Showoff POD

## Deploy Showoff POD

```kubectl apply -f showoff.yaml```

## Showoff renders markdown files from GitHub repository noted in showoff.yaml

```https://github.com/hackathon-team-3/preso```

## Presenter connects to showoff via external LB port (example):

```http://35.236.11.104:30000/presenter```

### Students follow presentation:

```http://35.236.11.104:30000```

