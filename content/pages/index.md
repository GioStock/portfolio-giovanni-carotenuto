---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
  url: /images/featured-Image1.jpg
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'Ciao, sono Giovanni un Jr. Full Stack Web Developer'
    subtitle: >-
      HTML & CSS | Javascript | Java | SpringBoot | JPA | Hibernate | MyQSL |
      Node.js | JSON | Bootstrap | VSC | Eclipse | REST | MVC | GIT |
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Link
        label: GIT HUB
        altText: ''
        url: 'https://github.com/GioStock'
        showIcon: true
        icon: github
        iconPosition: left
        elementId: ''
      - type: Link
        label: LinkedIn
        altText: ''
        url: 'https://www.linkedin.com/in/giovanni-carotenuto1996/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        elementId: ''
    media:
      type: ImageBlock
      url: /images/IMG_7370-removebg-preview.png
      altText: Foto Personale
      caption: Foto
      elementId: ''
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: 'Project '
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: >-
      Hai qualche Domanda? compila il modulo Qui oppure puoi scrivermi su
      LinkedIn
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: nome
          label: Nome
          hideLabel: true
          placeholder: nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: cognome
          label: cognome
          hideLabel: true
          placeholder: cognome
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: indirizzo
          label: indirizzo
          hideLabel: true
          placeholder: indirizzo
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: Aggiornamenti
          label: Resta Aggiornato
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Invia \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
metaTitle: Portfolio Personale
metaDescription: my portfolio Web Developer
addTitleSuffix: false
---
