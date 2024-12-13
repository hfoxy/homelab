Kubernetes Storage
===

### NVME-oF CSI tools
* simplyblock-csi https://github.com/simplyblock-io/simplyblock-csi
  * Looks to be organisation focussed, maybe limits in the free version?
* spdk-csi (original simplyblock-csi) https://github.com/spdk/spdk-csi
  * Properly open-source but unmaintained since the org version took over
* kubernetes csi-driver-nvmf https://github.com/kubernetes-csi/csi-driver-nvmf
  * More of a spec than an actual usable project. Requires manual configuration for each PVC
