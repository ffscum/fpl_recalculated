# fpl_recalculated
I have recalculated points for the 2023/24 and 2024/25 seasons using the new rule changes for the 2025/26 season. I think
it's outrageous that this data wasn't released.

Individual fixtures can be seen in ```player_data/by_fixture```. Details of fixtures for the 2023/24 and 2024/25 seasons
are shown in ```23_fixtures.csv``` and ```24_fixtures.csv```. Combined data is shown in ```player_data/combined```. A map 
between fpl and fotmob ids can be seen in ```ids.csv```.

The data has been recalculated to show position changes for the 2025/26 season. 

The limitastions of the data are that it
currently doesn't show goal line clearances bps changes or updated assists. This is much more difficult to find data for. 
Goal line clearances will be added if I have time before the season starts,
but is sufficiently rare that it doesn't affect the data too much.

The files contain both old and new points. New data has 'new' as a prefix, such as 'new_total_points'. It also shows changes
between old and new totals such as 'change_in_total_points'. The combined data also shows PPM (points per match) and PPMPM
(points per million per match). The data can be easily modified to show other interesting data such as points per million
per start, or excluding red cards, etc. 

If you see any issue with the data please let me know here https://www.reddit.com/user/Competitive_Clock896/.