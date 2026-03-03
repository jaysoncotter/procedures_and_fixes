# Procedures and Fixes

A comprehensive database of Standard Arrival and Departure (STAR/DP) procedures with cross-referenced waypoints and fixes used across multiple airports.

## What's Inside

- **7,576 unique waypoints** organized by aviation procedure
- **2,645 unique fixes/navaids** across the national airspace
- **2,132 waypoints** appearing in multiple airports
- **985 fixes** shared across different airport procedures
- **1,887 total airports** in the dataset

## Quick Facts

- MISEN fix appears in **15 airports** (most shared)
- COREZ fix appears in **13 airports**
- Many procedures reuse the same navigation points for consistency across regions
- Waypoints range from 2-12 airport appearances, fixes up to 15

## File Format

`STARDP_procedures.json` contains:
- `shared_waypoints_list` - All waypoints used by multiple airports
- `detailed_shared_waypoints` - Quick lookup by waypoint identifier
- `shared_fixes_list` - All fixes used by multiple airports
- `detailed_shared_fixes` - Quick lookup by fix identifier
- `summary` - Statistical breakdown by airport count
- `airports` - Complete list of all airport codes

## How to Use

Search the JSON for any waypoint or fix to see which airports use it. Perfect for:
- Flight planning across multiple airports
- Procedure analysis and comparison
- Understanding airspace structure
- Aviation research and education

## Data Source

Compiled from FAA STAR/DP procedure data (STARDP.txt format)

## Live Demo

https://jaysoncotter.github.io/procedures_and_fixes/
