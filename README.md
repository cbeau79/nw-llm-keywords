# Newsweek LLM keyword eval

A review tool for comparing the keywords editors added to an article with the tags an LLM chose.

Reviewers open the page, enter their name, rate each article (Editor better, About equal, LLM better), flag any wrong LLM tags, then export a CSV and send it back.

- `index.html`: the review tool
- `data.json`: the articles being reviewed. Replace this file to load a new batch.

Ratings are stored in each reviewer's browser until they export.
