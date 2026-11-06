# Progress Checklist

## Step 1: Mental model
- [ ] Projects vs namespaces, `oc` vs `kubectl`, web console
- [ ] Routes vs Ingress
- [ ] Security Context Constraints (SCCs)
- [ ] ImageStreams, BuildConfigs, Source-to-Image
- [ ] Operators and OperatorHub

## Step 2: Cluster
- [ ] Developer Sandbox account and login with `oc`
- [ ] OpenShift Local (CRC) running
- [ ] Single Node OpenShift or cloud install

## Step 3: Developer track
- [ ] `oc new-app` + Route
- [ ] Dockerfile fixed for the `restricted` SCC
- [ ] ConfigMaps, Secrets, probes, limits, HPA
- [ ] S2I and BuildConfigs
- [ ] ImageStreams and internal registry
- [ ] Route TLS: edge, passthrough, re-encrypt
- [ ] OpenShift Pipelines (Tekton)
- [ ] OpenShift GitOps (Argo CD)
- [ ] Helm and Kustomize

## Step 4: Security and networking
- [ ] RBAC, ServiceAccounts, SCCs in depth
- [ ] OAuth and identity providers
- [ ] NetworkPolicy and egress control
- [ ] Image security: signing, scanning, pull secrets

## Step 5: Administrator track
- [ ] Cluster architecture and ClusterOperators
- [ ] Install methods: IPI, UPI, Assisted, Agent-based
- [ ] MachineSets, MachineConfig, MachineConfigPools
- [ ] Upgrades and update channels
- [ ] etcd backup and restore
- [ ] Monitoring and logging
- [ ] Storage: CSI, StorageClasses, ODF
- [ ] OLM: installing and managing operators

## Step 6: Advanced
- [ ] Write an operator with Operator SDK
- [ ] Service Mesh
- [ ] Serverless (Knative)
- [ ] Multi-cluster with ACM
- [ ] Troubleshooting: `oc debug`, `must-gather`, `oc adm`

## Step 7: Certification
- [ ] Confirm current exam list on Red Hat's site
- [ ] EX280 (administration)
- [ ] Developer exam

## Step 8: Capstone
- [ ] Spring Boot services deployed via S2I or Tekton
- [ ] PostgreSQL, Redis, Kafka (Strimzi)
- [ ] Argo CD deploying from Git
- [ ] TLS Routes, NetworkPolicies, quotas, dashboards
- [ ] Clean README with architecture diagram
