# Activity log

_100 issue(s) closed in the last 30 days. Generated; do not edit._

## 2026-06-30

- [logical-minds-foundry/.github#14](https://github.com/logical-minds-foundry/.github/issues/14) Epic: ansible-lint compliance gate
- [logical-minds-foundry/mq-resiliency-lab-for-linux#225](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/225) IBM Docs canonical fetch + local cache utility (bypass 403 bot-block)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#246](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/246) Design + build: Native HA + CRR on VMs — RHEL 9 and Ubuntu 24.04 arms
- [logical-minds-foundry/mq-resiliency-lab-for-linux#276](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/276) Make the lab host-arch-aware: run natively on x86 Linux, keep arm64 Mac as dev
- [logical-minds-foundry/mq-resiliency-lab-for-linux#288](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/288) Finish RDQM HA+DR automation — site-rdqm-dr.yml + DR queue manager + cutover (Plan C)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#299](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/299) Publish repo as a signed, semver-tagged release tarball
- [logical-minds-foundry/mq-resiliency-lab-for-linux#327](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/327) RHEL box build is pinned to TCG even on native-x86 hosts
- [logical-minds-foundry/mq-resiliency-lab-for-linux#337](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/337) Cloud: symlink the RHEL DVD from /vergil into the pool instead of a 12 GB copy onto the 29 GB boot disk (ENOSPC pauses nested VMs)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#339](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/339) vm lifecycle: destroy fails on paused guests; create won't start a created-but-stopped guest
- [logical-minds-foundry/mq-resiliency-lab-for-linux#341](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/341) obs up doesn't ensure PKI material (mq_prometheus.p12) before site-obs.yml
- [logical-minds-foundry/mq-resiliency-lab-for-linux#343](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/343) Consolidate fresh-volume prerequisite ensures (galaxy + MQ + PKI) into one helper; add the missing galaxy-collection install
- [logical-minds-foundry/mq-resiliency-lab-for-linux#347](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/347) Research: IBM MQ client identity & authorization model (vendor CCDT/username request)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#352](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/352) docs(reference): extract NativeHA/CRR setup + TLS reference guides for QMNATIVE
- [logical-minds-foundry/mq-resiliency-lab-for-linux#360](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/360) Distributed provision fails on app-client: missing 'acl' package for unprivileged become (mqm)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#368](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/368) Design: reusable-component extraction roadmap (harvest the lab into mq-resiliency-* packages)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#371](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/371) Enable ansible-lint and comply with findings (repo-wide, ~500) — never ran due to ansible/ nesting
- [logical-minds-foundry/mq-resiliency-lab-for-linux#381](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/381) observe phase never runs observability.yml -> cluster-state + node-exporter not on cluster nodes -> empty cluster cockpit / no-data dashboards
- [logical-minds-foundry/mq-resiliency-lab-for-linux#383](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/383) observe phase missing host-obs.yml -> network throughput / lab_network_health panels empty
- [logical-minds-foundry/mq-resiliency-lab-for-linux#385](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/385) fix(libvirt): revert the #376 pool redirect, rely on a larger boot disk — clean rebuild vs cold
- [logical-minds-foundry/mq-resiliency-lab-for-linux#387](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/387) Set the cloud Vergil VM boot disk to 100 GiB (vergil.toml) — cloud only
- [logical-minds-foundry/mq-resiliency-lab-for-linux#389](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/389) fix(nativeha): CRR never connects — Live/Recovery groups have mismatched QMIds (AMQ3256E/3257E)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#390](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/390) fix(observability): lab-nativeha-state collector crashes on BACKLOG(Unknown) → Site B 'no data'
- [logical-minds-foundry/mq-resiliency-lab-for-linux#391](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/391) fix(nativeha): NHARAPP.NHARSVC channel TLS CipherSpec mismatch (AMQ9641E) — app/svc link down
- [logical-minds-foundry/mq-resiliency-lab-for-linux#392](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/392) docs: note the IBM-Docs WebFetch-403 workaround (use tools/ibm_doc_cache.py) in CLAUDE.md
- [logical-minds-foundry/mq-resiliency-lab-for-linux#398](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/398) fix(observability): host-net-state runs the container .venv on the host → lab_network_state never emitted (NHA planes-state panel empty)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#399](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/399) refactor(observability): recolor Recovery group + Leader tiles blue (normal standby, not a warning); add _BLUE/_YELLOW macros
- [logical-minds-foundry/mq-resiliency-lab-for-linux#403](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/403) Enable + enforce the ansible-lint gate (skip_list for deferred cosmetic, exclude lab/)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#405](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/405) Repoint cloud lab host to us-east1-b (reserved N2 capacity)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#407](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/407) Cold-cache bootstrap misses the Ubuntu MQ tarball for commons svc/app (stack provision installs MQ on svc-sim)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#409](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/409) Native HA inter-QM TLS channel NHARAPP.NHARSVC can't start — keystore/SSLKEYR naming mismatch (AMQ9660E)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#414](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/414) ansible-lint gate lints downloaded collections under build/cache (develop red) — exclude build/

## 2026-06-28

- [logical-minds-foundry/mq-resiliency-lab-for-linux#329](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/329) push-rhel-iso.sh fails silently: dead error guard + stale name-match instance resolution
- [logical-minds-foundry/mq-resiliency-lab-for-linux#331](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/331) RHEL box build: surface install progress (heartbeat + latest console line) instead of a silent shut-off wait
- [logical-minds-foundry/mq-resiliency-lab-for-linux#333](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/333) MQ tarball not ensured for manifest-less setups (monitoring): decouple artifact provisioning from manifests
- [logical-minds-foundry/mq-resiliency-lab-for-linux#335](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/335) obs up provisions monitoring without ensuring its MQ tarball (#333 fix only covered vm provision)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#346](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/346) grafana fails to start on fresh obs provision: restart races oss-ac-basic-role-seeder server-lock → permanent 'failed' (verify grafana reachable exit 56)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#350](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/350) Rationalize mqlab CLI namespace: collapse to 4 stacks + consistent end-to-end bootstrap
- [logical-minds-foundry/mq-resiliency-lab-for-linux#351](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/351) QM naming convention: drop the QM prefix; per-stack short names + app/svc role; distinct per-stack service QMs
- [logical-minds-foundry/mq-resiliency-lab-for-linux#355](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/355) Redirect the vagrant dotfile into shared build/state (VAGRANT_DOTFILE_PATH) — stop worktree lab orphaning
- [logical-minds-foundry/mq-resiliency-lab-for-linux#356](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/356) Regression: 'setup_dict is undefined' breaks distributed provision (their-side MQSC / MON.SVRCONN); QMSVC exporter 2540
- [logical-minds-foundry/mq-resiliency-lab-for-linux#366](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/366) QM-naming regression guard didn't ship with #363 (untracked → never committed)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#373](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/373) bootstrap: provision phase doesn't inject stack secrets -> hacluster password fails (#350 regression)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#375](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/375) nativeha-rhel provision: site-B nodes (nha-rhel-b1/2/3) go UNREACHABLE at crtmqm — cloud-box triage
- [logical-minds-foundry/mq-resiliency-lab-for-linux#376](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/376) Redirect libvirt image storage onto the data volume (env-aware) — cloud boot-disk exhaustion (#375)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#377](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/377) bootstrap: provision runs against a STALE ansible inventory (missing cutover aggregate groups) -> acl play no-ops -> mqweb become_user fails
- [logical-minds-foundry/mq-resiliency-lab-for-linux#380](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/380) mqlab fails from a subdirectory: buildenv mis-detects worktree (git-dir absolute vs git-common-dir relative)

## 2026-06-23

- [logical-minds-foundry/mq-resiliency-lab-for-linux#313](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/313) Per-panel command tooltips on the cockpit dashboards (Native HA spike)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#314](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/314) Move vergil-user VM off-platform to GCP (native-x86 nested-KVM, n2-standard-16); commit vergil-audit lifecycle profile
- [logical-minds-foundry/mq-resiliency-lab-for-linux#317](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/317) Add scripts/push-rhel-iso.sh to seed the RHEL DVD onto off-platform lab VMs
- [logical-minds-foundry/mq-resiliency-lab-for-linux#319](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/319) Pin off-platform VM sizing in vergil.toml (move manual develop edit to a branch)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#321](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/321) vergil.toml: declare build-essential — off-platform vagrant gem-install fails on the minimal cloud base (missing libc6-dev)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#323](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/323) box build assumes the vagrant-libvirt management network exists — fails on a fresh host
- [logical-minds-foundry/mq-resiliency-lab-for-linux#325](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/325) build-box.sh not idempotent — a leftover rhel96-build domain from a failed run blocks the retry

## 2026-06-22

- [logical-minds-foundry/mq-resiliency-lab-for-linux#197](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/197) Evaluate complexity/effort of migrating lab automation from Ansible to Salt
- [logical-minds-foundry/mq-resiliency-lab-for-linux#219](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/219) obs: recover the PCMK cluster-cockpit dashboard (lost from Grafana) + build the RDQM cluster view
- [logical-minds-foundry/mq-resiliency-lab-for-linux#244](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/244) feat(hadr): pcmk-rhel Phase 1 — RHEL substrate (Corosync/Pacemaker + iSCSI SAN), code only
- [logical-minds-foundry/mq-resiliency-lab-for-linux#245](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/245) Capture MQ requirements: MQGateway proxy + vendor-initiated datagram/notification queue
- [logical-minds-foundry/mq-resiliency-lab-for-linux#253](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/253) Investigate: exact Pacemaker/Corosync/DRBD versions RDQM bundles vs. our OSS-built versions
- [logical-minds-foundry/mq-resiliency-lab-for-linux#266](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/266) Version manifest per arm build: pin dependency versions for reproducible stacks
- [logical-minds-foundry/mq-resiliency-lab-for-linux#272](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/272) fix(obs): cluster-state collector misreports a healthy DRBD as down/STALE
- [logical-minds-foundry/mq-resiliency-lab-for-linux#279](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/279) obs: Native HA cluster cockpit — port the PCMK cockpit to nativeha-rhel (full 3+3 + CRR)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#282](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/282) Research: MQ JSON-format diagnostic logging → parseable MQ logs for the obs framework (all arms)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#286](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/286) Reorganize build/ into cache/state/work/temp buckets with clear keep-nuke semantics
- [logical-minds-foundry/mq-resiliency-lab-for-linux#287](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/287) RDQM cluster cockpit (lab-rdqm-cluster) — collector + board
- [logical-minds-foundry/mq-resiliency-lab-for-linux#289](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/289) Report: quantify the x86-on-arm64 TCG emulation tax — evidence backing native-x86 platform (#276, #283)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#291](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/291) Add [vm.anonymous] profile for credential-less lab bootstrap testing
- [logical-minds-foundry/mq-resiliency-lab-for-linux#300](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/300) fix(rdqm): tighten RDQM dashboard matrices — drop wasted height + kill horizontal scroll

## 2026-06-21

- [logical-minds-foundry/mq-resiliency-lab-for-linux#304](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/304) feat(build): run 'build ensure' before every mqlab command (root callback)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#305](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/305) build/ bucket wiring is not guaranteed outside mqlab (worktree-creation ensure)

## 2026-06-20

- [logical-minds-foundry/mq-resiliency-lab-for-linux#273](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/273) fleet: sort 'vm status' table by columns left-to-right (Guest first)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#297](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/297) Interactive shell default: separate host venv (.venv-host) on all Vergil VMs to avoid container .venv conflicts

## 2026-06-18

- [logical-minds-foundry/mq-resiliency-lab-for-linux#250](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/250) Design + build: Stage 1 — TLS-secure all pcmk-ubuntu MQ connections
- [logical-minds-foundry/mq-resiliency-lab-for-linux#255](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/255) Expose the IBM MQ Console (browser QM browser) — it's already in our mqweb; forward it like Grafana
- [logical-minds-foundry/mq-resiliency-lab-for-linux#256](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/256) group_vars/all.yml shadowed by group_vars/all/ dir — breaks mqweb provision (#250 regression)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#258](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/258) Lab convenience: open the MQ Console (human UI) only; keep the REST API authenticated; anonymous Grafana
- [logical-minds-foundry/mq-resiliency-lab-for-linux#259](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/259) pki-distribute stash task fails on hosts without acl (become_user unprivileged temp-files)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#262](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/262) fix(grafana): YAML parse error in env drop-in — Jinja block-scalar indentation (#255/#258 regression)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#264](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/264) fix(obs): grafana port-forward relay wedges after 'obs up' restarts grafana — self-heal + fail-loud verify

## 2026-06-17

- [logical-minds-foundry/mq-resiliency-lab-for-linux#178](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/178) MQ Service panel tuning: status string-mappings, queue column cleanup + rate graphs, channel-traffic story
- [logical-minds-foundry/mq-resiliency-lab-for-linux#180](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/180) DTCC responder crash-loops: pymqi bindings (2058) fails; switch to client-mode localhost
- [logical-minds-foundry/mq-resiliency-lab-for-linux#182](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/182) Monitor QMSVC: 2nd mq_prometheus instance (mon-probe on net-ext, :9158)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#186](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/186) infra: lab time synchronization — chrony with hypervisor authority + drift monitoring
- [logical-minds-foundry/mq-resiliency-lab-for-linux#187](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/187) Pivot: promote RDQM/RHEL to priority arm at parity with Pacemaker/Ubuntu; open the arm abstraction to N arms
- [logical-minds-foundry/mq-resiliency-lab-for-linux#188](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/188) feat: P1 — parity harness run/report + capability matrix (vs Pacemaker)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#198](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/198) Design: IBM MQ Native HA on Kubernetes/OpenShift arm (nativeha-ocp)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#201](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/201) Design: lab PKI / TLS certificate provider (base-lab security foundation)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#202](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/202) Plan A: arm-backend seam + pcmk refactor (RDQM parity build)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#203](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/203) docs(rdqm): RDQM 3-node HA setup cheat sheet
- [logical-minds-foundry/mq-resiliency-lab-for-linux#206](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/206) Salt-ssh roster generator + mqlab/Salt integration design
- [logical-minds-foundry/mq-resiliency-lab-for-linux#208](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/208) RDQM-DR vs Native HA/CRR — network-requirements fact-check + reports
- [logical-minds-foundry/mq-resiliency-lab-for-linux#210](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/210) Build: lab PKI provider — Tasks 1-7 (per #201 plan)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#211](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/211) Parallelize lab bootstrap: bounded-concurrent VM creation + Ansible forks for safe provisioning
- [logical-minds-foundry/mq-resiliency-lab-for-linux#213](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/213) Investigate: must RDQM be configured with DR at setup — can DR not be added later?
- [logical-minds-foundry/mq-resiliency-lab-for-linux#216](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/216) Plan B: RDQM distributed-parity (arm registry verbs + distributed-rdqm-rhel)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#217](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/217) docs(nativeha): mark Native-HA-on-K8s design ON HOLD (firm chose DMZ/bare-metal)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#218](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/218) Lab snapshot/restore: get back to a provisioned state fast (clone + cheat-bootstrap)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#223](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/223) RDQM allows only ONE floating IP per QM — multi-VIP/multi-home assumption breaks (vs Pacemaker arm)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#224](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/224) Pin IBM doc links to 9.4 in shareable reports (HA/DR set + general practice)
- [logical-minds-foundry/mq-resiliency-lab-for-linux#235](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/235) Brainstorm: message-exit + distinct primary/secondary QM names for independent (uncoordinated) DR failover
- [logical-minds-foundry/mq-resiliency-lab-for-linux#239](https://github.com/logical-minds-foundry/mq-resiliency-lab-for-linux/issues/239) Investigate: is IBM MQ v10 LTS or CD, and did Native HA / CRR land in it?

