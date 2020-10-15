# Build and Run Your Application

Before running application, we have to configure it.

1. Change port in `cli-config.yaml` to 5000:5000
2. Duplicate `.env.example` file to `.env` file.
3. From `server/localdev-config.json` file, copy the **api key** and **url**, and paste them into `.env`file

To build and run your application on workspace, run the following commands.

```text
npm install && npm run dev
```

Make sure you can access to your application from localhost:5000

```text
ibmcloud dev build && ibmcloud dev run
```





