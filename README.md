![CI](https://github.com/mg0x7BE/REPO_NAME/actions/workflows/ci.yml/badge.svg)
![GitHub repo size](https://img.shields.io/github/repo-size/mg0x7BE/REPO_NAME)
![GitHub License](https://img.shields.io/github/license/mg0x7BE/REPO_NAME)
![GitHub Created At](https://img.shields.io/github/created-at/mg0x7BE/REPO_NAME)
![GitHub forks](https://img.shields.io/github/forks/mg0x7BE/REPO_NAME)
![GitHub Repo stars](https://img.shields.io/github/stars/mg0x7BE/REPO_NAME)\
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Native AOT](https://img.shields.io/badge/.NET-Native_AOT-1F0A32?style=flat&labelColor=8A2BE2)
![Self-contained](https://img.shields.io/badge/.NET-Self--contained-1F0A32?style=flat&labelColor=8A2BE2)

# Project Name

Description.

## Setup Checklist

### README
- [ ] Replace `REPO_NAME` with actual repo name in all badge URLs
- [ ] Replace `# Project Name` with actual name
- [ ] Remove unused OS badges (Windows / macOS / Linux)
- [ ] Remove unused .NET badge (Native AOT / Self-contained)
- [ ] Write description and usage

### Workflows

| Variant | CI | Release |
|---|---|---|
| Windows only | `ci-windows.yml.template` | `release-windows.yml.template` |
| Windows + macOS | `ci-multi.yml.template` | `release-multi.yml.template` |

- [ ] Rename chosen variant to `ci.yml` / `release.yml`
- [ ] Delete unused `.yml.template` files
- [ ] Replace `PROJECT_NAME` with actual executable name in `release.yml`

### Dependabot
- [ ] Remove `nuget` ecosystem if project has no NuGet packages

### Repository Settings
- [ ] Enable release immutability: Settings > General > Releases
- [ ] Import `protect-the-master.json` via Settings > Rules > Rulesets > Import a ruleset
- [ ] Delete `protect-the-master.json` from repo
- [ ] Set repo description and topics on GitHub
- 
## License

[Unlicense](LICENSE)
