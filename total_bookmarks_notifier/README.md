# cloudformation
## total\_bookmarks\_notifier.yml

### About
Lambdaを使って特定サイトのはてなブックマーク総数と増加数をSlackに通知する https://cohalz.hatenablog.com/entry/2018/06/16/173818

### Usage
- change `bookmark_url` and `slack_url`
```
Input: >
  {
    "bookmark_url": "http://example.com",
    "slack_url": "https://hooks.slack.com/services/XXXXXXXXX/XXXXXXXXX/xxxxxxxxxxxxxxxxxxxxxxxx"
  }
```
