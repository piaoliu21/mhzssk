
[gcr.io/google-appengine/docker-image-base-deducer](https://hub.docker.com/r/anjia0532/google-appengine.docker-image-base-deducer/tags/)
-----


[gcr.io/google-appengine/docker-image-base-deducer:latest](https://hub.docker.com/r/anjia0532/google-appengine.docker-image-base-deducer/tags/)
<!-- BEGIN MUNGE: GENERATED_TOC -->
- [v1.15.2](#v1152)
  - [Downloads for v1.15.2](#downloads-for-v1152)
- [v1.15.3](#v1153)
  - [Downloads for v1.15.3](#downloads-for-v1153)
    - [Client Binaries](#client-binaries)
    - [Server Binaries](#server-binaries)
    - [Node Binaries](#node-binaries)
  - [Changelog since v1.15.1](#changelog-since-v1151)
- [v1.15.1](#v1151)
  - [Downloads for v1.15.1](#downloads-for-v1151)
  - [Changelog since v1.15.2](#changelog-since-v1152)
    - [Other notable changes](#other-notable-changes)
- [v1.15.2](#v1152)
  - [Downloads for v1.15.2](#downloads-for-v1152)
    - [Client Binaries](#client-binaries-1)
    - [Server Binaries](#server-binaries-1)
    - [Node Binaries](#node-binaries-1)
  - [Changelog since v1.15.0](#changelog-since-v1150)
    - [Other notable changes](#other-notable-changes)
- [v1.15.0](#v1150)
  - [Downloads for v1.15.0](#downloads-for-v1150)
  - [Changelog since v1.15.1](#changelog-since-v1151)
- [v1.15.1](#v1151)
  - [Downloads for v1.15.1](#downloads-for-v1151)
    - [Client Binaries](#client-binaries-2)
    - [Server Binaries](#server-binaries-2)
    - [Node Binaries](#node-binaries-2)
  - [Changelog since v1.15.0](#changelog-since-v1150)
    - [Other notable changes](#other-notable-changes-1)
- [v1.15.0](#v1150)
  - [Downloads for v1.15.0](#downloads-for-v1150)
    - [Client Binaries](#client-binaries-3)
    - [Server Binaries](#server-binaries-3)
    - [Node Binaries](#node-binaries-3)
- [Kubernetes v1.15 Release Notes](#kubernetes-v115-release-notes)
  - [1.15 What’s New](#115-whats-new)
      - [Continuous Improvement](#continuous-improvement)
@@ -53,7 +60,7 @@
    - [CLI Improvements](#cli-improvements)
    - [Misc](#misc)
  - [API Changes](#api-changes)
  - [Other notable changes](#other-notable-changes-1)
  - [Other notable changes](#other-notable-changes-2)
    - [API Machinery](#api-machinery-1)
    - [Apps](#apps-1)
    - [Auth](#auth-1)
@@ -78,54 +85,129 @@
    - [Unchanged](#unchanged)
- [v1.15.0-rc.1](#v1150-rc1)
  - [Downloads for v1.15.0-rc.1](#downloads-for-v1150-rc1)
    - [Client Binaries](#client-binaries-3)
    - [Server Binaries](#server-binaries-3)
    - [Node Binaries](#node-binaries-3)
  - [Changelog since v1.15.0-beta.2](#changelog-since-v1150-beta2)
    - [Other notable changes](#other-notable-changes-2)
- [v1.15.0-beta.2](#v1150-beta2)
  - [Downloads for v1.15.0-beta.2](#downloads-for-v1150-beta2)
    - [Client Binaries](#client-binaries-4)
    - [Server Binaries](#server-binaries-4)
    - [Node Binaries](#node-binaries-4)
  - [Changelog since v1.15.0-beta.1](#changelog-since-v1150-beta1)
    - [Action Required](#action-required)
  - [Changelog since v1.15.0-beta.2](#changelog-since-v1150-beta2)
    - [Other notable changes](#other-notable-changes-3)
- [v1.15.0-beta.1](#v1150-beta1)
  - [Downloads for v1.15.0-beta.1](#downloads-for-v1150-beta1)
- [v1.15.0-beta.2](#v1150-beta2)
  - [Downloads for v1.15.0-beta.2](#downloads-for-v1150-beta2)
    - [Client Binaries](#client-binaries-5)
    - [Server Binaries](#server-binaries-5)
    - [Node Binaries](#node-binaries-5)
  - [Changelog since v1.15.0-alpha.3](#changelog-since-v1150-alpha3)
    - [Action Required](#action-required-1)
  - [Changelog since v1.15.0-beta.1](#changelog-since-v1150-beta1)
    - [Action Required](#action-required)
    - [Other notable changes](#other-notable-changes-4)
- [v1.15.0-alpha.3](#v1150-alpha3)
  - [Downloads for v1.15.0-alpha.3](#downloads-for-v1150-alpha3)
- [v1.15.0-beta.1](#v1150-beta1)
  - [Downloads for v1.15.0-beta.1](#downloads-for-v1150-beta1)
    - [Client Binaries](#client-binaries-6)
    - [Server Binaries](#server-binaries-6)
    - [Node Binaries](#node-binaries-6)
  - [Changelog since v1.15.0-alpha.2](#changelog-since-v1150-alpha2)
  - [Changelog since v1.15.0-alpha.3](#changelog-since-v1150-alpha3)
    - [Action Required](#action-required-1)
    - [Other notable changes](#other-notable-changes-5)
- [v1.15.0-alpha.2](#v1150-alpha2)
  - [Downloads for v1.15.0-alpha.2](#downloads-for-v1150-alpha2)
- [v1.15.0-alpha.3](#v1150-alpha3)
  - [Downloads for v1.15.0-alpha.3](#downloads-for-v1150-alpha3)
    - [Client Binaries](#client-binaries-7)
    - [Server Binaries](#server-binaries-7)
    - [Node Binaries](#node-binaries-7)
  - [Changelog since v1.15.0-alpha.1](#changelog-since-v1150-alpha1)
  - [Changelog since v1.15.0-alpha.2](#changelog-since-v1150-alpha2)
    - [Other notable changes](#other-notable-changes-6)
- [v1.15.0-alpha.1](#v1150-alpha1)
  - [Downloads for v1.15.0-alpha.1](#downloads-for-v1150-alpha1)
- [v1.15.0-alpha.2](#v1150-alpha2)
  - [Downloads for v1.15.0-alpha.2](#downloads-for-v1150-alpha2)
    - [Client Binaries](#client-binaries-8)
    - [Server Binaries](#server-binaries-8)
    - [Node Binaries](#node-binaries-8)
  - [Changelog since v1.15.0-alpha.1](#changelog-since-v1150-alpha1)
    - [Other notable changes](#other-notable-changes-7)
- [v1.15.0-alpha.1](#v1150-alpha1)
  - [Downloads for v1.15.0-alpha.1](#downloads-for-v1150-alpha1)
    - [Client Binaries](#client-binaries-9)
    - [Server Binaries](#server-binaries-9)
    - [Node Binaries](#node-binaries-9)
  - [Changelog since v1.14.0](#changelog-since-v1140)
    - [Action Required](#action-required-2)
    - [Other notable changes](#other-notable-changes-7)
    - [Other notable changes](#other-notable-changes-8)
<!-- END MUNGE: GENERATED_TOC -->

<!-- NEW RELEASE NOTES ENTRY -->


# v1.15.3

[Documentation](https://docs.k8s.io)

## Downloads for v1.15.3


filename | sha512 hash
-------- | -----------
[kubernetes.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes.tar.gz) | `dd9f121bd8c6eadf004b9720d72c338e4d0711bd48ee5763e5f26c576c0743e993c76a13aac3bce69336cb071c9d8461213b0a4f3ccd62dec32f2051e12ff81e`
[kubernetes-src.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-src.tar.gz) | `2f2a304c11e2aaf68e339c970ebd919fa1ce5913e3a6f47ac51be080de9300a7cd91267e637b4fa6cbd945d0de6d4263badb06a6bb3160dc03cd422b0a818963`

### Client Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-client-darwin-386.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-darwin-386.tar.gz) | `04c08da4d25b8a7b80e0211050928458d7bae9d721f96353a886332d60db0aca7350dafb0021124c2d8186313207e32ed07dcc3c8a28065774b5d45a2db4466c`
[kubernetes-client-darwin-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-darwin-amd64.tar.gz) | `d340c797d6a49c7034046a7004285d29066c11ac77fc492651849d101e5e57bb406fbc77b937dea873fc839d134577c719d85c49fac352c3134fc9d149b630f0`
[kubernetes-client-linux-386.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-386.tar.gz) | `16b00092144f04b75b7c7d5b7e9dc1ba5b8038ba68b0ef2edb17e508d87a7e78b876ac7aafd15eb3c5d854d8440dec0d8f5cc9618fe07fc8af5ce0d920d6bda6`
[kubernetes-client-linux-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-amd64.tar.gz) | `93049dcadbe401fc2ed2f53ace598aa4bd183142ec2b7451d2a53e61c4bbc64f393639df166853cbf62c361839f87a386015c0be6b1a9a4d3c9fa84564d376ef`
[kubernetes-client-linux-arm.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-arm.tar.gz) | `6798e066a13ca70bae62540f7387ad803f2431c67b6e0d1d9f21233b5ca045c9a082090e743fb7d26653fb8109a5df3c5b38e607bf005617cee7b1b1bd8089e1`
[kubernetes-client-linux-arm64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-arm64.tar.gz) | `edda1fd33dc78c3557a146c3976d19b88082ea86bdd3f0de6f63c8dec899d6fe7207335edc4ed3b9d123af495fbe019702dfbbc34b0d6f9562330e3968049591`
[kubernetes-client-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-ppc64le.tar.gz) | `8fd023b0c546eca42a53ead1c246d093f9303ac22baf34b6b9910d6d146fdea5742a74fb09bc145d0caeaafb306e92a3ce18f756d7f2d713cdceba28ebf06aa0`
[kubernetes-client-linux-s390x.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-linux-s390x.tar.gz) | `fd15210ef272e65e25e64d9fc0dc62780cb69fc6a6063062d0f3d5e9ed89b46f039fc30d9df3e216ec73df39b96966ab86d1fb52acac606bf8763803878b6289`
[kubernetes-client-windows-386.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-windows-386.tar.gz) | `3688147e3ace45f3e0f5227867dea59ebd3f33e9a973f015257b79aec02bdbc045a355b4ee398ba061fa160ca128701bcdb89f0ade19d6b169ef45ad8c0eccc0`
[kubernetes-client-windows-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-client-windows-amd64.tar.gz) | `78f42ce023bef618cb116f713f0f9e5b2ff8402c2e4ce3ab306a598b642ffa0a9f615db46c42e4a86d96ec84f1001f222c7896746338287f62730062979cf38d`

### Server Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-server-linux-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-server-linux-amd64.tar.gz) | `33f048c350fa0e92857cf8ff61ac7971ad263eb5d4976bd7a2dbe303b6a523948d2a2f9da085d44375d860cdffe1c3e10030e1a9467b9269a23dd7ffa5c8cf83`
[kubernetes-server-linux-arm.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-server-linux-arm.tar.gz) | `acce3e4902dc26c799915cfc607f47a40106982fb2ec2f6b7eed54df30b0cfa74b1f5bbcf3c3d0dfe9d45c0ea2ff86f4d35463b2c1a1c833436005004d674bbe`
[kubernetes-server-linux-arm64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-server-linux-arm64.tar.gz) | `2ea339786c9cc452fa429584715d3034d9a65379f30e467a349f865b2533d26317051aabb590318d5586c803c14ced533e2aaf28f260fab73d83697540f7f91d`
[kubernetes-server-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-server-linux-ppc64le.tar.gz) | `cd64d5331d41213d4101885b6ad6a22438a025c9f752db4333b5728e85d4b50a15a15962c6a4ec0011b38e542dbdb2ea5874db92330d12fb545021ad64e08094`
[kubernetes-server-linux-s390x.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-server-linux-s390x.tar.gz) | `0d028067e32a6532c7377010031bc0d166d24bde0f1bd04c53beb3f8272e872b6d142dd7e9d63f3e088f90266e58eca8fc8bf54f7cdd86e442633a4098d497e3`

### Node Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-node-linux-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-linux-amd64.tar.gz) | `77d7031a5d9f3e4ba5aa66b011982152898b68cc97eca1e9b6f6f5dad4e722ba41e33d66136226c5a7e9c54e5e71257ab3fd8f9ca2233ad616fd5e7ca84052d2`
[kubernetes-node-linux-arm.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-linux-arm.tar.gz) | `d94894a86051c63e5d5c768059c9a1ce88bed6105222e498110dac7980d0ffd92b6821ff8c79e4388dd31f9b5aae03178889da016561541aa5cd672beff4e7e9`
[kubernetes-node-linux-arm64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-linux-arm64.tar.gz) | `9d79049451b2dc3030a1edb62ea826b05a78dad2ffbe9623fe1a8bf235bb29102f0cae133443c95166fcde6469433d814c32379a7b15679843903d1fe165063c`
[kubernetes-node-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-linux-ppc64le.tar.gz) | `c8cad37ce2f67415bbd21bec8e019ef0bb790ebd083d67f62066643d4a5af3670d765322bce01af7d44d18d804a5f729180565886fd65d86562c2dc1df208387`
[kubernetes-node-linux-s390x.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-linux-s390x.tar.gz) | `a8a1bde2451de413a429c15693299525eda1057b1d879899f4f02b6b46af5580b3f20b0afefa3a4661d5a633feaf945a7e076826c844257a87a0898ab9ff4f02`
[kubernetes-node-windows-amd64.tar.gz](https://dl.k8s.io/v1.15.3/kubernetes-node-windows-amd64.tar.gz) | `6010f63e040a6b8f8a8047a4c4a2e1b293ac3a514f2cf3202d494985e9fe0fb8951ad36d29e32337bac4fe68813621c8bee8306f9d7b66b014c64eb714562104`

## Changelog since v1.15.2

### Other notable changes

* Update golang/x/net dependency to bring in fixes for CVE-2019-9512, CVE-2019-9514 ([#81522](https://github.com/kubernetes/kubernetes/pull/81522), [@cblecker](https://github.com/cblecker))
* Update to use go 1.12.8 ([#81390](https://github.com/kubernetes/kubernetes/pull/81390), [@cblecker](https://github.com/cblecker))
* Update to use go 1.12.9 ([#81489](https://github.com/kubernetes/kubernetes/pull/81489), [@BenTheElder](https://github.com/BenTheElder))
* cpuUsageNanoCores is now reported in the Kubelet summary API on Windows nodes ([#80176](https://github.com/kubernetes/kubernetes/pull/80176), [@liyanhui1228](https://github.com/liyanhui1228))
* API: the metadata.selfLink field is deprecated in individual and list objects. It will no longer be returned starting in v1.20, and the field will be removed entirely in v1.21. ([#80978](https://github.com/kubernetes/kubernetes/pull/80978), [@wojtek-t](https://github.com/wojtek-t))
* Fix Azure client requests stuck issues on http.StatusTooManyRequests (HTTP Code 429). ([#81279](https://github.com/kubernetes/kubernetes/pull/81279), [@feiskyer](https://github.com/feiskyer))
* Update the GCE windows node image to include hot fixes since July. ([#81233](https://github.com/kubernetes/kubernetes/pull/81233), [@YangLu1031](https://github.com/YangLu1031))
* switch to VM Update call in attach/detach disk operation, original CreateOrUpdate call may lead to orphaned VMs or blocked resources ([#81208](https://github.com/kubernetes/kubernetes/pull/81208), [@andyzhangx](https://github.com/andyzhangx))
* Fix conflicted cache when the requests are canceled by other Azure operations. ([#81282](https://github.com/kubernetes/kubernetes/pull/81282), [@feiskyer](https://github.com/feiskyer))
* update to use go 1.12.7 ([#80134](https://github.com/kubernetes/kubernetes/pull/80134), [@tao12345666333](https://github.com/tao12345666333))
* Fix public IP not found issues for VMSS nodes ([#80703](https://github.com/kubernetes/kubernetes/pull/80703), [@feiskyer](https://github.com/feiskyer))
* Fixes validation of VolumeAttachment API objects created with inline volume sources. ([#80945](https://github.com/kubernetes/kubernetes/pull/80945), [@tedyu](https://github.com/tedyu))
* Fix kubelet errors in AArch64 with huge page sizes smaller than 1MiB ([#78495](https://github.com/kubernetes/kubernetes/pull/78495), [@odinuge](https://github.com/odinuge))
* kube-addon-manager has been updated to v9.0.2 to fix a bug in leader election (https://github.com/kubernetes/kubernetes/pull/80575) ([#80861](https://github.com/kubernetes/kubernetes/pull/80861), [@mborsz](https://github.com/mborsz))
* Fix a bug that ListOptions.AllowWatchBookmarks wasn't propagating correctly in kube-apiserver. ([#80157](https://github.com/kubernetes/kubernetes/pull/80157), [@wojtek-t](https://github.com/wojtek-t))
* Pass-through volume MountOptions to global mount (NodeStageVolume) on the node for CSI ([#80191](https://github.com/kubernetes/kubernetes/pull/80191), [@davidz627](https://github.com/davidz627))
* Fix error in `kubeadm join --discovery-file` when using discovery files with embedded credentials ([#80675](https://github.com/kubernetes/kubernetes/pull/80675), [@fabriziopandini](https://github.com/fabriziopandini))
* make node lease renew interval more heuristic based on node-status-update-frequency in kubelet ([#80173](https://github.com/kubernetes/kubernetes/pull/80173), [@gaorong](https://github.com/gaorong))
* Bugfix: csi plugin supporting raw block that does not need attach mounted failed ([#79920](https://github.com/kubernetes/kubernetes/pull/79920), [@cwdsuzhou](https://github.com/cwdsuzhou))
* Reduces GCE PD Node Attach Limits by 1 since the node boot disk is considered an attachable disk ([#80923](https://github.com/kubernetes/kubernetes/pull/80923), [@davidz627](https://github.com/davidz627))



# v1.15.2

[Documentation](https://docs.k8s.io)
