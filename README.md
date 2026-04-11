# DecodingPro – Free Enterprise‑Grade Python Samples

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Security: Contact](https://img.shields.io/badge/Security-contact%20us-blue)](SECURITY.md)

## Who We Are
**DecodingPro** provides production‑ready Python scripts and `.jsonl` datasets for fine‑tuning local LLMs.  
We serve developers, data engineers, and AI teams who need high‑quality code to train models for finance, DevOps, security, and cloud automation.

## What We Offer

| Tier | Price | What You Get | Where to Find |
|------|-------|--------------|----------------|
| **Free** | $0 | Sample Python scripts (this repo) – learn core patterns | GitHub (you are here) |
| **Core** | $49 | 15 OOP scripts + `.jsonl` datasets for fine‑tuning | [decodingpro.com/core](https://decodingpro.com/core) |
| **Premium** | $99 each | Enterprise vaults (HFT, stealth scraping, PySpark, DGA detection, K8s autoscaling) | [decodingpro.com/premium](https://decodingpro.com/premium) |

## Free Tier – What’s Inside

| Category | Description | Status |
|----------|-------------|--------|
| [Cloud Automation](Free_Tier/Cloud_Automation) | AWS S3 upload, server health monitor, backup archiver | ✅ Ready |
| Data Engineering | PySpark basics, Kafka producer/consumer | 🚧 Coming soon |
| Cybersecurity | Threat intel, DGA detection basics | 🚧 Coming soon |
| Finance | Basic indicators, order book snapshots | 🚧 Coming soon |

## Quick Start (Cloud Automation)

```bash
git clone https://github.com/DecodingPro/DecodingPro.git
cd DecodingPro/Free_Tier/Cloud_Automation
pip install -r requirements.txt
cp .env.example .env   # edit with your AWS keys (if needed)
python scripts/01_s3_file_uploader.py --help
