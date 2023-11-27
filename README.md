# ARTA ECMS Docs

> Currently Deployed at https://arta.goldcoders.dev

<img  alt="Screenshot 2023-10-17 at 5 41 58 PM" src="./images/home.png">

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`

----

### Services
- Brief description of each service's responsibility.
- Interface definitions (API methods it exposes, if any).
- Basic data models.
- Inter-service dependencies.

### Processes
- Application's startup sequence.
- Workflow describing how a typical request travels through the system.
- Background jobs or tasks.

### Application Architecture
- A brief on the chosen architecture style (Modular Monolith in this case).
- Reasons for choosing this architectural style.
- Data flow diagram (How components interact at a high level).

### Infrastructure
- Cloud services to be used (Google Cloud, in this case).
- Deployment strategy and tools (Docker, Kubernetes).
- Networking configurations like Load Balancers, VPNs, etc.
- Monitoring and logging solutions.
