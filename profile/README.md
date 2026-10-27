<div align="center">

# Abrams Research Systems LLC

Independent research · deterministic state records for constrained embedded systems

<p>
  <a href="https://abramsresearch.net"><img alt="Website" src="https://img.shields.io/badge/Website-abramsresearch.net-0284C7?style=for-the-badge&labelColor=080c16" /></a>
  <a href="https://github.com/Abrams-Research-Systems-LLC/Abrams-Event-Address-AEA"><img alt="AEA-STATE/1" src="https://img.shields.io/badge/AEA--STATE%2F1-reference-0284C7?style=for-the-badge&labelColor=080c16" /></a>
  <a href="https://abramsresearch.net/government/"><img alt="Government" src="https://img.shields.io/badge/Government-federal-0284C7?style=for-the-badge&labelColor=080c16" /></a>
  <a href="https://abramsresearch.net/assurance/"><img alt="Evidence" src="https://img.shields.io/badge/Evidence-checks-0284C7?style=for-the-badge&labelColor=080c16" /></a>
  <a href="https://abramsresearch.net/contact/"><img alt="Contact" src="https://img.shields.io/badge/Contact-email-0284C7?style=for-the-badge&labelColor=080c16" /></a>
</p>

</div>

## 🔬 About

Abrams Research Systems LLC is a U.S. small business formed in 2026 and based in Loveland, Colorado. It develops and evaluates deterministic state-record software for constrained embedded systems. Joshua M. Abrams is Founder and Principal Investigator.

## 📂 What this GitHub is for

This organization hosts our public code. It starts with the [AEA-STATE/1](https://github.com/Abrams-Research-Systems-LLC/Abrams-Event-Address-AEA) open reference implementation, which can be inspected and tested on a host.

## 📐 AEA-STATE/1 at a glance

| Item | Detail |
| --- | --- |
| Record | Fixed 136-byte state record |
| Context | Reference frame and time scale tagged on each record |
| Integrity | Unkeyed SHA-256 digest for accidental corruption |
| Implementation | `#![no_std]` Rust reference library with a C ABI |
| Footprint | About 2.3 KB on Cortex-M (cross-compiled size) |
| License | MIT / Apache-2.0 |
| Readiness | TRL 3 — host-verified proof of concept; no hardware or flight demonstration yet |

## 🛠️ What we do

**AEA-STATE/1.** A published specification and reference library for a host-supplied state record.

**Engineering.** Target-platform, research-question, and hardware-evaluation discussions around that format.

**Materials R&D (RawCarbon).** Graphene research through flash Joule heating. Stated goals include stronger composites, improved coatings and components, and custom synthesis equipment. Batch-specific material properties and component improvements have not been established by public measurements.

## 🏛️ Federal registration

CAGE `25CH7` · UEI `J3B7R2FBHMA3` · active SAM.gov registration. U.S. small business, Loveland, Colorado. Company identifiers: [government information](https://abramsresearch.net/government/).

## ✉️ Contact

[Contact page](https://abramsresearch.net/contact/) · [contact@abramsresearch.net](mailto:contact@abramsresearch.net)

<details>
<summary>Verify it yourself</summary>

<br>

In the [AEA-STATE/1](https://github.com/Abrams-Research-Systems-LLC/Abrams-Event-Address-AEA) repository:

```
python verify.py
bash verify.sh
cargo test
```

These are host checks. Hardware timing and flight results are not claimed.

</details>
