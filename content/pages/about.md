---
type: PageLayout
title: About
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: The Journey
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: "Peux OS was initially a customized arch for my personal use. It was never really an idea to convert it into a distro. COVID-19 boredom made it possible. Bitter truth is that you'll find many arch-based distros out there. \n\nThen why Peux OS? Well, its a proof that community-driven ideas and already existing tools can make the experience so much better. Further tweaks can make it more than better.\n\n\nNow, honestly speaking, it's just a hobby.\_The project began in year 2020 with test releases and the first stable ISO was released in Feb 2021. It's been a bit more than 4 years now, out of which this project stayed dormant for 2 years due to my personal issues. \n\nPeux OS received a lot of positive reviews and some not so good ones. I only wanted to share my way of customizing the \"LINUX\" environment with the World, not in a competitive manner but as a guide to beginners and intermediate Linux users. Peux OS is not really a distro, it is more of a highly customized spin-off of Arch Linux, bundled with some very useful tools. \n\nIt made the headlines with its 4 Desktop Environments, XFCE being the most unique of all, that was followed up with 9 Tiling Window Managers. That being said, on its wake after 2 years the plans have changed, Peux OS will only ship XFCE. \n\nI hope to continue this journey and keep sharing my experience with you good people out there."
    actions: []
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: ''
    text: ''
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: 'https://www.youtube.com/watch?v=eSYdnToDpjU&t=11s'
      autoplay: false
      loop: false
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
slug: about
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
