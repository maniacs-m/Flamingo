# Flamingo
Minimalist Hacker News Reader

<p align="center">
  <img src="https://i.imgur.com/rYp9ajL.png" style="max-height:400px;">
</p>

## Purpose
I'm an avid reader of Hacker News, which to me is one of the best news aggregator in relation to my interests (Tech, Science, World News). HN as some flaws though :
- It doesn't provide any excerpt or summary
- There are no images
- There are no indicator of article length
- It's overall quite unappealing to the reader

The purpose of this project is to provide the best experience possible for reading HN top stories, similar to what Yahoo Digest did offer before being discontinued. I've open-sourced both the code and the design file (.sketch).

You can find this app on the AppStore here : https://itunes.apple.com/app/id817164332

## Basic principle
Here is what the app currently does :
- [x] Fetch HN top stories
- [x] Get curated previews of each story through [Mercury API](https://mercury.postlight.com/)
- [x] Load sotries images and grab the first to finish. This is our head article
- [x] Display stories "readtime" based on the content word count
- [x] Show individual stories using `SFSafariViewController` with reader mod on

## Roadmap
There are a lot of ways to improve the experience even further. I'm open to any ideas the community may have!
Here are a few :
- [ ] Display individual stories in custom webview
- [ ] Provide a way to switch between top and new stories
- [ ] Allow infinite loading

## One more thing
Flamingo, what a cool name! How did I find it you ask? I actually used [the Qolor app](https://itunes.apple.com/app/id973492333) on the Hacker News orange, and it was the result :)
