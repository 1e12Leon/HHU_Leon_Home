---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 硕士
          company: 河海大学
          company_url: https://www.hhu.edu.cn/
          location: 中国南京
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              研究方向:

              * 计算机视觉
              * 无人机视角多模态目标检测
              * 无人机视角人脸检测与识别
        - title: 学士
          company: 河海大学
          company_url: https://www.hhu.edu.cn/
          location: 中国南京
          date_start: '2018-09-01'
          date_end: '2022-07-01'
          description: 计算机科学与技术
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2022-08-01'
          description: ''
          organization: 工信部&教育部
          organization_url: http://www.cnsoftbei.com/
          title: 第十一届中国软件杯全国三等奖
          url: ''
        - date_end: ''
          date_start: '2021-05-01'
          description: ''
          organization: MCM
          organization_url: https://www.contest.comap.com/undergraduate/contests/mcm
          title: '美国大学生数学建模Meritorious Winner'
          url: ''
        - date_end: '2020-05-01'
          date_start: '2020-03-01'
          description: ''
          organization: 中国计算机学会
          organization_url: https://www.ccf.org.cn/
          title: '科技战疫·数据公益挑战赛一阶段优胜奖&前十名'
          url: ''
        - date_end: ''
          date_start: '2022-11-01'
          description: ''
          organization: 江苏计算机学会&计算机工程与网络国际会议
          organization_url: https://www.jscs.org.cn/
          title: '远见杯元智能数据挑战大赛二等奖'
          url: ''
        - date_end: ''
          date_start: '2021-05-01'
          description: ''
          organization: 江苏省共青团
          organization_url: http://www.jiangsugqt.org/
          title: '第十七届挑战杯江苏省二等奖'
          url: ''          
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      items:
        - title: 
          date_start: '2023-10-01'
          description: ''
          organization: CCBR2023
          organization_url: https://ccbr99.cn/
          title: 'Single Sample Face Recognition Based on Identity-Attribute Disentanglement and Adversarial Feature Augmentation'
          url: './content/publication/conference-paper/Single_Sample_Face_Recognition_Based_on_Identity_Attribute_Disentanglement_and_Adversarial_Feature_Augmentation.pdf' 
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: liangyao@hhu.edu.cn
      address:
        street: 江苏省南京市佛城西路8号河海大学江宁校区计算机与信息学院
        postcode: '211100'
        country: China
      office_hours:
        - '10:00 to 20:00'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
