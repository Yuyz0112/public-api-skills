# Authentication

This document describes the authentication methods supported by this API.

## BearerToken

**Type:** http

- **Scheme:** bearer

## OAuth2UserToken

**Type:** oauth2

**authorizationCode flow:**
- Authorization URL: https://api.x.com/2/oauth2/authorize
- Token URL: https://api.x.com/2/oauth2/token
- Scopes:
  - `block.read`: View accounts you have blocked.
  - `bookmark.read`: Read your bookmarked Posts.
  - `bookmark.write`: Create and delete your bookmarks.
  - `dm.read`: Read all your Direct Messages.
  - `dm.write`: Send and manage your Direct Messages.
  - `follows.read`: View accounts you follow and accounts following you.
  - `follows.write`: Follow and unfollow accounts on your behalf.
  - `like.read`: View Posts you have liked and likes you can see.
  - `like.write`: Like and unlike Posts on your behalf.
  - `list.read`: View Lists, members, and followers of Lists you created or are a member of, including private Lists.
  - `list.write`: Create and manage Lists on your behalf.
  - `media.write`: Upload media, such as photos and videos, on your behalf.
  - `mute.read`: View accounts you have muted.
  - `mute.write`: Mute and unmute accounts on your behalf.
  - `offline.access`: Request a refresh token for the app.
  - `space.read`: View all Spaces you have access to.
  - `timeline.read`: View all Custom Timelines you can see, including public Custom Timelines from other developers.
  - `tweet.moderate.write`: Hide and unhide replies to your Posts.
  - `tweet.read`: View all Posts you can see, including those from protected accounts.
  - `tweet.write`: Post and repost on your behalf.
  - `users.read`: View any account you can see, including protected accounts.

## UserToken

**Type:** http

- **Scheme:** OAuth

