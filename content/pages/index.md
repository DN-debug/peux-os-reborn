---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Peux OS | [POS]'
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: |
      \| beautiful, minimal, secure, and highly customized Arch spin-off
    actions:
      - label: DOWNLOAD
        altText: ''
        url: /download
        showIcon: true
        icon: play
        iconPosition: right
        style: primary
        elementId: download
        type: Button
    media:
      url: /images/v-0822ee16.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Features
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Customized Environment
        subtitle: Numbers Done
        text: >+
          Peux OS uses customized XFCE as its default-version. BTRFS is the
          default filesystem with auto-snap enabled. It is the first distro to
          highly customize the default key features of a DE. Aiming to have a
          minimal desktop and yet beautiful.

        actions: []
        elementId: null
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Beautiful yet Secure
        subtitle: ''
        text: >+
          Peux OS not only looks good, it is tied with apps that will help you
          secure your data and privacy. You can sandbox your applications, do
          anonymous surfing among many other things. Oh! and btw "FISH" is the
          default shell.




        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Apps & Packages
        subtitle: ''
        text: >
          PACMAN is the default CLI package manager along with yay as an
          alternative. For GUI, we are Bauh (ba-oo) -- one stop shop for Snaps,
          Flatpaks, Appimages and AUR.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: ''
    images:
      - url: /images/Stackbit-Icon--Streamline-Svg-Logos (1).svg
        altText: stackbit
        type: ImageBlock
      - url: /images/sourceforge-svgrepo-com.svg
        altText: sourceforge
        type: ImageBlock
      - url: /images/Flathub--Streamline-Simple-Icons.svg
        altText: flathub
        type: ImageBlock
      - url: /images/Github-Icon--Streamline-Svg-Logos.svg
        altText: github
        type: ImageBlock
      - url: /images/brand-bittorrent-svgrepo-com.svg
        altText: fosstorrents
        type: ImageBlock
      - url: /images/TLIJ6f01 (1) (1).svg
        altText: selinux
        type: ImageBlock
      - type: ImageBlock
        url: /images/com.github.marhkb.Pods (1).svg
        altText: Pods
        elementId: ''
        styles:
          self:
            borderRadius: medium
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - type: GenericSection
    title:
      type: TitleBlock
      text: Where to download from?
      color: text-dark
    subtitle: ''
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Peux OS
  metaDescription: A unique arch spin-off
  socialImage: /images/800x600_0.png
  type: Seo
type: PageLayout
---
