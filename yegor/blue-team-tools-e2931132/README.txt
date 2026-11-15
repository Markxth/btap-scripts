Unchanged Blue-Team-Tools shortlist

These three selected reference files were copied byte-for-byte from the pinned
GitHub commit. They have not been executed, tested on a target machine, modified,
or uploaded. All files are non-executable copies. This is a reference collection,
not a safety certification or an automated deployment package.

Selected files:
- Linux/Harden-Apache/flawless-hedgehog.sh
- Linux/Harden-SSH/ssh_harden.sh
- Windows/CCDCprep/checklist/DiscoverySteps.md

Review before any use:
- Apache: uses older Debian-style configuration paths, edits configuration and
  can restart Apache. Settings may break applications or service availability.
- SSH: changes authentication, ports, SELinux and firewall rules. Disabling
  password or root login without verified alternative access can lock you out.
- Windows checklist: contains older commands/tools and some unrelated entries.
  Treat it as reference material and verify each step against your Windows
  version and the authorized scenario rather than following it wholesale.

No commands inside these files were run. If you later choose to use them,
review every action first and test in an isolated environment with backups
and a working recovery/console path.

SOURCE-ATTRIBUTION.txt records origin and license context.
SOURCE-MANIFEST.json records the pinned commit, Git blob IDs and SHA-256 hashes.
SHA256SUMS.txt covers every other file in this subfolder.
The pre-existing contents of the parent Downloads folder were left unchanged.
