**ID** : **`T1133`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |
| 2. | `TA0003` | **Persistence** |

Adversaries may leverage external-facing remote services to initially access and/or persist within a network.

- Remote services such as VPNs, Citrix, and other access mechanisms allow users to connect to internal enterprise network resources from external locations.

- There are often remote service gateways that manage connections and credential authentication for these services.

- Services such as *`Windows Remote Management`* and *`VNC`* can also be used externally.

- Access to **Valid Accounts** to use the service is often a requirement, which could be obtained through *`credential pharming`* or by obtaining the credentials from users after compromising the enterprise network.

- Access to remote services may be used as a redundant or persistent access mechanism during an operation.

- Access may also be gained through an exposed service that doesn’t require authentication. In containerized environments, this may include an exposed Docker API, Kubernetes API server, kubelet, or web application such as the Kubernetes dashboard.