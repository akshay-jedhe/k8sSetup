Using gcePersistentDisk As type of Volume:
1.first create the gce-pd disk of size you want
gcloud compute disks create --size=5GB --zone=us-central1-a mydisk
2.use that disk name in pod yml specification.
