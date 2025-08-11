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
    text: >+
      # Hey — I'm Ronith Reddy Prodduturi

      **Developer • Digital Artist • Consultant**

      I build data-driven products, clean data pipelines, and visuals people
      actually use. Based in **Dallas, TX** (open to TX/CA & remote).
      Lately I've shipped fraud-detection prototypes, time-series forecasts,
      and music analytics dashboards that turn messy data into clear decisions.
      Curious, fast, and pragmatic—if you like shipping, keep scrolling! 🚀

    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Portrait of Ronith
    styles:
      self:
        height: auto
        width: wide
        margin: [mt-0, mb-0, ml-0, mr-0]
        padding: [pt-16, pb-12, pl-4, pr-4]
        textAlign: left
    type: HeroSection

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-8, pb-8, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I work with these tools:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Python
        caption: Python
      - type: ImageBlock
        url: /images/logo2.svg
        altText: SQL
        caption: SQL
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Power BI
        caption: Power BI
      - type: ImageBlock
        url: /images/logo4.svg
        altText: AWS
        caption: AWS
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Azure
        caption: Azure
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding: [pt-8, pb-8, pl-4, pr-4]
        textAlign: left

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-8, pb-8, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: FeaturedItemsSection
    subtitle: 'Find me here:'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Website
            url: 'https://ronithreddy.netlify.app/'
        styles: { self: { textAlign: left } }
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/REPLACE_WITH_YOUR_HANDLE' # TODO
        styles: { self: { textAlign: left } }
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/REPLACE_SLUG' # TODO
        styles: { self: { textAlign: left } }
      - type: FeaturedItem
        actions:
          - type: Link
            label: Kaggle
            url: 'https://kaggle.com/REPLACE_HANDLE' # TODO
        styles: { self: { textAlign: left } }
      - type: FeaturedItem
        actions:
          - type: Link
            label: Email
            url: 'mailto:REPLACE@EMAIL.COM' # TODO
        styles: { self: { textAlign: left } }
      - type: FeaturedItem
        actions:
          - type: Link
            label: Resume (PDF)
            url: '/assets/Resume.pdf'
        styles: { self: { textAlign: left } }
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding: [pt-8, pb-8, pl-4, pr-4]

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-12, pb-12, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: Python
      - type: Label
        label: SQL
      - type: Label
        label: Power BI
      - type: Label
        label: Tableau
      - type: Label
        label: Pandas / NumPy
      - type: Label
        label: scikit-learn
      - type: Label
        label: Time Series (ARIMA/Prophet)
      - type: Label
        label: Anomaly Detection (Isolation Forest)
      - type: Label
        label: PySpark
      - type: Label
        label: AWS (S3, Lambda, Glue)
      - type: Label
        label: Azure (ADF)
      - type: Label
        label: Docker / Git
      - type: Label
        label: CI/CD
      - type: Label
        label: Data Modeling
      - type: Label
        label: Storytelling with Data

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-12, pb-12, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [REPLACE@EMAIL.COM](mailto:REPLACE@EMAIL.COM)  <!-- TODO: update -->

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-8, pb-8, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * **Data Analyst — AtlasProGroup**  
            Build Power BI dashboards, write SQL for reporting & QA, and
            close the loop with stakeholders to iterate fast.

          **Projects (Selected)**

          * **Credit Card Fraud Detection (Isolation Forest):** Prototype to flag suspicious transactions and explain spikes.
          * **Music Data Analysis Dashboard:** Cleaned streaming/event data into clear artist & trend views (Power BI).
          * **Trend Forecasting Dashboard:** Lightweight time-series forecasts for KPIs with drift monitoring.

          **Past**

          * Freelance/Academic data projects across analytics & ML.
        styles:
          self:
            textAlign: left

      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2024**

          * **M.S., Technology Management — Lindsey Wilson University**

          **2022**

          * **B.S., Computer Science — GITAM University**
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding: [pt-8, pb-8, pl-4, pr-4]
        textAlign: left

  - type: DividerSection
    styles:
      self:
        width: wide
        padding: [pt-12, pb-12, pl-4, pr-4]
        borderWidth: 1
        borderStyle: solid

  - type: ContactSection
    backgroundSize: full
    title: "Let's talk... 💬"
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project or role
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to receive updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit 🚀"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin: [mt-0, mb-0, ml-4, mr-4]
        padding: [pt-12, pb-12, pr-4, pl-4]
        flexDirection: row
        textAlign: left
---
