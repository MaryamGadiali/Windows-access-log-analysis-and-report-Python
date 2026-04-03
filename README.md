# Windows-access-log-analysis-and-report-Python

This Python project analyses exported data from the Windows security event logs. It uses Pandas to analyse and gather the username attempts (with regex pattern matching) of the sucessful and failed login attempts, and then gathers alerts for varying severities of failed attempts within a rolling window of 5 minutes. These alerts are then exported and stored in an alerts log.
