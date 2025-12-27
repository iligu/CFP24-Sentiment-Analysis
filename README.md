## College Football Playoff 2024-25: Twitter Sentiment Analysis
# What This Does
Analyzes 11,000+ tweets about CFP teams to understand how fan sentiment changed throughout the playoff run—from first round through the national championship.

# Methodology
1. Data Collection:
- Sample dataset covering Dec 1, 2024 - Jan 20, 2025
- 11 CFP teams tracked across all playoff rounds
- Tweets categorized by timing: pre-game (24hrs before), during, post-game (24hrs after)
- 
2. Sentiment Analysis:
- Hybrid ensemble model combining VADER (speed) + BERT (accuracy)
- 88% classification accuracy
- Scores range from -1 (very negative) to +1 (very positive)

Topic Categories Tracked:
- Offense & defense performance
- Coaching decisions
- Injuries
- Committee/SEC bias discussions
- Strength of schedule
