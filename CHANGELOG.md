# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Recent Changes (2020-04-23)

#### Added
- **LABL Table Proposal**: Added comprehensive proposal for a new `LABL` (Glyph labels) table by Adam Twardoch
  - Provides human-readable labels for glyphs in fonts
  - Supports multiple vocabularies and languages
  - Offers two implementation variants (A and B)
  - Includes examples for ligatures, symbols, and logotypes
  - References existing work (Zapf table) and provides rationale for the new approach

#### Changed
- Multiple refinements to the LABL table proposal documentation
- Minor formatting improvements (heading levels)

### Previous Changes (2019-10-11)

#### Added
- **New Proposals**:
  - Capability Conditions proposal for handling different shaping engine capabilities
  - Polygon Kerning proposal for advanced spacing between clusters
  - Extended spacing marks proposal

### Earlier Notable Changes

#### Added
- **Documentation**:
  - Script segmentation documentation discussing text run segmentation algorithms
  - Ligature formation documentation explaining OpenType ligature handling
  - Documentation needs file outlining areas requiring clarification

- **Proposals**:
  - Move Lookup proposal for GSUB glyph movement
  - Complex Contextual Chaining proposal for advanced GSUB operations
  - Glyph Filtering proposal extending mark filtering to non-marks
  - Lookup Flags Extensions proposal
  - Spacing Attachment proposal for handling spacing marks
  - Topographical Features proposal (PDF)

#### Fixed
- Typo corrections in ligature examples
- DirectWrite compatibility issues documentation for ligatures

#### Changed
- Clarifications to complex contextual proposal implementation details
- Added information about higher-level segmentation (bidi and word caching)
- Code formatting improvements in documentation examples