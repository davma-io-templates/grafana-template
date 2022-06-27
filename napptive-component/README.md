# davma.io Grafana

> This application is for development only, it is strongly recommended not to use it in production environments.

Grafana - is the open source analytics & monitoring solution for every database.

Grafana deployment with a single click in NAPPTIVE. Once registered on the platform you can deploy the application from the application catalog.

## Requirements

 - Free account on [NAPPTIVE platform](https://napptive.com/)

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










<!--    

        playground login --patFile D:/Github/no-git/napptive-cli/test_pat.dat
        kubectl --kubeconfig napptive-cli/napptive-kubeconfig create -f napptive-grafana/component/

        playground catalog push davma-io/Grafana:v8.5 napptive-grafana/component/
        playground catalog remove davma-io/Grafana:v1
        
-->