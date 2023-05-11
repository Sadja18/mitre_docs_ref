**ID** : **`T1195`**

---

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | **`TA0001`** | **Initial Access** |

| Platforms |
| --- |
| `Linux`, `Windows`, `macOS` |

---

Adversaries may manipulate products or product delivery mechanisms prior to receipt by a final consumer for the purpose of data or system compromise.

Supply chain compromise can take place at any stage of the supply chain including:

- Manipulation of development tools.

- Manipulation of a development environment.

- Manipulation of source code repositories (public or private).

- Manipulation of source code in open-source dependencies.

- Manipulation of software update/distribution mechanisms.

- Compromised/infected system images (multiple cases of removable media infected at the factory)[1](https://www.ibm.com/support/pages/storwize-usb-initialization-tool-may-contain-malicious-code).

- Replacement of legitimate software with modified versions. 

- Sales of modified/counterfeit products to legitimate distributors.

- Shipment interdiction.

While supply chain compromise can impact any component of hardware or software, adversaries looking to gain execution have often focused on malicious additions to legitimate software in software distribution or update channels.

Targeting may be specific to a desired victim set or malicious software may be distributed to a broad set of consumers but only move on to additional tactics on specific victims.

Popular open source projects that are used as dependencies in many applications may also be targeted as a means to add malicious code to users of the dependency.