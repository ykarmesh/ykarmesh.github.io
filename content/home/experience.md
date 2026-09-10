---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

experience:
  - title: AI Scientist Intern
    company: Mistral AI
    company_url: 'https://mistral.ai'
    location: Palo Alto
    date_start: '2025-05-01'
    date_end: '2026-07-31'
    description: |2-
        * Initiated and led the Multimodal Reasoning effort, establishing end-to-end training, evaluation, and data pipelines.
        * Developing rubric-guided reinforcement learning methods to reduce visual hallucinations and improve grounded reasoning in multimodal language models.

  - title: Intern, Technical Staff, AI
    company: Yutori
    company_url: 'https://yutori.com'
    location: San Francisco
    date_start: '2024-08-01'
    date_end: '2024-11-30'
    description: |2-
        * Developed deployment pipelines for web agents to operate on real websites while effectively avoiding bot detection.
        * Created data filtering pipeline and trained VLM-based agents for web navigation tasks.

  - title: AI Resident
    company: Fundamental AI Research (FAIR), Meta AI
    company_url: 'https://ai.meta.com/research/'
    location: Menlo Park
    date_start: '2021-08-01'
    date_end: '2023-06-30'
    description: |2-
        * Researched self-supervised pretraining techniques for learning useful visual representations for embodied agents.
        * Released the HM3D-Semantics (HM3DSem) dataset and the Open-Vocabulary Mobile Manipulation (OVMM) benchmark based on the Habitat Simulator.

  - title: Senior Robotics Engineer
    company: ISEE Inc.
    company_url: 'https://www.isee.ai'
    location: Boston
    date_start: '2020-07-01'
    date_end: '2021-08-31'
    description: |2-
        * Explored deep uncertainty estimation techniques for predicting the closed loop tracking performance of an autonomous vehicle controller. Estimated the collision probability of the AV with respect to obstacles in an occupancy grid.
        * Improved the trajectory optimization planner and robustified its collision checking. This led to an increased confidence in its performance and resulted in its deployment on the AV.

  - title: Software Development Intern
    company: ISEE Inc.
    company_url: 'https://www.isee.ai'
    location: Boston
    date_start: '2019-05-01'
    date_end: '2019-08-31'
    description: |2-
        * Built toolboxes to automate the system identification and calibration procedure of ISEE's vehicles.
        * Researched and implemented various vehicle and tire models for control applications in autonomous vehicles.

  - title: Intern, Autonomous Driving Team
    company: MathWorks
    company_url: 'https://www.mathworks.com'
    location: Hyderabad
    date_start: '2017-08-01'
    date_end: '2017-11-30'
    description: |2-
        * Worked on improving the localization module of an autonomous vehicle by fusing ORB-SLAM output with GPS, IMU, and wheel odometry.

  # - title: Graduate Research Assistant
  #   company: Robotics Research Center, IIITH
  #   company_url: 'https://robotics.iiit.ac.in/'
  #   location: Hyderabad
  #   date_start: '2017-08-01'
  #   date_end: '2018-06-12'
  #   description: |2-
  #       * Created a Q-Learning based planner to prevent monocular slam failure on non-holonomic robots.
  #       * Developed a simulation environment in Gym-Gazebo for training, with Navigation Stack for planning and ORB-SLAM for perception and localization.

#   - title: Intern, Autonomous Driving Team
#     company: Mathworks
#     company_url: 'https://www.mathworks.com/'
#     location: Hyderabad
#     date_start: '2017-08-01'
#     date_end: '2017-11-24'
#     description: |2-
#         * Optimized ORB-SLAM and made it more robust to fuse its position output with RTK-GPS, IMU & Wheel Encoder data using an EKF.
#         * Worked on SLAM pose covariance estimation and extrinsic calibration of IMU and cameras        

#   - title: Research Intern
#     company: Intelligent Vehicles Lab, National Taiwan University
#     company_url: 'http://140.112.14.7/~kangli1234/IVMechatronics/index.html'
#     location: Taipei
#     date_start: '2016-05-15'
#     date_end: '2016-07-20'
#     description: |2-
#         * Developed a two-level motion planner, utilizing the A-star (A*) and Rapidly-exploring Random Tree (RRT) algorithm, on a local map built using laser scanners for an electric golf cart.
#         * Created a vehicle model and forward-simulated the vehicle trajectory using Pure Pursuit steering controller and Proportional-Integral (PI) speed controller.
---
