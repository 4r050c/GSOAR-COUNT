# GSOAR-COUNT – SOC Shift Case Counter

A lightweight JavaScript bookmarklet designed for SOC analysts to quickly calculate the number of cases/tickets created during each shift while automatically excluding automation-generated cases from the final count.

## Overview

COUNT helps SOC teams generate accurate shift metrics without manually filtering cases. The bookmarklet retrieves case information directly from the SOAR platform, categorizes tickets by shift, removes automation-generated entries, and provides a cleaner representation of analyst workload.

## Features

- 📊 Counts cases created during SOC shifts
- 🚫 Excludes automation-generated cases from totals
- ⏱ Supports shift-wise analysis
- ⚡ Runs directly from a browser bookmark
- 🔐 Uses the active authenticated session
- 📋 Quick copy/export of results
- 🎯 Useful for shift handovers and reporting

## Use Cases

- Daily SOC reporting
- Shift productivity tracking
- Analyst workload measurement
- Management reporting
- Incident volume trending
- Shift handover statistics

## How It Works

1. Open the SOAR platform in your browser.
2. Click the **COUNT** bookmarklet.
3. Enter the required parameters (if prompted).
4. The bookmarklet retrieves relevant case data.
5. Automation-generated cases are filtered out.
6. Results are displayed with adjusted shift counts.

<img width="754" height="504" alt="image" src="https://github.com/user-attachments/assets/f48ecbb6-8e06-4834-94e7-faf01786cbcd" />
<img width="769" height="448" alt="image" src="https://github.com/user-attachments/assets/449a41e9-ca89-4ce0-b89c-7fe832944769" />




## Example Output

<img width="1338" height="625" alt="image" src="https://github.com/user-attachments/assets/20f0be1e-55f4-42be-b3e0-d34bfa91ba80" />

