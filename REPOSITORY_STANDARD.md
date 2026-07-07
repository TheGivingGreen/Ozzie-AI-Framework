# Repository Standard

This framework repository must remain lightweight, portable, and implementation-free.

These rules apply to this framework repository itself. Target projects that adopt the framework may contain their own code, assets, dependencies, and deliverables.

## Allowed

- Canonical operating instructions
- Vendor-neutral agent protocols
- Governance rules
- Documentation standards
- Playbooks and checklists
- Copyable templates
- Thin tool-specific adapters

## Not Allowed

- Implementation source code
- Product-specific website pages
- Package manager manifests or lockfiles
- Dependency folders
- Generated output such as `dist/`, `build/`, `out/`, `.next/`, or coverage reports
- Product images, videos, fonts, or brand assets
- Client deliverables
- Deployment workflows for a specific product
- Secrets, credentials, or local environment files

## Adapter Rule

Tool-specific folders may exist only to help tools locate the canonical instructions.

Adapters should contain pointers and tool-loading notes. They should not restate durable framework rules.

## Cleanup Rule

If copied project material lands in this repository, remove it before adding framework changes.

Ignore rules help prevent residue, but reviewing the tree is still required.
