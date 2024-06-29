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
  - elementId: hero
    colors: colors-f
    backgroundSize: full
    title: 'Ciao, sono Giovanni un Jr. Full Stack Web Developer'
    subtitle: >-
      HTML & CSS | Javascript | Java | SpringBoot | JPA | Hibernate | MySQL |
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
        label: GitHub
        altText: 'Visita il mio GitHub'
        url: 'https://github.com/GioStock'
        showIcon: true
        icon: github
        iconPosition: left
        elementId: github-link
      - type: Link
        label: LinkedIn
        altText: 'Visita il mio LinkedIn'
        url: 'https://www.linkedin.com/in/giovanni-carotenuto1996/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        elementId: linkedin-link
    media:
      type: ImageBlock
      url: /images/IMG_7370-removebg-preview.png
      altText: Foto Personale
      caption: Foto
      elementId: hero-image
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: featured-projects
    actions:
      - type: Link
        label: Vedi tutti i progetti
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
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
          - pt-5
          - pb-10
          - pl-10
          - pr-10
        justifyContent: center
        borderRadius: xx-small
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Progetti Recenti
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: >-
      Hai qualche domanda? Compila il modulo qui sotto oppure scrivimi su LinkedIn.
    form:
      type: FormBlock
      elementId: contact-form
      fields:
        - name: nome
          label: Nome
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: cognome
          label: Cognome
          hideLabel: true
          placeholder: Cognome
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
          label: Indirizzo
          hideLabel: true
          placeholder: Indirizzo
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: aggiornamenti
          label: Resta Aggiornato
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Invia 🚀"
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
metaDescription: Il portfolio di Giovanni Carotenuto, Jr. Full Stack Web Developer.
addTitleSuffix: false
---