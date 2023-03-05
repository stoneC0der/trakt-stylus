# trakt-stylus
A Dark Mode theme for Trakt.tv

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
