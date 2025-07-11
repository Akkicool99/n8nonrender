# Deploy n8n on Render
- Using render to use n8n an open source program for free. 
- Using the free postgres database of 256mb ram and 1 gb storage
- Only 15 minutes runtime if no changes

# Issues
- I am unable to connect google drive api and google sheets api
- its asking for verification
- currently working on using an alternative api
 
> [!IMPORTANT]
> **View full deployment instructions in the [**Render docs**](https://render.com/docs/deploy-n8n).**

This template defines a [`render.yaml`](https://github.com/render-examples/n8n/blob/main/render.yaml) file you can use to deploy [n8n](https://n8n.io/) on Render. Click **Use this template** in the upper right to copy this template into your account as a new repo.

The `render.yaml` file defines the following resources:

- A web service that pulls and runs the official n8n Docker image
- A Render Postgres database that stores n8n data

Each of the above uses a free instance type by default.
