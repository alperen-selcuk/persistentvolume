## multi container PV-PVC example

GOOGLE NFS server command - FILESTORE

````
gcloud filestore instances create nfs-server --project=devops-project-devops --zone=europe-west2-c --tier=STANDARD --file-share=name=devopsdude,capacity=50GB --network=name="default",reserved-ip-range="10.0.0.0/29"
