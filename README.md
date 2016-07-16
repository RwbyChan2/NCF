# NCF
## TODO LIST ON UPDATE:
1. `/root/mqp-server/webserver/public/index.html` -> add override.css file.
2. Place *git* `override.css` in `/root/mqp-server/webserver/public`.
3. Open `index.html`
4. Change:
```
Around line 577:
data-ng-show="roomSettings.altControls" => data-ng-show="!roomSettings.altControls"
AND 
Around line 598:
data-ng-show="!roomSettings.altControls" => data-ng-show="roomSettings.altControls"
```
5. Change on 2nd `controls` class:
```
JOIN | UPVOTE | GRAB | DOWNVOTE | SNOOZE
```
