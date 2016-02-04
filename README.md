# Personal Projects

[Music Recommendation app] (https://github.com/ecatkins/instabilly)

Over the summer of 2015 I attended a coding bootcamp in New York. As our final project, my partner and I built a Django web-app to provide music recommendations to users. The project utilised the Spotify API to download a user's existing music, and provide recommendations based on other 'similar' users in the app. As users 'like' or 'dislike' playlists that are served to them, the app applies a bayesian model to further inform future music recommendations. ([Login] (http://moneymusic.co/) using username: 'ecatkins', password: 'ecatkins' or view screenshots in repo).

[Republican Party Debate - Sentiment Analysis] (https://github.com/adamrj/Debate-Sentiment-Analysis)

This lightweight Django app (also a pair project) was built to track and visualise twitter sentiment during the Republican Party debate in August 2015. A bayes text classification model was trained using over 2 million hand-labelled tweets. We then utilised the twitter API to track and classify tweets relating to each candidate during the debate. This was visualised using the Javascript visualisation library, D3 (see screenshot in repo).

[Elo AFL Rankings] (https://github.com/ecatkins/elo_afl)

Inspired by the data science website FiveThirtyEight's models for NFL and NBA, I developed my own model for the Australian Football League to rank and rate teams using the Elo methodology (which allows the calculation of win probabilities for any match up). After creating the base model, I employed a loss function and grid search to optimise certain parameters which are sport specific.
