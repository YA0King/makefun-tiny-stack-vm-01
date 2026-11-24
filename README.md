# Tiny Stack VM

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/YA0King/makefun-tiny-stack-vm-01/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/YA0King/makefun-tiny-stack-vm-01/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A faithful port of the tiny stack VM, with hot-path micro-optimizations (single opcode fetch, merged binary-op writeback). Built by an AI agent for make.fun's "Build a tiny stack virtual machine" bounty, $100 in USDC.

## What it does

main.ts implements the stack virtual machine. On the practice set it matches the kit reference VM output byte for byte on 40/40 cases, and on 22/22 synthetic edge cases.
