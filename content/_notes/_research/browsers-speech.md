---
layout: note
path: /browser-screen-readers/
date: "2019-11-30"
title: "Browser Screen Readers"
catagories: []
tags: [research, ]
image: "https://cdn.glitch.com/2ff0e797-b09a-4778-b41b-6fd69beb7cb9%2FdirectNav_closeUp_v0.gif?v=1589715026860"

---

# Extension to Web Flow

This report looks at how to improve the experience of the current chrome web extension in preparation of the Speechify Web App. I go over current screen readers in browsers which have come a long way this last year (2019) and how web extensions connect to their web app. Both from a content importing and full app.

---

# Browsers

To start we need to understand what is already provided to our users for free at a system level. Some browsers are starting to add speech-to-text services to expand their reader views for reducing the noise from new articles. Below are example of what major browsers and native (provided on os install) browsers are offering.


### Chrome

There is not really a native solution available unless you install [ChromeVox](https://www.chromevox.com), which is by google but would seam to be considered a legacy extension. But would seam to act more as a way to navigate a webpage thats being dictated and less about reading selected portions of text. I had some trouble getting the extension to work, so I included a video from Google instead.

<iframe width="560" height="315" src="https://www.youtube.com/embed/NyuuK7tB9fM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Edge

After years on not knowing which way is up, Edge is final has good accessibility options. There is a native screen reader with a slightly computerized voice that will read article and highlighted text to you. It's not the same playback quality as Speechify but it's a great native option.

![Edge Screen Reader Example](https://d2w9rnfcy7mm78.cloudfront.net/7474270/original_89717d13fe68ba366394b5eace81693b.png?1590738910?bc=0)

### Safari

Safari has the best free or native experience. Its optimized to work natively with the accessibility tools in macOS. They also have a lot os additional options based on how you read best. You can for example underline the current sentence being spoken, or highlight the current word spoken. Or just highlight text anywhere in macOS, including safari, and use the same shortcuts to ready anything. For those that use speechify for accessibility reasons keeping a native app presence the only does screen reading would be tremendously valuable. Especially because they likely are using Speechify for a lot more ways that we haven't asked about, for example writing papers.

![Safari Screen Reader Example](https://d2w9rnfcy7mm78.cloudfront.net/7474272/original_f1f919f7968a708a910a2e860a1e9e45.png?1590738911?bc=0)

### Firefox

Firefox now has a build in screen reader which integrates directly into your pocket account. (Has Speechify ever explored this type or projects?) Firefox own pocket, and as screen readers become standard in browsers it could be good to look into opera, or others to partner with. The screen reader is limited to 3x playback and has limited a limited voice selection. But the voice quality is decent.

![Firefox Screen Reader Example](https://d2w9rnfcy7mm78.cloudfront.net/7474269/original_2f25108a9774b24d07e2b8e7e2f05708.png?1590738909?bc=0)
