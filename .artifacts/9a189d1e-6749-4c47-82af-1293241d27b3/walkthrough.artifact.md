# Walkthrough: Increasing SVG file limit

I have increased the SVG file size limitation from 700 KB (approximately 0.7 MB) to 10 MB in the `IconPack` repository.

## Changes Made
- Modified `E:/SnapTune-V3.0.0/IconPack/.github/scripts/process_icon_submission.py` to change `MAX_SVG_BYTES` from `700_000` to `10_000_000`.

This will allow users to submit SVG files up to 10 MB in size via the automated submission process.
