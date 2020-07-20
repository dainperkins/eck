# eck

This repo includes example ECK config files for building Elastic Clusters on GKE (I may add more later - at this point I think the only GKE specific config is the SSD Storage Class)

I will also add a command line gcloud config for building a cluster.

## Example 1: GKE Basic Enterprise ECK Implementation
 -  1: Elastic Trial license (optional)
  - 2: SSD Persistent Storage Class
  - 3: Elastic Cluster
   - 3x Master Nodes
   - 3x Ingest Nodes
   - 3x Hot Data
   - 2x Warm Data
   - 1x Cold Data
  - 4: Kibana

   
#### To Do's
- [ ] Add APM
- [ ] RBAC
- [ ] Gcloud Cluster Creation
- [ ] Real SSL Cert
- [ ] Ingest Processor Reqs
