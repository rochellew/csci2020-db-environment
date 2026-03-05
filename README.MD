# CSCI 2020 – Database Environment Setup

This repository provides a pre-configured PostgreSQL database environment that runs entirely in your browser via GitHub Codespaces. **No software installation required.**

## Getting Started

### 1. Accept the GitHub Classroom Assignment

Click the assignment link provided by your instructor. GitHub will automatically create a personal copy of this repository under your account.

### 2. Launch Your Codespace

From your repository page:

1. Click the green **Code** button
2. Select the **Codespaces** tab
3. Click **Create codespace on main**

The environment will take about 60–90 seconds to build the first time. Subsequent launches are faster.

### 3. Connect to the Database

Once the Codespace has loaded:

1. Click the **SQLTools icon** in the left sidebar (looks like a database cylinder)
2. Under *Connections*, click **CSCI 2020 Local DB**
3. Click **Connect**

You're connected. The database has been pre-seeded and is ready to query.

### 4. Verify Your Setup

Open `testquery.sql` in the editor and run it to confirm the database is populated correctly. You can run a file in SQLTools by opening it and clicking the **Run on Active Connection** button (▶) at the top right of the editor.

---

## Connection Details

| Setting  | Value       |
|----------|-------------|
| Host     | `localhost` |
| Port     | `5432`      |
| Database | `csci2020`  |
| Username | `admin`     |
| Password | `admin`     |

---

## Troubleshooting

**Codespace loads but SQLTools can't connect**
The database container may still be initializing. Wait 20–30 seconds and try connecting again.

**"Extension not found" or SQLTools is missing**
Open the Extensions panel (`Ctrl+Shift+X` / `Cmd+Shift+X`) and search for `SQLTools`. Install both **SQLTools** and **SQLTools PostgreSQL/CockroachDB Driver** by Matheus Teixeira.

**I accidentally broke something**
Your Codespace is yours alone — it does not affect anyone else's. If something is seriously broken, delete the Codespace and create a new one from the same repo. Your database will reset to the original seed data.

---

## Notes

- Each student has their own isolated Codespace and database instance. Changes you make do not affect classmates.
- Your Codespace will automatically stop after a period of inactivity. Resume it anytime from [github.com/codespaces](https://github.com/codespaces).
- Free GitHub accounts include 120 core-hours of Codespaces per month, which is well in excess of what this course requires.