# Intelligent Drone Flight-Path Planning for 3D Reconstruction

## 1. Project context

This project is an **intelligent drone flight-path planning system for 3D reconstruction**. The intended workflow includes selecting a target region, viewing its terrain/buildings in a 3D workspace, visualizing cameras or planned flight paths, and developing flight path planning and mission export capabilities.

Known requirements and considerations:

- The front end 3D workspace must load terrain/building tiles for user selected regions and display camera information smoothly and reliably
- Flight path planning decisions must account for the constraints and requirements of drone based 3D data acquisition

## 2. Security and privacy

1. **Never open, read, print, summarize, process, or paste secrets** such as `.env` files, API keys, passwords, tokens, private keys, or credentials. Do not run commands that expose them
2. Access and process **only the repository files needed** for the current task. Do not inspect unrelated files

## 3. Architecture Decision Records (ADRs)

Create a **Proposed** ADR for consequential, important choices

Before an ADR becomes **Accepted**:

1. Define the drone planning problem and its constraints **without assuming the solution**
2. Evaluate **at least two viable alternatives** and give concrete reasons for rejecting options
3. Document trade-offs, costs, and negative consequences
