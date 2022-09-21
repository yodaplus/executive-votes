---
title: Template - [Executive Vote] Initial USXD test executive - Sep 14, 2022
summary: An experimental executive on Apothem, to test the governance module
date: 2022-09-14T00:00:00.000Z
address: "0xfBeeF65F14b89a66ba38cF2818D255a2E19Af951"
---

# [Executive Proposal] Initial USXD test executive - Sep 14, 2022

This executive spell updates Debt Auction Amounts on Apothem. Deployed primarily for dev testing purposes.

---

## Executive Summary

This test executive spell updates Debt Auction Amounts on Apothem.

## Proposal Details

Deployed primarily for dev testing purposes.

- USXD amount for system debt to be covered by each debt auction set to 2 .
- Starting Gov Token amount to be auctioned off to cover system debt (in debt auctions) also set to 2.

## Review

Internally, the `sump` & `dump` values of [VOW contract](https://apothem.blocksscan.io/address/xdc7687Ec6e0000423E8a569e4cE6895F67f8235965) should be updated to the new values (accounting for precission multiplier)

So,
- `sump` should be 2 * 10 ** 45
- `dump` should be 2 * 10 ** 18

## Resources

empty
