# Deploy WaveFront

Run the below command which will install the Wavefront Helm chart and configure it the the wavefront api token you provided.

## AWS

```bash
./workload-cluster-setup/scripts/05-install-wavefront.sh
```

## vSphere

```bash
./workload-cluster-setup/scripts/07-install-wavefront.sh
```

## Access wavefront

https://surf.wavefront.com and filter the cluster list to your $VMWARE_ID-service-cluster-name.


![mgmt-cls-2](../img/work-cls-4.png)

Back To [Home](../README.md)
