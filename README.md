# gh-pages2


# Images
avatar: 'avatar.webp'
background: 'background.webp'
favicon: 'favicon.ico'

# Online profiles
#dribbble: 'mydribbble'
facebook: 'myfacebook'
twitter: 'mytwitter'
#linkedin: 'mylinkedin'
instagram: 'myinsta'
#pinterest: 'mypinterest'
youtube: 'myyoutube'
github-user: 'mygithub'
#gitlab-user: ''
#codepen: ''
#steam: ''
#soundcloud: ''
#lastfm: ''
#stack-overflow: ''
#reddit: ''
#rubygems: ''
#medium:  ''
tumblr: 'mytumblr'
weibo: 'myweibo'
vk: 'myvk'
blog_url: 'myblog.blog.com'
email: 'hello@example.com'
messenger: 'myfbchat'

social-links-order: [github-user, facebook, twitter, instagram, tumblr, pinterest, linkedin, youtube, vk, weibo, dribbble, messenger, blog_url, email]

# Yaml manifest of supported social links
# Requirements:
# `name`
#     - plain-text name of the site (e.g. twitter)
#     - **mandatory**
# `url-pattern`
#     - site URL pattern containing a placeholder string (e.g. twitter.com/__USERNAME__)
#     - placeholder will be replaced by username or value specified in _config.yml (e.g. twitter.com/mytwitter)
#     - **mandatory**
# `url-scheme`
#     - the hardcoded URI/URN url-scheme (e.g. https://)
#     - can be one of: ['https://', 'http://', 'mailto:']
#     - defaults to '//'
#     - **optional**
# `icon-class`
#     - the font awesome icon class names
#     - font-awesome free and supports `fas` (solid) and `fab` (brands) styles
#     - defaults to `fab` style and uses value of `name` attribute (e.g. fab fa-2x fa-twitter)
#     - **optional**
social-links:
  - name: facebook
    url-pattern: facebook.com/__USERNAME__
    icon-class: fab fa-2x fa-facebook-f

  - name: twitter
    url-pattern: twitter.com/__USERNAME__

  - name: linkedin
    url-pattern: linkedin.com/in/__USERNAME__

  - name: google-plus
    url-pattern: plus.google.com/+__USERNAME__

  - name: vk
    url-pattern: vk.com/__USERNAME__

  - name: weibo
    url-pattern: weibo.com/__USERNAME__

  - name: instagram
    url-pattern: instagram.com/__USERNAME__

  - name: flickr
    url-pattern: flickr.com/__USERNAME__

  - name: pinterest
    url-pattern: pinterest.com/__USERNAME__

  - name: github-user
    url-pattern: github.com/__USERNAME__
    icon-class: fab fa-2x fa-github

  - name: gitlab-user
    url-pattern: gitlab.com/__USERNAME__
    icon-class: fab fa-2x fa-gitlab

  - name: codepen
    url-pattern: codepen.com/__USERNAME__

  - name: stack-overflow
    url-pattern: stackoverflow.com/users/__USERNAME__

  - name: reddit
    url-pattern: reddit.com/user/__USERNAME__

  - name: rubygems
    url-pattern: rubygems.org/profiles/__USERNAME__
    icon-class: far fa-2x fa-gem

  - name: steam
    url-pattern: steamcommunity.com/id/__USERNAME__

  - name: youtube
    url-pattern: youtube.com/__USERNAME__

  - name: vimeo
    url-pattern: vimeo.com/__USERNAME__

  - name: soundcloud
    url-pattern: soundcloud.com/__USERNAME__

  - name: lastfm
    url-pattern: last.fm/user/__USERNAME__

  - name: medium
    url-pattern: medium.com/@__USERNAME__

  - name: tumblr
    url-pattern: __USERNAME__.tumblr.com

  - name: dribbble
    url-pattern: dribbble.com/__USERNAME__

  - name: keybase
    url-pattern: keybase.io/__USERNAME__

  - name: messenger
    url-pattern: m.me/__USERNAME__
    icon-class: fab fa-2x fa-facebook-messenger

  - name: telegram
    url-pattern: telegram.me/__USERNAME__

  - name: snapchat
    url-pattern: snapchat.com/add/__USERNAME__

  - name: quora
    url-pattern: www.quora.com/profile/__USERNAME__

  - name: blog_url
    url-pattern: '__USERNAME__'
    icon-class: fas fa-2x fa-blog

  - name: email
    url-scheme: 'mailto:'
    url-pattern: '__USERNAME__'
    icon-class: far fa-2x fa-envelope-open
