---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: "# **Ciao Sono Giovanni,**\n\n#### Appassionato del Mondo IT, la mia Formazione è iniziata tardi in questo settore, ma ho sempre avuto una passione irrefrenabile nell'approfondire. Attualmente mi sto formando anche su C#, Visual Studio e .NET, perchè la mia passione sarebbe quella di essere un Game Designer Developer \U0001F916.\n\n"
    media:
      type: ImageBlock
      url: /images/IMG_7370-removebg-preview.png
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-c
    subtitle: 'Hard Skills:'
    images:
      - type: ImageBlock
        altText: HTML
        caption: HTML
        url: /images/html-124-svgrepo-com.svg
      - type: ImageBlock
        url: /images/css3-02-svgrepo-com.svg
        altText: CSS
        caption: CSS
      - type: ImageBlock
        url: /images/bootstrap-fill-svgrepo-com.svg
        altText: BOOTSTRAP
        caption: BOOTSTRAP
      - type: ImageBlock
        url: /images/js01-svgrepo-com.svg
        altText: JS
        caption: JS
      - type: ImageBlock
        url: /images/java-svgrepo-com.svg
        altText: JAVA
        caption: JAVA
      - type: ImageBlock
        url: /images/mysql-svgrepo-com.svg
        altText: MYSQL
        caption: MYSQL
        elementId: ''
      - type: ImageBlock
        url: /images/spring-boot-svgrepo-com.svg
        altText: SPRING
        caption: SPRING
        elementId: ''
    spacing: 41
    columns: 7
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    title: Le mie competenze attuali
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/GioStock'
        styles:
          self:
            textAlign: left
        title: ''
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/giovanni-carotenuto1996/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/giostock'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: "Puoi contattarmi qui \U0001F449\U0001F3FB"
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: E-Mail
    colors: colors-f
    text: |
      [carotenuto.giovanni1996@gmail.com](mailto:thisismyemail.@myemail.me)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Per qualsiasi dubbio, Contattami! \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
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
          width: full
          type: EmailFormControl
        - name: message
          label: messaggio
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
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
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
