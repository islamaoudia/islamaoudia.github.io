---
title: Pwning "Under The Web" (HTB)
date: 2026-11-19 20:00:00 +0100
categories: [Writeups, HTB]
tags: [pwn, heap, php, lfi]
---

My first CTF writeup! Going from a PHP LFI (`/proc/self/maps` leak) to an unbounded `strcpy()` heap overflow in a custom C extension (`metadata_reader.so`), poisoning the Zend Memory Manager freelist, and hijacking `_efree@GOT` for RCE.

**[Read the full writeup on Medium](https://medium.com/@isl.aoudia/pwning-under-the-web-f1131eac17f9)**
