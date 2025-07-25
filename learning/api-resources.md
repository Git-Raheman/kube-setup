# Kubernetes API Resources (Sorted List)

| NAME                                      | SHORTNAMES        | APIVERSION                            | NAMESPACED | KIND                                    |
|-------------------------------------------|-------------------|---------------------------------------|------------|-----------------------------------------|
| apiservices                               |                   | apiregistration.k8s.io/v1             | false      | APIService                              |
| bgpconfigurations                         |                   | crd.projectcalico.org/v1              | false      | BGPConfiguration                        |
| bgpfilters                                |                   | crd.projectcalico.org/v1              | false      | BGPFilter                               |
| bgppeers                                  |                   | crd.projectcalico.org/v1              | false      | BGPPeer                                 |
| blockaffinities                           |                   | crd.projectcalico.org/v1              | false      | BlockAffinity                           |
| caliconodestatuses                        |                   | crd.projectcalico.org/v1              | false      | CalicoNodeStatus                        |
| certificatesigningrequests                | csr               | certificates.k8s.io/v1                | false      | CertificateSigningRequest               |
| clusterinformations                       |                   | crd.projectcalico.org/v1              | false      | ClusterInformation                      |
| clusterrolebindings                       |                   | rbac.authorization.k8s.io/v1          | false      | ClusterRoleBinding                      |
| clusterroles                              |                   | rbac.authorization.k8s.io/v1          | false      | ClusterRole                             |
| componentstatuses                         | cs                | v1                                    | false      | ComponentStatus                         |
| configmaps                                | cm                | v1                                    | true       | ConfigMap                               |
| controllerrevisions                       |                   | apps/v1                               | true       | ControllerRevision                      |
| cronjobs                                  | cj                | batch/v1                              | true       | CronJob                                 |
| csidrivers                                |                   | storage.k8s.io/v1                     | false      | CSIDriver                               |
| csinodes                                  |                   | storage.k8s.io/v1                     | false      | CSINode                                 |
| csistoragecapacities                      |                   | storage.k8s.io/v1                     | true       | CSIStorageCapacity                      |
| customresourcedefinitions                 | crd,crds          | apiextensions.k8s.io/v1               | false      | CustomResourceDefinition                |
| daemonsets                                | ds                | apps/v1                               | true       | DaemonSet                               |
| deployments                               | deploy            | apps/v1                               | true       | Deployment                              |
| endpoints                                 | ep                | v1                                    | true       | Endpoints                               |
| endpointslices                            |                   | discovery.k8s.io/v1                   | true       | EndpointSlice                           |
| events                                    | ev                | events.k8s.io/v1                      | true       | Event                                   |
| events                                    | ev                | v1                                    | true       | Event                                   |
| felixconfigurations                       |                   | crd.projectcalico.org/v1              | false      | FelixConfiguration                      |
| flowschemas                               |                   | flowcontrol.apiserver.k8s.io/v1       | false      | FlowSchema                              |
| globalnetworkpolicies                     |                   | crd.projectcalico.org/v1              | false      | GlobalNetworkPolicy                     |
| globalnetworksets                         |                   | crd.projectcalico.org/v1              | false      | GlobalNetworkSet                        |
| horizontalpodautoscalers                  | hpa               | autoscaling/v2                        | true       | HorizontalPodAutoscaler                 |
| hostendpoints                             |                   | crd.projectcalico.org/v1              | false      | HostEndpoint                            |
| ingressclasses                            |                   | networking.k8s.io/v1                  | false      | IngressClass                            |
| ingresses                                 | ing               | networking.k8s.io/v1                  | true       | Ingress                                 |
| ipamblocks                                |                   | crd.projectcalico.org/v1              | false      | IPAMBlock                               |
| ipamconfigs                               |                   | crd.projectcalico.org/v1              | false      | IPAMConfig                              |
| ipamhandles                               |                   | crd.projectcalico.org/v1              | false      | IPAMHandle                              |
| ippools                                   |                   | crd.projectcalico.org/v1              | false      | IPPool                                  |
| ipreservations                            |                   | crd.projectcalico.org/v1              | false      | IPReservation                           |
| jobs                                      |                   | batch/v1                              | true       | Job                                     |
| kubecontrollersconfigurations             |                   | crd.projectcalico.org/v1              | false      | KubeControllersConfiguration            |
| leases                                    |                   | coordination.k8s.io/v1                | true       | Lease                                   |
| limitranges                               | limits            | v1                                    | true       | LimitRange                              |
| localsubjectaccessreviews                 |                   | authorization.k8s.io/v1               | true       | LocalSubjectAccessReview                |
| mutatingwebhookconfigurations             |                   | admissionregistration.k8s.io/v1       | false      | MutatingWebhookConfiguration            |
| namespaces                                | ns                | v1                                    | false      | Namespace                               |
| networkpolicies                           |                   | crd.projectcalico.org/v1              | true       | NetworkPolicy                           |
| networkpolicies                           | netpol            | networking.k8s.io/v1                  | true       | NetworkPolicy                           |
| networksets                               |                   | crd.projectcalico.org/v1              | true       | NetworkSet                              |
| nodes                                     | no                | v1                                    | false      | Node                                    |
| persistentvolumeclaims                    | pvc               | v1                                    | true       | PersistentVolumeClaim                   |
| persistentvolumes                         | pv                | v1                                    | false      | PersistentVolume                        |
| poddisruptionbudgets                      | pdb               | policy/v1                             | true       | PodDisruptionBudget                     |
| pods                                      | po                | v1                                    | true       | Pod                                     |
| podtemplates                              |                   | v1                                    | true       | PodTemplate                             |
| priorityclasses                           | pc                | scheduling.k8s.io/v1                  | false      | PriorityClass                           |
| prioritylevelconfigurations               |                   | flowcontrol.apiserver.k8s.io/v1       | false      | PriorityLevelConfiguration              |
| replicasets                               | rs                | apps/v1                               | true       | ReplicaSet                              |
| replicationcontrollers                    | rc                | v1                                    | true       | ReplicationController                   |
| resourcequotas                            | quota             | v1                                    | true       | ResourceQuota                           |
| rolebindings                              |                   | rbac.authorization.k8s.io/v1          | true       | RoleBinding                             |
| roles                                     |                   | rbac.authorization.k8s.io/v1          | true       | Role                                    |
| runtimeclasses                            |                   | node.k8s.io/v1                        | false      | RuntimeClass                            |
| secrets                                   |                   | v1                                    | true       | Secret                                  |
| selfsubjectaccessreviews                  |                   | authorization.k8s.io/v1               | false      | SelfSubjectAccessReview                 |
| selfsubjectreviews                        |                   | authentication.k8s.io/v1              | false      | SelfSubjectReview                       |
| selfsubjectrulesreviews                   |                   | authorization.k8s.io/v1               | false      | SelfSubjectRulesReview                  |
| serviceaccounts                           | sa                | v1                                    | true       | ServiceAccount                          |
| services                                  | svc               | v1                                    | true       | Service                                 |
| statefulsets                              | sts               | apps/v1                               | true       | StatefulSet                             |
| storageclasses                            | sc                | storage.k8s.io/v1                     | false      | StorageClass                            |
| subjectaccessreviews                      |                   | authorization.k8s.io/v1               | false      | SubjectAccessReview                     |
| tokenreviews                              |                   | authentication.k8s.io/v1              | false      | TokenReview                             |
| validatingadmissionpolicies               |                   | admissionregistration.k8s.io/v1       | false      | ValidatingAdmissionPolicy               |
| validatingadmissionpolicybindings         |                   | admissionregistration.k8s.io/v1       | false      | ValidatingAdmissionPolicyBinding        |
| validatingwebhookconfigurations           |                   | admissionregistration.k8s.io/v1       | false      | ValidatingWebhookConfiguration          |
| volumeattachments                         |                   | storage.k8s.io/v1                     | false      | VolumeAttachment                        |

---



