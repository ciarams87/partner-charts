### Run-Time Protection Without Compromise

NeuVector delivers a complete run-time security solution with container process/file system protection and vulnerability scanning combined with the only true Layer 7 container firewall. Protect sensitive data with a complete container security platform.

NeuVector integrates tightly with Rancher and Kubernetes to extend the built-in security features for applications that require defense in depth. Security features include:

+ Build phase vulnerability scanning with Jenkins plug-in and registry scanning
+ Admission control to prevent vulnerable or unauthorized image deployments using Kubernetes admission control webhooks
+ Complete run-time scanning with network, process, and file system monitoring and protection
+ The industry's only layer 7 container firewall for multi-protocol threat detection and automated segmentation
+ Advanced network controls including DLP detection, service mesh integration, connection blocking and packet captures
+ Run-time vulnerability scanning and CIS benchmarks

Additional Notes:
+ Configure correct container runtime and runtime path under container runtime. Enable only one runtime.
+ Neuvector deployed from Partners chart repository do not support Single Sign On from Rancher Manager. Please deploy Neuvector from Rancher charts for Single Sign On to work.
+ For deploying on hardened RKE2 and K3s clusters, enable PSP and set user id from other configuration for Manager, Scanner and Updater deployments. User id can be any number other than 0.
+ For deploying on hardened RKE cluster, enable PSP from other configuration.
