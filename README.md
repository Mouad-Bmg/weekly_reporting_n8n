# weekly_reporting_n8n
Weekly automation workflow that extracts data from Google Sheets, structures it, analyzes it through an AI agent, and then generates a formal report sent to the team. Designed to be scalable, readable, and easily adaptable to other use cases.

This workflow automatically generates a weekly report from structured data in Google Sheets. It runs on a defined schedule, retrieves relevant rows, separates them by type (weekly values and global averages), then dynamically builds a prompt for an AI agent. The agent interprets the data and produces a formal summary, which is then delivered to the team through a communication channel.

The entire process is designed to be modular and easily extensible. It can adapt to other types of reporting, integrate additional data sources, or evolve toward more complex output formats. The workflow is based on clear logic, a strict separation of responsibilities between components, and particular attention to the readability of input and output data.
