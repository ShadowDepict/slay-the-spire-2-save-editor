# Security Policy

## Supported versions

| Version | Supported |
|---|---|
| 1.0.x | Yes |
| Older builds | No, download the current one from the landing page |

## What this tool does and does not do

Slay the Spire 2 Save Editor is an offline desktop utility. It opens a local save document that you select, shows the values it parsed, and writes the fields you changed back to that file. Before the first write it copies the original next to it with a timestamp.

It does not:

- attach to, open or inject into the running game process;
- read or write process memory;
- install a driver, a kernel component or a Windows service;
- request administrator rights;
- open a network connection, check for updates or send telemetry;
- require an account, a licence key or a login.

Uninstalling means deleting the folder. The only files it leaves behind are the save backups it created and its own plain-text settings file.

## Data handling

Everything stays on your disk. The editor reads the save path you point it at, writes the same file, and stores its own settings beside the application. No file contents are transmitted anywhere, because there is no network code in the build.

## Reporting a vulnerability

If you believe you have found a security issue, open a private report through GitHub's **Security → Report a vulnerability** flow on this repository rather than a public issue.

Please include:

- the version shown in the app and on the landing page;
- your Windows build;
- the exact steps that reproduce the problem;
- the save format or game build you were editing;
- what you expected to happen and what happened instead.

You can expect an acknowledgement within a few days. Please give a reasonable window for a fix before publishing details.

## Scope

Reports about the game itself, its publisher, store listings, leaked material or save-format changes are out of scope for this repository. This policy covers the editor application and this project page only.

## Distribution

Builds are distributed through the project landing page only. If you obtained this tool from anywhere else, treat that copy as untrusted.
