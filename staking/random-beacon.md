---
description: >-
  Random Beacons are at the heart of the network. They are needed to randomly
  select providers to create a new keep. Providers need to stake KEEP tokens,
  create a node and maintain it to be part of the
---

# Random Beacon



{% hint style="info" %}
Random Beacons are at the heart of the network. They are needed to randomly select providers to create a new keep. Providers need to stake KEEP tokens, create a node and maintain it to be part of the network and earn fees.
{% endhint %}

## Run a Random Beacon

The original article from Keep to run this node.

{% embed url="https://docs.keep.network/run-random-beacon.html" %}

## Deployment

### Cloud deployment - Vultr

This article is a step-by-step tutorial to set-up a random beacon node in TestNet \(Ropsten\) with a deployment in the cloud with Vultr. This is the tutorial we used to set-up our own testnet node! No previous knowledge needed, give it a go ;\) What you will need \(explained in the article\):

* ETH and KEEP faucet tokens
* an Infura account
* an SSH client
* a wallet \(MetaMask\)

{% embed url="https://medium.com/@hardcorecoin/how-to-set-up-and-run-random-beacon-node-step-by-step-guide-for-beginners-c593ebc768cd" %}

### Cloud deployment - Google

Video to learn how to run the Random Beacon node:

{% embed url="https://www.youtube.com/watch?v=7zgXxqnYF\_0" %}

In this step-by-step tutorial you can learn how to launch both nodes \(BEACON and ECSDA\) at once on one vps. 

{% embed url="https://youtu.be/WhqkOwmQIoo" %}

### Cloud deployment - Hetzner

Installation guide with translations in Indonesian and Russian!

{% embed url="https://icohigh.gitbook.io/keep-nodes/english/installation-guide" %}

### Cloud deployment - DigitalOcean

{% embed url="https://medium.com/@ben\_longstaff/a-beginners-quick-start-guide-to-staking-on-the-keep-network-testnet-using-digitalocean-5a74ca60adc3" %}



### Rasberry Pi cluster

{% hint style="success" %}
🏆 This project won the play for keep award!
{% endhint %}

Wondering how you can run a bare metal Raspbery Pi cluster? Yes, find below a step-by-step tutorial.

{% embed url="https://medium.com/@stevenyuan/staking-keep-on-a-raspberry-pi-cluster-with-ansible-kubernetes-k3s-glusterfs-and-more-10efe30539d4" %}

{% embed url="https://github.com/syuan100/keep-pi-cluster" %}

### Local deployment

This article is a step-by-step tutorial to set-up a random beacon node in TestNet \(Ropsten\) with a local deployment. What you will need \(explained in the article\):

* ETH and KEEP faucet tokens
* an Infura account
* an SSH client
* a wallet \(MetaMask\)

{% embed url="https://medium.com/@novysf/run-a-keep-network-testnet-node-37096946af35" %}

This nice article is also well detailed for absolute beginners:

{% embed url="https://medium.com/@jack.baldwin/the-absolute-beginners-guide-to-playing-for-keeps-aea9ab32f6e8" %}

### Helm Charts

"These charts provide a simple way to deploy KEEP Network clients into Kubernetes and make for easier and simplier upgrade processes". Look at the keep-client for the Beacon chain client.

{% embed url="https://github.com/ajcrowe/keep-helm-chart" %}

### Monitoring using Grafana, Prometheus and Loki

Below you will find a step-by-step guide, and its corresponding code in git, to set up the monitoring on a Keep Random Beacon node using Grafana, Prometheus and Loki.

{% embed url="https://medium.com/@hr12rtk/keep-random-beacon-node-monitoring-grafana-prometheus-and-loki-4a4b669b31ea" %}

{% embed url="https://github.com/mutedtommy/monitoring-setup-script" %}

