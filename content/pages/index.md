---
type: PageLayout
title: Home
colors: colors-b
backgroundImage:
  type: BackgroundImage
  url: /images/freepik__upload__72068.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Casa vindecării
    subtitle: Câmpina
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
          - pt-6
          - pb-4
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: center
        fontWeight: 400
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Button
        label: Doneaza
        altText: ''
        url: /info/
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/aspecte_20110528_1455382526.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
    text: >+
      <div style="text-align: center">Suntem o asociație creștină care se ocupă
      cu reabilitarea persoanelor care au crescut în mediul stradal. Cu o
      experiență de peste 25 de ani, dorim cu ajutorul lui Dumnezeu să oferim
      șansa la un mediu creștin, reabilitare și încadrare în societate celor
      care doresc dar nu pot să fie schimbați.</div>

  - type: CtaSection
    title: 'Donații:'
    text: |
      *ASOCIATIA CRESTINA CASA VINDECARII - CAMPINA*

      BCR COD SWIFT **RNCBROBU** (BIC)

      **RO94RNCB0208104735400001** (RON)

      **RO13RNCB0208104735400004** (EURO)

      **RO40RNCB0208104735400003** (USD)
    actions:
      - type: Button
        label: Doneaza
        altText: ''
        url: 'https://www.paypal.com/donate/?hosted_button_id=8C3YJUG6SLM9Q'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-0
          - pb-0
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: QuoteSection
    quote: >
      *"Religia curată şi neîntinată înaintea lui Dumnezeu, Tatăl nostru, este
      să cercetăm pe orfani şi pe văduve în necazurile lor şi să ne păzim
      neîntinaţi de lume. "*
    name: 'Iacov 1:27'
    title: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        fontWeight": 500
        textAlign: center
      title:
        fontWeight": 400
        textAlign: center
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
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
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
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
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
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
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
---
