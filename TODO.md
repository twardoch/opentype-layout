# OpenType Layout Repository - TODO List

This is a simplified task list based on the comprehensive improvement plan in PLAN.md. Tasks are organized by priority and phase.

## Phase 1: Foundation and Organization (Immediate - Month 1)

### Legal and Governance
- [ ] Add LICENSE file (recommend Apache 2.0 or MIT)
- [ ] Create CONTRIBUTING.md with contribution guidelines
- [ ] Add CODE_OF_CONDUCT.md (use Contributor Covenant)
- [ ] Create .github/ISSUE_TEMPLATE/ for bug reports and feature requests
- [ ] Create .github/PULL_REQUEST_TEMPLATE.md

### Repository Structure
- [ ] Create new directory structure:
  - [ ] Create `docs/overview/` directory
  - [ ] Create `docs/guides/` directory
  - [ ] Create `proposals/gsub/` directory
  - [ ] Create `proposals/gpos/` directory
  - [ ] Create `proposals/lookup-flags/` directory
  - [ ] Create `proposals/tables/` directory
  - [ ] Create `proposals/features/` directory
  - [ ] Create `resources/images/` directory
  - [ ] Create `resources/examples/` directory
  - [ ] Create `resources/archive/` directory

### File Organization
- [ ] Rename files to follow YYYY-MM-DD-name.md convention:
  - [ ] Rename `20151104-movelookup.md` to `2015-11-04-move-lookup.md`
  - [ ] Rename `20151104-spacemark.md` to `2015-11-04-spacing-attachment.md`
  - [ ] Rename `20200423-AdamTwardoch-LABL-table.md` to `2020-04-23-labl-table.md`
  - [ ] Rename other proposal files similarly
- [ ] Move files to appropriate subdirectories
- [ ] Move `spacing_mark.png` to `resources/images/`
- [ ] Fix broken link in README.md (capability.md reference)

### Content Migration
- [ ] Convert `20160203-Joining_Feature_Proposal_1.2.pdf` to Markdown
- [ ] Convert `20160523-KamalMansour-SpacingMarksAddendum.pdf` to Markdown
- [ ] Archive original PDFs in `resources/archive/`
- [ ] Remove or document purpose of `llms.txt`

## Phase 2: Documentation Enhancement (Month 2)

### Core Documentation
- [ ] Create `docs/overview/introduction.md`
- [ ] Create `docs/overview/how-to-contribute.md`
- [ ] Create `docs/overview/proposal-process.md`
- [ ] Create `docs/glossary.md` with OpenType terms
- [ ] Create `proposals/README.md` with proposal index table

### Proposal Metadata
- [ ] Add YAML frontmatter to all proposals with:
  - [ ] Title, authors, status, dates
  - [ ] Category and implementation status
- [ ] Create proposal numbering system (e.g., OTL-YYYY-NNN)

### Technical Documentation
- [ ] Document proposal states (Draft, Under Review, Accepted, etc.)
- [ ] Create proposal template in `docs/guides/proposal-template.md`
- [ ] Write technical writing style guide
- [ ] Create implementation tracking guide

## Phase 3: Web Deployment (Month 3)

### Static Site Setup
- [ ] Install and configure MkDocs with Material theme
- [ ] Create `mkdocs.yml` configuration
- [ ] Set up navigation structure
- [ ] Configure search functionality
- [ ] Enable syntax highlighting

### GitHub Integration
- [ ] Configure GitHub Pages deployment
- [ ] Set up GitHub Actions workflow for automatic building
- [ ] Configure custom domain (if available)
- [ ] Enable HTTPS

### Content Preparation
- [ ] Create landing page (`index.md`)
- [ ] Create FAQ page
- [ ] Add implementation compatibility matrix
- [ ] Create examples index page

## Phase 4: Community Building (Months 4-6)

### Automation and Quality
- [ ] Add markdown linting GitHub Action
- [ ] Add link checking GitHub Action
- [ ] Add spell checking GitHub Action
- [ ] Create proposal validation script

### Community Resources
- [ ] Create newsletter signup or mailing list
- [ ] Set up discussion forum or use GitHub Discussions
- [ ] Create contributor recognition system
- [ ] Document meeting schedule and process

### Outreach
- [ ] Create project announcement for typography communities
- [ ] Prepare presentation materials
- [ ] Reach out to OpenType implementers
- [ ] Create social media presence (Twitter/Mastodon)

## Phase 5: Advanced Features (Future)

### Testing and Validation
- [ ] Create test suite structure
- [ ] Develop reference tests for proposals
- [ ] Set up automated testing infrastructure
- [ ] Create result reporting dashboard

### Internationalization
- [ ] Identify key proposals for translation
- [ ] Set up translation infrastructure
- [ ] Recruit translation volunteers
- [ ] Create localized documentation

### Advanced Documentation
- [ ] Create video tutorials
- [ ] Write implementation case studies
- [ ] Develop interactive examples
- [ ] Create API documentation

## Quick Wins (Can be done immediately)

- [ ] Add LICENSE file
- [ ] Fix broken link in README.md
- [ ] Create basic CONTRIBUTING.md
- [ ] Start using consistent file naming
- [ ] Update README.md with better organization

## Notes

- Each checked item should be turned into a PR when possible
- Coordinate with repository maintainers before major changes
- Consider creating a project board to track progress
- Regular progress reviews recommended (monthly)
- Community feedback should guide prioritization