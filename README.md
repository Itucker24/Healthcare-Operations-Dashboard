# Healthcare Wait-Time & Operations Dashboard

An interactive, executive-facing Power BI dashboard engineered to monitor hospital clinical workflows, track operational capacity, and automatically isolate department bottlenecks.

## Live Dashboard Preview
![Healthcare Dashboard Preview](Healthcare_Operation_Dashboard_SCREENSHOT_.png)

## The Business Problem
Hospital administration required a responsive, centralized business intelligence tool to evaluate patient throughput across distinct clinical departments. Manual spreadsheet analysis caused major delays in identifying structural workflow delays. This solution bridges that gap by providing instantaneous operational insights.

## Core Technical Features & Skills Demonstrated
* **Interactive Data Filtering:** Built a dynamic user-driven Slicer pane to allow cross-filtering of the entire report by specific hospital departments.
* **Executive Summary Architecture:** Engineered dual high-level KPI Summary Cards to track overall patient volume (Sum of Wait Time) alongside the typical patient experience (Average Wait Time).
* **Exception Reporting Logic:** Programmed conditional formatting (`fx` rules) directly into the primary visual layer to automatically flag operational wait-time violations (>30 minutes) in red, leaving compliant departments green.
* **Data Hierarchy & Layout:** Structured canvas layouts to fit strict corporate reporting standards—positioning high-level headline metrics at the top left and comparative depth charts below.

## How to Review This Project
1. Download the source file: `Healthcare_Operations_Dashboard.pbix` from this repository.
2. Launch **Power BI Desktop** on your machine.
3. Open the downloaded file to view the full operational data model and layout configuration.
