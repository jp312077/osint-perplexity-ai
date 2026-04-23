# OSINT Investigation: Perplexity AI vs. Publishers

A documented OSINT investigation into claims that Perplexity AI 
scraped publisher content in violation of robots.txt directives.

## Research Question
Did publicly available data confirm allegations of unauthorized 
content copying by Perplexity AI, and did the company change 
its behavior after the accusations became public?

## Key Findings
- robots.txt grew from 89 to 451 characters between January and August 2024
- Number of Disallow rules increased from 2 to 6 after the scandal
- Perplexity never added an explicit "User-agent: PerplexityBot" rule
- The biggest structural change occurred in May 2024 – before the Wired article
- Google Trends data shows a short-term drop in interest after the scandal (88→65)
- The company raised funding in June 2024 during the crisis

## Methods
- Wayback Machine (robots.txt historical analysis)
- Wayback Machine CDX API
- Crunchbase (funding data)
- Google Trends (exported CSV data)
- Google Dorking

## Tools & Stack
Python, requests, matplotlib, Google Colab

## Course
OSINT Investigation Project | Silesian University of Technology | 2026
