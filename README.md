# open-charts

## Install repos

### Helm

Replace `<name>` with any name you want to call this repo

```
$ helm repo add <name> https://carlosjgp.github.io/open-charts/
"<name>" has been added to your repositories
$ helm repo update
Hang tight while we grab the latest from your chart repositories...
...Successfully got an update from the "<name>" chart repository
Update Complete. ⎈ Happy Helming!⎈ 

# Testing (with Helm 3)
$ helm search repo zipkin
NAME            CHART VERSION	APP VERSION	DESCRIPTION                                       
<name>/zipkin   0.1.0        	2.21.0     	Zipkin is a distributed tracing system. It help...
```

### From source

```
$ git checkout <this repo> <path>
$ helm install --upgrade <flags> <path>/charts/zipkin
```
