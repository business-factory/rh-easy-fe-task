# ROI Hunter Frontend Testing Task

The goal of the task is to implement a simple single-page app. It should include this functionality:
- Load last 50 tweets from Twitter API and list these tweets.
- It will also be possible to work with this tweets list - sort by date and the number of likes (either ascending or descending)
- Filter tweets: by date, tweet length, number of likes, number of mentions (eg. @user) and hashtags (eg. #hashtag) in tweets, substring occurrence, an exact match for mention or hashtag. You should use multiple operators dependent on context (eg. equals, not equals, includes, not includes, greater than, less than). The set of filters (and operators) should be easily extensible.
- Statistics of all loaded tweets - shown in a modal window and including these stats: a sum of all likes, average likes per tweet, all mentions in tweets with a number of unique occurrences (eg. @username: 5x).

Technical requirements:
- You can use our mock API(https://storage.googleapis.com/goostav-static-files/rh-easy-data-source.json) or build you own service for loading tweets from Twitter API  
- Usage of ES2015+ syntax / language features
- Utilize React and Twitter Bootstrap for UI (eg. https://react-bootstrap.github.io/components/alerts/)
- You may also use Redux and Immutablejs for state management and data model
- Development in GitHub repository (share it with us and commit to it as you progress)
- As a scaffolding tool, we recommend to use [Create React App](https://github.com/facebook/create-react-app).

If you struggle, you can contact us anytime and we will provide more information. Also if you stuck at one point, just try to implement the rest of functionality.

Good luck and have fun!


Contact: ondrej.parizek@roihunter.com