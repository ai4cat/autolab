---
# Leave the homepage title empty to use the site title
title:
type: home_index



section_titles:
  research: Research
  publication: Selected Publications
  image: Images
  video: Videos
  contact: Contact
  repos: Codebase

# 实验室介绍
heroBlock:
  block: hero
  content:
    title: AI for Science Researcher  
#   image:
#      filename: research_topic.jpg
    text: |
      Building autonomous robotic platforms for catalyst discovery and electrochemical systems
  



# 图片轮播  
heroSlideBlock:
  block: slider

  content:

    slides:

      - title: "AI4C for Autonomous Catalyst Discovery" # desc-title1
        content:  "An interactive visual companion featuring the robotic platform, experimental workflow, and key moments behind the paper" # desc1
        align: left
        background:
          image:
            filename: group_slides/g3.png
            filters:
              brightness: 1 # 0.5 #1
          position: right
          color: '#666'  
 

      - title: "AI4C for Autonomous Catalyst Discovery" # desc-title1
        content:  "An interactive visual companion featuring the robotic platform, experimental workflow, and key moments behind the paper" # desc1
        align: left
        background:
          image:
            filename: group_slides/g2.png
            filters:
              brightness: 1 # 0.5 #1
          position: right
          color: '#666'  
 

      - title: "AI4C for Autonomous Catalyst Discovery" # desc-title1
        content:  "An interactive visual companion featuring the robotic platform, experimental workflow, and key moments behind the paper" # desc1
        align: left
        background:
          image:
            filename: group_slides/g1.png
            filters:
              brightness: 1 # 0.5 #1
          position: right
          color: '#666'  
 

  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    # height controlled by css
    
#    slide_height: '500px'
    
    
    is_fullscreen: false
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 1000
  
  
  


research_capability: 
  - title: AI for Catalyst
#    icon: "fas fa-atom"
    icon: "fas fa-brain"
    desc:   We integrate AI-driven inverse materials design with real experimental validation to accelerate the discovery and optimization of high-performance catalysts.

  - title: Autonomous Experimentation
#    icon: "fas fa-microchip"
    icon: "fas fa-robot"
    desc:  We build autonomous experimental platforms to enable the automation and high-throughput optimization of catalytic materials research, improving both experimental efficiency and result reliability.

  - title: Catalysis
#    icon: "fas fa-wave-square"
    icon: "fas fa-flask"
    desc:  Focus on heterogeneous catalysis and single-atom catalysis, exploring the construction of active sites and reaction mechanisms in key catalytic processes.

  - title: Electrochemistry
#    icon: "fas fa-brain"
    icon: "fas fa-bolt"
    desc:  We investigate electrochemical interfacial processes and energy conversion mechanisms to develop efficient electrocatalytic materials and reaction systems.


 
images_list:
  
  - title:  ""
    path: "images/home/h1.png"
    
  - title:  "Robotic High-Temperature Calaination Workflow"
    path: "images/home/h2.png"
    
  - title:  "Robotic High-Temperature Calaination Workflow"
    path: "images/home/h3.png"
    
  - title:  ""
    path: "images/home/h4.png"
    
  - title:  "Automated Electrochemical Evaluation of ORR"
    path: "images/home/h5.png"

image_show_content: "{{< imgList image_list_var=\"images_list\" >}}"





email_info:
  email: ai4cat@outlook.com
  type: Personal Contact
  name: Dr. Weibin Chen

contact1_info:
  name: Collaborate With Us
  address: We welcome collaborations in AI-driven catalyst discovery, autonomous experimentation, and energy systems


contact2_info:
  name: Remote Access Laboratory
  address: Remote access to automated synthesis, characterization, and testing platforms






---  



