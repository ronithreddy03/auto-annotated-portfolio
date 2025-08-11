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
        subtitle: 'Professional Experience:'
        text: |-
          **Full Stack Python Developer**
          **PayPal | San Jose CA**
          *Mar 2025 - Present*

          • Designed and deployed Flask-based microservices leveraging SQLAlchemy and OOP patterns, sustaining 99.9% uptime while supporting high-volume data transactions.
          • Automated CI/CD pipelines in Azure DevOps with Ansible, integrating PyTest and functional testing to reduce deployment issues by 40%.
          • Tuned SQL and NoSQL queries monitored through Azure App Insights, leading to a 50% cut in API and dashboard latency for end users.
          • Delivered real-time KPI dashboards in Tableau sourced from Spark-driven ETL jobs, transforming multi-hour reporting processes into on-demand analytics.
          • Built Python-powered data validation and cleansing workflows, improving ETL dataset accuracy by 35% for downstream analytics.
          • Optimized Apache Spark job configurations for parallelism, boosting batch data processing speed by over 40% in ML feature generation tasks.
          • Presented query optimization metrics and data throughput insights to cross-functional teams, prompting infrastructure adjustments that increased efficiency by 25%.
          • Produced clear documentation outlining ML data workflows, enabling faster onboarding and ensuring consistency in analytics processes.

          **Full Stack Python Developer**
          **Vanguard | Remote**
          *Apr 2024 - Feb 2025*

          • Delivered FastAPI and GraphQL fraud detection services that processed thousands of concurrent user requests, cutting confirmed fraud incidents by 30% through real-time ML scoring.
          • Reduced model training preparation time by 45% by migrating fraud datasets to Snowflake data lakes with AWS Glue ETL workflows, streamlining the ML pipeline.
          • Achieved sub-300ms prediction latency for anomaly detection by deploying AWS Lambda applications backed by DynamoDB and containerized inference endpoints.
          • Boosted analyst productivity by 25% by developing React.js dashboards that visualized streaming ML outputs from Python APIs for instant risk assessment.
          • Maintained 24/7 service availability by orchestrating Kubernetes-based deployments via Jenkins and GitHub Actions, eliminating production downtime during releases.
          • Increased stakeholder trust in ML predictions by implementing SHAP and LIME explainability, enabling clear insight into model decision-making.
          • Elevated deployment quality by coaching junior engineers on Terraform automation, AWS Lambda optimization, and secure API design, leading to a 20% improvement in release success.
          • Ensured reproducible ML model performance by establishing MLflow-based version control and experiment tracking in collaboration with data science teams.

          **Python Developer**
          **Bayer | India**
          *Oct 2020 - Dec 2022*

          • Delivered optimized React.js and Node.js front-end modules integrated with Django and Flask backends over GraphQL, enabling customers to complete transactions 20% faster through reduced API response times.
          • Architected a Django-powered analytics framework with ML-driven insights, leveraging AWS ECS and Lambda to handle over 15TB of daily transaction data, resulting in a 35% increase in throughput.
          • Orchestrated real-time fraud detection by deploying Dockerized Flask microservices with SQLAlchemy to Kubernetes, achieving sub-second predictions via SageMaker and ensuring seamless scalability.
          • Transformed multi-source transactional data pipelines using PySpark to load into Snowflake data lakes, cutting batch latency by 40% and making ML features available ahead of schedule for model training.
          • Enhanced deployment reliability by implementing Jenkins and Ansible pipelines with PyTest validation, which reduced production release issues by 25% and improved post-deployment stability.
          • Improved schema consistency and indexing for MySQL and Redis ETL jobs, raising prediction accuracy of downstream ML models by 18% and eliminating recurring data integration errors.
          • Led a cross-functional team of five to operationalize ML models with SageMaker and MLflow tracking, reducing deployment cycles by 40% and maintaining reproducibility across all releases.
          • Designed monitoring dashboards with Prometheus and Grafana to track API health and latency, sustaining 99.99% uptime for core payment services and enabling proactive incident handling.
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
      submitLabel: 'Submit 🚀'
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
