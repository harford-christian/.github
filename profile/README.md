# Harford Christian School — IT

Internal tooling for Harford Christian School: Google Apps Script web apps, FACTS SIS
integrations, campus signage and kiosks, and network automation.

Most repositories here are private. The handful that are public exist to serve a
GitHub Pages site.

## Finding your way around

Repositories are tagged by topic rather than grouped into folders — GitHub has no
folders. Filter the [repository list](https://github.com/orgs/harford-christian/repositories)
by any of these:

| topic | what it covers |
| --- | --- |
| `facts` | FACTS SIS integrations — provisioning, rostering, dismissal, directory |
| `apps-script` | Google Apps Script projects, managed with clasp |
| `google-workspace` | Workspace provisioning, groups, distribution lists |
| `unifi` | Ubiquiti network and door automation |
| `paging` | Yeastar / CyberData paging system |
| `signage` | Lobby, gym and classroom displays |
| `kiosk` | iPad and Chromebook kiosk apps |
| `forms` | The in-house form builder and runner |
| `athletics` | Team logistics and communication |
| `documentation` | SOPs, guides, reference material |

Archived repositories are superseded or no longer maintained. They stay readable
for reference.

## Conventions

- Repository names are lower-case kebab-case.
- `main` is the default branch.
- Secrets live in Script Properties or a git-ignored `.env` — never in a committed
  file, and never written into documentation.
- Each project carries a `README.md` describing what it does.

## Access

| team | access |
| --- | --- |
| `admins` | Admin on all repositories |
| `developers` | Write on all repositories |

Everyone else in the organization has Read by default, plus Write on the specific
repositories they maintain. If you need access to something, ask an organization owner.
