# example-voting-app-kubernetes-v2

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) from docker-examples(https://github.com/dockersamples)

modified to work on Kubernetes

Architecture

![architecture](https://user-images.githubusercontent.com/73242630/176510583-31e07f9e-d819-4305-84fa-4457486f81db.png)

A front-end web app in Python or ASP.NET Core which lets you vote between two options
A Redis or NATS queue which collects new votes
A .NET Core, Java or .NET Core 2.1 worker which consumes votes and stores them in…
A Postgres or TiDB database backed by a Docker volume
A Node.js or ASP.NET Core SignalR webapp which shows the results of the voting in real time
