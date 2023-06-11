# rancher-fleet
This repo contains manifests for a couple websites that I host. These are ingested and deployed to a group of single-node rke clusters that I manage. Ingress is load balanced at the DNS layer by Cloudflare.

This topologoy works great for stateless, static sites which were (in my experience) often impacted by etcd and Longhorn errors when deployed on a more traditional multi-node cluster with several etcd and worker nodes. 
