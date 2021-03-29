# How to sync GitHub Mirrors

## Hook
In this video, I'm gonna show you a universal way to sync GitHub repos and their mirrors. This practice is essential to have always up-to-date backups. Coming up!

> Static JSC image with background music.

## Content
Hey guys, Vladimír here with JSC electronics. We work on various embedded projects, mostly Arduino. Check out our GitHub page. Link's in the description below.

- What are git mirrors and why do we need them?
- What was my motivation? Syncing Comenio repos...

- Existing solutions
  - GitLab Community mirroring - community version supports only pushing changes, not pulling. In this case, GitLab is your main source of truth.
    > B-roll - show GitHub Community page for mirroring
  - gitlab-mirror-pull
    - https://github.com/ochorocho/gitlab-mirror-pull
    - Unmaintained for over 3 years
    - Docker image
    - I was not able to set this up
    - Runs on the server. You can set up cron job
    > B-roll - show gitlab-mirror-pull GitHub page

  - gitlab-mirrors
    - https://github.com/samrocketman/gitlab-mirrors
    - Unmaintained for over 3 years
    - Written in Python 2
    - Runs locally on your PC. I was not able to set it up.
	> B-roll - show gitlab-mirrors GitHub page

- My solution
  - Simple bash script
  - Hierarchical structure of git repos I want to sync
  - On each level there's a sync script
  > Show screen capture on the screen with a proper comment

- Limitations
  - Not triggered automatically
  - Need to set up manually
  - Only the branches you specify are synced

- Pros
  - Universal solution
  - Low software requirements - bash and git only
  - Ability to simply transfer all repos to another PC

## CTA
There you have it. This solution works for us very well and it took only an hour to write. Let us know in the comments how do you back up your code. Did you like this video? Then hit the Subscribe button for more. Also smash the notification bell. Thanks and see you in the next video!