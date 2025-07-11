<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# Auth Special Interest Group

Covers improvements to Kubernetes authorization, authentication, and cluster security policy.

"All I want is a secure system where it's easy to do anything I want. Is that so much to ask?" - [xkcd](https://xkcd.com/2044 "xkcd")

The [charter](charter.md) defines the scope and governance of the Auth Special Interest Group.

## Meetings
*Joining the [mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-auth) for the group will typically add invites for the following meetings to your calendar.*
* Regular SIG Meeting: [Wednesdays at 11:00 PT (Pacific Time)](https://zoom.us/j/264572674?pwd=NHVXTm14VktMRi8zRmU0aUt1NE9uQT09) (biweekly, you must be signed into a free zoom account to join). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=11%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1woLGRoONE3EBVx-wTb4pvp4CI7tmLZ6lS26VTbosLKM/edit#).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP0VMOZ-V7-5AchXTHAQFzJw).
* Secrets Store CSI Meeting: [Thursdays at 9:00 PT (Pacific Time)](https://zoom.us/j/91272289538?pwd=ZXZFV251Zi82Vnp3cEJrcmVDeGZaZz09) (biweekly, you must be signed into a free zoom account to join). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=9%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1q74nboAg0GSPcom3kLWCIoWg43Qg3mr306KNL58f2hg/edit#).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP0PCFJrlpV6_nR_j_3RtnwI).
* Weekly Issues/PR Triage Meeting: [Mondays at 9:00 PT (Pacific Time)](https://zoom.us/j/264572674?pwd=NHVXTm14VktMRi8zRmU0aUt1NE9uQT09) (weekly, you must be signed into a free zoom account to join). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=9%3A00&tz=PT%20%28Pacific%20Time%29).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* Anish Ramasekar (**[@aramase](https://github.com/aramase)**), Microsoft
* Micah Hausler (**[@micahhausler](https://github.com/micahhausler)**), Amazon
* Rita Zhang (**[@ritazh](https://github.com/ritazh)**), Microsoft

### Technical Leads
The Technical Leads of the SIG establish new subprojects, decommission existing
subprojects, and resolve cross-subproject technical issues and decisions.

* David Eads (**[@deads2k](https://github.com/deads2k)**), Red Hat
* Mo Khan (**[@enj](https://github.com/enj)**), Microsoft
* Jordan Liggitt (**[@liggitt](https://github.com/liggitt)**), Google

## Emeritus Leads

* Eric Chiang (**[@ericchiang](https://github.com/ericchiang)**)
* Eric Tune (**[@erictune](https://github.com/erictune)**)
* Mike Danese (**[@mikedanese](https://github.com/mikedanese)**)
* Tim Allclair (**[@tallclair](https://github.com/tallclair)**)

## Contact
- Slack: [#sig-auth](https://kubernetes.slack.com/messages/sig-auth)
- [Mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-auth)
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fauth)
- GitHub Teams:
    - [@kubernetes/sig-auth-api-reviews](https://github.com/orgs/kubernetes/teams/sig-auth-api-reviews) - API Changes and Reviews
    - [@kubernetes/sig-auth-bugs](https://github.com/orgs/kubernetes/teams/sig-auth-bugs) - Bug Triage and Troubleshooting
    - [@kubernetes/sig-auth-feature-requests](https://github.com/orgs/kubernetes/teams/sig-auth-feature-requests) - Feature Requests
    - [@kubernetes/sig-auth-misc](https://github.com/orgs/kubernetes/teams/sig-auth-misc) - General Discussion
    - [@kubernetes/sig-auth-pr-reviews](https://github.com/orgs/kubernetes/teams/sig-auth-pr-reviews) - PR Reviews
    - [@kubernetes/sig-auth-proposals](https://github.com/orgs/kubernetes/teams/sig-auth-proposals) - Design Proposals
    - [@kubernetes/sig-auth-test-failures](https://github.com/orgs/kubernetes/teams/sig-auth-test-failures) - Test Failures and Triage
- Steering Committee Liaison: Patrick Ohly (**[@pohly](https://github.com/pohly)**)

## Subprojects

The following [subprojects][subproject-definition] are owned by sig-auth:
### audit-logging
Kubernetes API support for audit logging.
- **Owners:**
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/apis/audit](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/apis/audit/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/audit](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/audit/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/plugin/pkg/audit](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/plugin/pkg/audit/OWNERS)
### authenticators
Kubernetes API support for authentication.
- **Owners:**
  - [kubernetes/kubernetes/pkg/apis/authentication](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/authentication/OWNERS)
  - [kubernetes/kubernetes/pkg/kubeapiserver/authenticator](https://github.com/kubernetes/kubernetes/blob/master/pkg/kubeapiserver/authenticator/OWNERS)
  - [kubernetes/kubernetes/pkg/registry/authentication](https://github.com/kubernetes/kubernetes/blob/master/pkg/registry/authentication/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/auth/authenticator](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/auth/authenticator/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/api/authentication](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/api/authentication/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/authentication](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/authentication/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/plugin/pkg/authenticator](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/plugin/pkg/authenticator/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/kubernetes/typed/authentication](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/kubernetes/typed/authentication/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/listers/authentication](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/listers/authentication/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/pkg/apis/clientauthentication](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/pkg/apis/clientauthentication/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/plugin/pkg/client/auth](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/plugin/pkg/client/auth/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/tools/auth](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/tools/auth/OWNERS)
### authorizers
Kubernetes API support for authorization.
- **Owners:**
  - [kubernetes/kubernetes/pkg/apis/authorization](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/authorization/OWNERS)
  - [kubernetes/kubernetes/pkg/apis/rbac](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/rbac/OWNERS)
  - [kubernetes/kubernetes/pkg/kubeapiserver/authorizer](https://github.com/kubernetes/kubernetes/blob/master/pkg/kubeapiserver/authorizer/OWNERS)
  - [kubernetes/kubernetes/pkg/registry/authorization](https://github.com/kubernetes/kubernetes/blob/master/pkg/registry/authorization/OWNERS)
  - [kubernetes/kubernetes/pkg/registry/rbac](https://github.com/kubernetes/kubernetes/blob/master/pkg/registry/rbac/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/auth/authorizer](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/auth/authorizer/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/api/authorization](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/api/authorization/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/api/rbac](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/api/rbac/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/authorization](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/authorization/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/plugin/pkg/authorizer](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/plugin/pkg/authorizer/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/kubernetes/typed/authorization](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/kubernetes/typed/authorization/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/kubernetes/typed/rbac](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/kubernetes/typed/rbac/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/listers/authorization](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/listers/authorization/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/listers/rbac](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/listers/rbac/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/kubectl/pkg/cmd/auth](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/kubectl/pkg/cmd/auth/OWNERS)
### certificates
Certificates APIs and client infrastructure to support PKI.
- **Owners:**
  - [kubernetes/kubernetes/pkg/apis/certificates](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/certificates/OWNERS)
  - [kubernetes/kubernetes/pkg/controller/certificates](https://github.com/kubernetes/kubernetes/blob/master/pkg/controller/certificates/OWNERS)
  - [kubernetes/kubernetes/pkg/registry/certificates](https://github.com/kubernetes/kubernetes/blob/master/pkg/registry/certificates/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/authentication/request/x509](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/authentication/request/x509/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/util/cert](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/util/cert/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/client-go/util/certificate](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/client-go/util/certificate/OWNERS)
### encryption-at-rest
API storage support for storing data encrypted at rest in etcd.
- **Owners:**
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/server/options/encryptionconfig](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/server/options/encryptionconfig/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/apiserver/pkg/storage/value](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/apiserver/pkg/storage/value/OWNERS)
### node-identity-and-isolation
Node identity management (co-owned with sig-lifecycle), and authorization restrictions for isolating workloads on separate nodes (co-owned with sig-node).
- **Owners:**
  - [kubernetes/kubernetes/pkg/controller/certificates/approver](https://github.com/kubernetes/kubernetes/blob/master/pkg/controller/certificates/approver/OWNERS)
  - [kubernetes/kubernetes/pkg/kubelet/certificate](https://github.com/kubernetes/kubernetes/blob/master/pkg/kubelet/certificate/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/admission/noderestriction](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/admission/noderestriction/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/auth/authorizer/node](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/auth/authorizer/node/OWNERS)
### policy-management
API validation and policies enforced during admission, such as PodSecurityPolicy. Excludes run-time policies like NetworkPolicy and Seccomp.
- **Owners:**
  - [kubernetes/kms](https://github.com/kubernetes/kms/blob/main/OWNERS)
  - [kubernetes/kubernetes/pkg/apis/imagepolicy](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/imagepolicy/OWNERS)
  - [kubernetes/kubernetes/pkg/apis/policy](https://github.com/kubernetes/kubernetes/blob/master/pkg/apis/policy/OWNERS)
  - [kubernetes/kubernetes/pkg/registry/policy](https://github.com/kubernetes/kubernetes/blob/master/pkg/registry/policy/OWNERS)
  - [kubernetes/kubernetes/pkg/security/podsecuritypolicy](https://github.com/kubernetes/kubernetes/blob/master/pkg/security/podsecuritypolicy/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/admission/imagepolicy](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/admission/imagepolicy/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/admission/security/podsecuritypolicy](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/admission/security/podsecuritypolicy/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/api/imagepolicy](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/api/imagepolicy/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/api/policy](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/api/policy/OWNERS)
  - [kubernetes/pod-security-admission](https://github.com/kubernetes/pod-security-admission/blob/master/OWNERS)
### secrets-store-csi-driver
Integrates secrets stores with Kubernetes via a CSI volume.
- **Leads:**
  - Anish Ramasekar (**[@aramase](https://github.com/aramase)**), Microsoft
  - Rita Zhang (**[@ritazh](https://github.com/ritazh)**), Microsoft
- **Owners:**
  - [kubernetes-sigs/secrets-store-csi-driver](https://github.com/kubernetes-sigs/secrets-store-csi-driver/blob/master/OWNERS)
- **Contact:**
  - Slack: [#csi-secrets-store](https://kubernetes.slack.com/messages/csi-secrets-store)
  - [Mailing List](https://groups.google.com/forum/#!forum/kubernetes-secrets-store-csi-driver)
### secrets-store-sync-controller
This is a Kubernetes controller that watches for changes to a custom resource and syncs the secrets from external secrets-store as Kubernetes secret.
- **Leads:**
  - Anish Ramasekar (**[@aramase](https://github.com/aramase)**), Microsoft
  - Mo Khan (**[@enj](https://github.com/enj)**), Microsoft
- **Owners:**
  - [kubernetes-sigs/secrets-store-sync-controller](https://github.com/kubernetes-sigs/secrets-store-sync-controller/blob/main/OWNERS)
### service-accounts
Infrastructure implementing Kubernetes service account based workload identity.
- **Owners:**
  - [kubernetes/kubernetes/pkg/controller/serviceaccount](https://github.com/kubernetes/kubernetes/blob/master/pkg/controller/serviceaccount/OWNERS)
  - [kubernetes/kubernetes/pkg/kubelet/token](https://github.com/kubernetes/kubernetes/blob/master/pkg/kubelet/token/OWNERS)
  - [kubernetes/kubernetes/pkg/serviceaccount](https://github.com/kubernetes/kubernetes/blob/master/pkg/serviceaccount/OWNERS)
  - [kubernetes/kubernetes/plugin/pkg/admission/serviceaccount](https://github.com/kubernetes/kubernetes/blob/master/plugin/pkg/admission/serviceaccount/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/externaljwt](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/externaljwt/OWNERS)
### sig-auth-tools
Tooling to automate the SIG Auth project boards
- **Owners:**
  - [kubernetes-sigs/sig-auth-tools](https://github.com/kubernetes-sigs/sig-auth-tools/blob/main/OWNERS)

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
[working-group-definition]: https://github.com/kubernetes/community/blob/master/governance.md#working-groups
<!-- BEGIN CUSTOM CONTENT -->

<!-- END CUSTOM CONTENT -->
