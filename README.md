# Finextract

A packaged desktop delivery repo for FinExtract Pro, aimed at people who want the installer fast without wading through a source tree.

## What This Repo Contains

This repository currently distributes the Windows installer build of the application rather than the raw implementation source.

## Project Structure

```text
Finextract/
|-- FinExtract Pro Setup 1.0.0.exe
|-- .gitattributes
|-- .gitignore
`-- README.md
```

## Installation

1. Download or clone this repository.
2. Run `FinExtract Pro Setup 1.0.0.exe`.
3. Follow the installer steps.

## How It Works

The repository is intentionally simple: it serves as a delivery point for the packaged installer. The application logic lives inside the installed desktop app, not as source files in this repo.

## When This Repo Is Useful

This is the right format when you want to hand off an installable product quickly to users, testers, or stakeholders without asking them to build anything locally.
