# GitHub Command Line Interfaces for OriginAgents

## 1. Prerequisite

> Installation of GitHub CLI: 
>> brew install gh (macOS)<br>
>> sudo apt update && sudo apt install gh (Ubuntu)<br>
>> choco install gh (Windows)<br>

## 2. Custom Scripts

### (1) sync-forks

> Goal: Sync all forked repositories automatically with given owner(user or organization).
> 
> Run: sh ./scripts/sync-forks.sh

### (2) pull-updates

> Goal: Pull updates for all existing repositories automatically with given local owner path and owner(user or organization).
> 
> Run: sh ./scripts/pull-updates.sh

### (3) gen-forks-list

> Goal: Generation for GitHub Repository Forks List with given owner(user or organization).
>
> Run: sh ./scripts/gen-forks-list.sh

## 3. Custom Actions

### (1) sync-forks-originagents

> Goal: Synchronization of GitHub Repository Forks for OriginAgents.
>
> Result: All GitHub Repository Forks sync with the upstreams for OriginAgents(https://github.com/OriginAgents).

### (2) gen-forks-list-originagents

> Goal: Generation of GitHub Repository Forks List for OriginAgents.
> 
> Result: assets/docs/Forks-List-OriginAgents.md

---

## References

> (1) https://docs.github.com/zh<br>
> (2) https://docs.github.com/zh/github-cli<br>
> (3) https://github.com/cli/cli<br>
> (4) https://cli.github.com/<br>
> (5) https://cli.github.com/manual/<br>
