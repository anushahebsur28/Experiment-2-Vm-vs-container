# Experiment 2  Memory Performance: Virtual Machine vs Docker Container

[![Course](https://img.shields.io/badge/Course-Cloud%20Computing-blue.svg)](#)
[![Environments](https://img.shields.io/badge/Environments-VMware%20VM%20%7C%20Docker%20Container-orange.svg)](#)
[![Benchmark](https://img.shields.io/badge/Benchmark-Sysbench%20Memory%2010G-green.svg)](#)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)](#)

---

## Executive Summary

This experiment compares memory-operation performance of an **Ubuntu Virtual Machine (VMware Workstation)** and a **Docker container** (`vm-container-benchmark`, based on `ubuntu:24.04`) using the identical Sysbench memory workload (1 MiB blocks, 10 GiB total, 4 threads, write).

### Key Finding

> **The Docker container reached 123,725.89 MiB/sec versus 108,900.87 MiB/sec for the VM â€“ a +13.61% throughput advantage â€“ and a maximum latency of 1.13 ms versus 3.04 ms (-62.8%).**

---
