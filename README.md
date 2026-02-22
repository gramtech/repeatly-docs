# Repeatly — Docs & Legal Site

Public-facing website for [Repeatly](https://apps.apple.com/app/repeatly), a recurring task manager for iOS.

## About Repeatly

Repeatly sits between a calendar and a to-do list. It's built for obligations that repeat on a regular cadence — things too important to forget but that don't belong in a full calendar app.

**Examples:**
- Annual: car MOT, insurance renewals, passport expiry, medical check-ups
- Monthly: subscription reviews, bill payments, financial check-ins
- Daily: medication reminders, supplements, habit tracking

When you complete a task, Repeatly automatically schedules its next occurrence. You never have to re-enter a recurring obligation.

## Features

- **Flexible recurrence** — daily, weekly, monthly, yearly, or custom intervals
- **Calendar view** — month-grid overview of all upcoming tasks
- **Smart notifications** — reminders days or weeks before something is due
- **Auto-complete** — tasks can auto-complete after their grace period
- **Categories** — colour-coded groups (Health, Finance, Vehicle, Home, and more)
- **Repeatly Pro** — multiple reminders per task, custom detail fields, and more

## Tech Stack

Built with React Native (Expo managed workflow) and TypeScript, targeting iOS.

| Layer | Technology |
|---|---|
| Framework | React Native + Expo |
| Language | TypeScript |
| Database | SQLite (expo-sqlite) |
| State | Zustand |
| Styling | NativeWind (Tailwind CSS) |
| Navigation | React Navigation |
| Subscriptions | RevenueCat |
| Notifications | Expo Notifications (on-device) |

## This Repository

This repo contains the static marketing and legal pages hosted via GitHub Pages:

| File | Description |
|---|---|
| `index.html` | Landing page |
| `privacy/index.html` | Privacy Policy |
| `terms/index.html` | Terms of Service |

## Contact

repeatly@gramtech.co.uk
