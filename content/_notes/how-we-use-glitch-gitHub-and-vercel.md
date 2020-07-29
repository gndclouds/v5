---
layout: project
permalink: /github2discord/
externalurl: ""
date: "2019-07-19"
title: "How we use Glitch, GitHub, & Zeit"
tags: [ webhook, discord, experiments ]
excerpt: "A preview of my first post"
---

Possible Intro: (for twitter or a post?)

Over the past few months our team has been working interdependently and remotely on some web project which we are going to share soon but in the mean time I wanted to share a bit about our current pipeline.

**Glitch** for development → **GitHub** for version control → **Zeit** for hosting or **Render** for hosting

---

## Updating and publishing projects:

Here is an overview on how we publish content remotely with each other through using [Glitch](https://glitch.com) for development, [Github](https://glitch.com) for version control, and [Zeit](https://zeit.co/) for hosting.

1. Head to [Glitch](https://glitch.com/@tinyfactories) and make any edits to the project.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bcadd01e-9047-4d8e-b3f9-b510aadc03da/Screen_Shot_2019-07-30_at_15.35.22.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bcadd01e-9047-4d8e-b3f9-b510aadc03da/Screen_Shot_2019-07-30_at_15.35.22.png)

2. Once edits are complete click `tools` button and then select `Git, Import and Export`.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/72ff6c15-b417-47a6-a8a8-1c6ebc3380a5/Screen_Shot_2019-07-30_at_15.37.23.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/72ff6c15-b417-47a6-a8a8-1c6ebc3380a5/Screen_Shot_2019-07-30_at_15.37.23.png)

3. If you see `Connect to Github` button then click it if not select `Export to GitHub`.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eb7cf851-4a44-4432-8e05-665eba19fc24/Screen_Shot_2019-07-30_at_15.40.45.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eb7cf851-4a44-4432-8e05-665eba19fc24/Screen_Shot_2019-07-30_at_15.40.45.png)

4. Next enter the GitHub-account/repo-name you would like to push to in the popup and click `ok`.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/43a033d9-bf8e-45d9-91b1-872d13961aa3/Screen_Shot_2019-07-30_at_15.42.04.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/43a033d9-bf8e-45d9-91b1-872d13961aa3/Screen_Shot_2019-07-30_at_15.42.04.png)

5. Enter a detailed decrition of what you are pushing. for example "Updated SEO with new branding" and click `ok`.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cef24187-5bcb-4a9f-83ab-ad7c574da11d/Screen_Shot_2019-07-30_at_15.46.45.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cef24187-5bcb-4a9f-83ab-ad7c574da11d/Screen_Shot_2019-07-30_at_15.46.45.png)

6. Now head on over to your [GitHub](https://github.com/tiny-factories) repo and click Compare & pull request. If you do not see this try pushing again from Glitch.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b3dce750-fe96-4ae9-bdb5-b2e5264cca03/Screen_Shot_2019-07-30_at_15.58.10.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b3dce750-fe96-4ae9-bdb5-b2e5264cca03/Screen_Shot_2019-07-30_at_15.58.10.png)

7. Add additional comments and click `Create pull request`.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/49746487-5747-4970-9705-3a9eecee0878/Screen_Shot_2019-07-30_at_16.01.06.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/49746487-5747-4970-9705-3a9eecee0878/Screen_Shot_2019-07-30_at_16.01.06.png)

8. Next [now.sh](http://now.sh) will check the code and if everything looks ✅  then you can click `Merge pull request` to push the changes to now.sh and the production or live build.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2a7b3ccb-c36a-46ad-b50e-7605e24c868b/Screen_Shot_2019-07-30_at_16.07.02.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2a7b3ccb-c36a-46ad-b50e-7605e24c868b/Screen_Shot_2019-07-30_at_16.07.02.png)

9. You will be asked to confirm the merge.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc48b6e3-9cc2-4d18-b579-3132ed36e67f/Screen_Shot_2019-07-30_at_16.07.49.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc48b6e3-9cc2-4d18-b579-3132ed36e67f/Screen_Shot_2019-07-30_at_16.07.49.png)

10. Thats it! 🎉 Now just wait for your update to go live. If you what to check the progress head on over to your [Zeit Dashboard](https://zeit.co/tiny-factories/tinyfactories) and click on the project to see the status of the lates build.

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a15c3831-bfa4-4da6-b039-2a9bc0aeabcc/Screen_Shot_2019-07-30_at_16.10.32.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a15c3831-bfa4-4da6-b039-2a9bc0aeabcc/Screen_Shot_2019-07-30_at_16.10.32.png)

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82295746-b9da-46a1-be28-21b9d1e7b4b0/Screen_Shot_2019-07-30_at_16.10.55.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82295746-b9da-46a1-be28-21b9d1e7b4b0/Screen_Shot_2019-07-30_at_16.10.55.png)

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8ff6e7de-b7cf-4fce-9293-184dd1d60420/Screen_Shot_2019-07-30_at_16.17.57.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8ff6e7de-b7cf-4fce-9293-184dd1d60420/Screen_Shot_2019-07-30_at_16.17.57.png)

---

Future Features Topics:

- [ ]  How to add api keys to glitch and zeit
- [ ]  How to start a new project pipeline
- [ ]  Publish straight from Glitch to Zeit
