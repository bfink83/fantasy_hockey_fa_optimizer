# Fantasy Hockey Free Agent Acquisition Optimizer #

This program analyzes players' season statistics and number of teams' games within a matchweek to project players' aggregate weekly statistics in a number of categories* (G, A, PIM, PPP, SHP, HAT, SOG, BLK).
It then cross-references this list with available free agents in the owner's fantasy hockey league to output the free agents with the highest projected statistics in any of the given categories.

*This program is built for a 'categories' point format league.

Written in Python using a Jupyter Notebook.
Libraries include Pandas, numpy, requests, BeautifulSoup, and espn_api.
Data scraped from https://www.hockey-reference.com/
