# LAB-001 — Excel slowdown investigation

This guided case study is part of **System Information & Hardware Diagnostics**. I practiced monitoring resource usage in a Windows 11 ARM virtual machine running in UTM on an Apple Silicon Mac. The Excel slowdown and workbook measurements were simulated.

## Scope and evidence

I asked whether the slowdown affected other apps, whether it happened with other Excel files, and what had changed in the report. The case narrowed to an updated workbook with several thousand added rows and more formulas.

| Workbook | Time to open | Peak CPU usage |
| --- | ---: | ---: |
| Original | 4 seconds | 22% |
| Updated | 45 seconds | 96% |

CPU stayed low with the old file and spiked with the new file. The comparison pointed to the updated workbook. The added rows and formulas changed together, so their individual effects still needed to be tested.

## Recommendation

My recommendation would be to take a look at that new file and figure out why the additional data is causing the CPU spike.

I would hold off on the proposed $1,500 purchase while investigating. If the workbook changes did not explain the spike, I would sort processes by CPU in Windows Task Manager while repeating the same steps and check whether Excel or another high-usage app, such as Edge or Outlook, was consuming CPU at the time.

## How I would verify a fix

I would use a copy of the updated workbook, keep the data and test conditions the same, and change one set of formulas at a time. After each change, I would repeat the open-and-recalculate test and compare elapsed time, peak CPU, and report totals. A repeatable improvement with the same correct totals would support the fix.

The case study is complete. The proposed isolation test and fix verification remain follow-up steps. [Session 001 checkpoint](LAB-001-SESSION-001-CHECKPOINT.md)
