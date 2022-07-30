# davma.io Grafana

> This application is for development only, it is strongly recommended not to use it in production environments.

Grafana - is the open source analytics & monitoring solution for every database.

## How to access to grafana

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Grafana component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-grafana
```

The davmaio-grafana instance automatically gets a public URL in the form of:

```
https://davmaio-grafana-<active-namespace>.apps.playground.napptive.dev
```

## Admin area

The default credentials are:

* User: admin
* Password: admin

**Note**: Please remember to change the user/password for the instance.
To change credentials
```
https://davmaio-grafana-<active-namespace>.apps.playground.napptive.dev/identity/account
```

## References
* https://grafana.com/
* https://grafana.com/docs/