### api-cache
Cache for UCI APIs

### TODO
- [ ] Create a helm chart for this
- [ ] Deploy to Sunbird Devops
   - [ ] Build Jobs
   - [ ] Artifact Upload Job
   - [ ] Deploy Job
   - [ ] Resource Limits
         - [ ] Dev
         - [ ] Prod
   - [ ] Heath Check
   - [ ] How to run in a cluster mode - HPA (Not worried about the having them separate)
   - [ ] Scaling
         - [ ] 10k 
- [ ] Add invalidation API
- [ ] In UCI APIs invalidate complete cache on any Update, Delete API
- [ ] Invalidate Cache every X hours - Part of VCL.
