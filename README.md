# Thistlewick Vendor Registry

Internal record of approved suppliers and the public artifacts we reference
for each of them.

Each supplier has a profile under `vendors/`. Profiles use a small YAML
front-matter block followed by review notes.

Fields:

- `vendor_id` - internal accounting identifier
- `vendor_name` - registered supplier name
- `onboarding_status` - current procurement state
- `github_repository` - location of the supplier's connector repository
- `docs_repo` - public connector link, populated only when the repository is
  released and available to us
