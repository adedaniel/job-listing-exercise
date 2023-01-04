a mini-dashboard that can displays a given set of jobs and their corresponding orders.

### The Code Layout

Inside of this repository there are two directories:

```shell
.
├── front-end
└── local-api
```

The `front-end` folder is a **Create-React-App**

The `local-api` folder contains a version of an Express-App API. Inside of it we are expecting two endpoints to be implemented `/list` and `/jobs/:jobId` that act as a proxy to the **Remote-API-Source**. There are integrations tests written in [Mocha](https://mochajs.org/)
