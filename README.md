# DashPro

> **Showcase page.** This repository is a public showcase of a **private repository**:
> it contains a description of the work only, with **no source code**.

A **MetaTrader 5 trading dashboard** written in MQL5: an in-terminal workspace that adds order tooling, chart theming, an economic calendar, trade replay and a social layer to the platform traders already use.

Developed across three generations, including a build tailored for a specific trading desk.

## What I built

**Trading tools**
- Order tool for placing and managing positions from the chart
- Ghost trade and replay engine for reviewing historical trades bar by bar
- Economic-calendar drawing directly on the chart
- Chart theming and a DPI-aware canvas so the interface stays sharp on any display

**Platform layer**
- Licensing and license-guard system with client-side crypto, plus a documented licence-server API specification
- Splash, logging and installer and patch tooling

**In-terminal chat**
- Authentication, friends, groups, messages, reactions, read receipts and typing indicators, all rendered inside MetaTrader
- A DLL bridge and REST API layer connecting the terminal to the chat backend

**Journal integration**
- A library connecting dashboard activity to a trading-journal product

## Stack

MQL5, MetaTrader 5, custom canvas UI rendering, Windows DLL bridge, REST API integration, PowerShell build tooling

---

*Source code is private. This page documents the work; code can be shared on request.*
