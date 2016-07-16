# NCF
## TODO LIST ON UPDATE:

### 1. 
`/root/mqp-server/webserver/public/index.html` -> add `<link rel="stylesheet" type="text/css" href="override.css">`.
`/root/mqp-server/webserver/public/index.html` -> add `<script src="plugin.js"></script>`.
### 2.
Place *git* `override.css` in `/root/mqp-server/webserver/public`.
Place *git* `plugin.js` in `/root/mqp-server/webserver/public`.
### 3.
Open `index.html`
### 4.
Change: 
```
Around line 577:
data-ng-show="roomSettings.altControls" => data-ng-show="!roomSettings.altControls"
AND 
Around line 598:
data-ng-show="!roomSettings.altControls" => data-ng-show="roomSettings.altControls"
```
### 5.
Change on 2nd `controls` class:
```
JOIN | UPVOTE | GRAB | DOWNVOTE | SNOOZE
```
### 6.
Remove guests icon:
```
Line 546: <div class="mdi mdi-account-multiple-outline" data-ng-show="roomSettings.separateUserCount"></div>
```
### 7.
Add `nc_fantasia.jpg` to `/root/mqp-server/webserver/public/lib/img`

