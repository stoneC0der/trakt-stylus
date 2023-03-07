# Trakt DarkMode (stylus)
A Dark Mode theme for Trakt.tv
![Up next/Upcoming sections](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/up-next-upcoming.png)
![Recent & Network activity sections](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/recent-activity-and-network.png)
![Recommended section](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/recommended-section.png)
![Profile activity section](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/profile-recent-activity.png)
![Movie details section](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/movie-details.png)
![Comments section](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/comments-section.png)
![Calendar/Search results section](https://github.com/stoneC0der/trakt-stylus/blob/master/screenshots/calendar.png)
## Usage
1- Install for [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
2- Go to [Trakt.tv](trakt.tv) and Click on the extension icon, then look for where it says ***Write extension for: URL*** and click the URL path, a new tab will open with an editor, copy the CSS from the style.styl and paste it in the editor.
On the left side of the editor look for the **Save** button and click to save and that's all, changes will be applied immediatly.

## Features:
- Added rounded border for posters, fantarts
- Remove VIP Ads in Calendar, search result
- Transparency

## Always on Dark mode:
Dark mode is toggle only when system is set to darkmode to have it constantly, just remove all the CSS out of the media query roule

    @media (prefers-color-scheme: dark) {
    
    }
