---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
      image:
        filename:
      cta:
        label:
        url:
      cta_alt:
        label:
        url:
      cta_note:
        label:
      text: 
    design:
      background:
        gradient_end: 
        gradient_start: 
        text_color_light:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
#  - block: features
#    content:
#      title: Skills
#      items:
#        - name: Hardware Design
#          description: Verilog and VHDL
#          icon: r-project
#          icon_pack: fab
#        - name: Cryptography
#          description: 
#          icon: chart-line
#          icon_pack: fas
#        - name: Quantum Computer Security
#          description: 
#          icon: camera-retro
#          icon_pack: fas
    design:
      columns: '2'

  - block: markdown
    id: news
    content:
      title: News
      text: |-
        | Date | News |
        |------|------|
        | **Nov 2026** | Paper ["Storing Less in-the-Head: An Area-Efficient Hardware Architecture for SDitH-v2"](/publication/asiacrypt2026/) accepted at Asiacrypt 2026. |
        | **Nov 2026** | New preprint: ["CKKS Acceleration for Next-Wave Homomorphic Encryption"](/publication/2026_eprint/). |
        | **Oct 2026** | Presented ["Accelerating FrodoKEM in Hardware"](/talk/ches2026-0/) and ["Correlation Power Analysis of Hamming-Quasi Cyclic (Extended)"](/talk/ches2026-1/) at CHES 2026. |
        | **Sep 2026** | [Guest lecture at Vellore Institute of Technology (VIT)](/talk/vit2026/). |
        | **Sep 2026** | [Invited talk at ETH Zurich's SAFARI Live Seminar](/talk/eth2026/). |
        | **Sep 2026** | [Invited talk at PKIA 2026, Bengaluru](/talk/pkia2026/). |
        | **Aug 2026** | [Presented at Selected Areas in Cryptography (SAC) 2026, Ottawa](/talk/sac2026/). |
        | **Jul 2026** | [Invited lecture at Cedarcrypt 2026](/talk/cedarcrypt2026/). |
        | **May 2026** | Received the Best Hardware Demo Award (2nd Place) at IEEE HOST 2026 for ["Correlation Power Analysis of Hamming Quasi-Cyclic"](/publication/host2026/). |
        | **May 2026** | Presented ["Performance Analysis of Parameterizable HQC Hardware Architecture"](/talk/cbcrypto2026/) at CBCrypto 2026. |
        | **May 2026** | Paper ["Correlation Power Analysis of Hamming-Quasi Cyclic"](/publication/host2026/) at IEEE HOST 2026. |
        | **Apr 2026** | [Invited talk at PQSecure Technologies](/talk/pqsecure2026/). |
        | **Jan 2026** | [Invited seminar at Microsoft Research](/talk/microsoftresearch2026/). |
        | **Jan 2026** | Paper ["Accelerating FrodoKEM in Hardware"](/publication/ches2026-0/) accepted at CHES 2026. |
    design:
      columns: '2'
  
 
  - block: collection
    id: research-directions
    content:
      title: Research Directions
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - research-directions
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Cryptography and Hardware
#          tag: Deep Learning
#        - name: Quantum Computer Security
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
  
  
  - block: markdown
    id: experience
    content:
      title: Experience
      text: |-
        ### Academic Appointments

        | Organization | Date | Position |
        |---|------|------|
        | <a href="https://www.northwestern.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/northwestern-logo.png" alt="Northwestern University"></a><a class="exp-org" href="https://www.northwestern.edu/" target="_blank" rel="noopener">Northwestern University</a><span class="exp-loc">Evanston, IL, USA</span> | **Jun 2025 – present** | **Postdoctoral Scholar**, Computer Architecture and Security Lab<span class="exp-detail">PI: Prof. Jakub Szefer</span><span class="exp-detail">FHE hardware acceleration; side-channel security of PQC; integrity verification for cloud quantum computers.</span> |
        | <a href="https://www.sinica.edu.tw/en" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/academia-sinica.png" alt="Academia Sinica"></a><a class="exp-org" href="https://www.sinica.edu.tw/en" target="_blank" rel="noopener">Academia Sinica</a><span class="exp-loc">Taipei, Taiwan</span> | **Nov 2025** | **Visiting Scholar**<span class="exp-detail">Host: Prof. Ruben Niederhagen</span><span class="exp-detail">Standardized evaluation methodology for fair comparison of post-quantum cryptographic hardware implementations.</span> |
        | <a href="https://www.yale.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/yale-logo-blue.svg" alt="Yale University"></a><a class="exp-org" href="https://www.yale.edu/" target="_blank" rel="noopener">Yale University</a><span class="exp-loc">New Haven, CT, USA</span> | **Aug 2021 – May 2025** | **Research Assistant**, Computer Architecture and Security Lab<span class="exp-detail">PI: Prof. Jakub Szefer</span><span class="exp-detail">Efficient FPGA and ASIC architectures for NIST post-quantum KEMs and digital signatures; security of cloud-based quantum computers.</span> |
        | <a href="https://www.yale.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/yale-logo-blue.svg" alt="Yale University"></a><a class="exp-org" href="https://www.yale.edu/" target="_blank" rel="noopener">Yale University</a><span class="exp-loc">New Haven, CT, USA</span> | **Oct 2020 – Aug 2021** | **Associate Researcher**, Computer Architecture and Security Lab<span class="exp-detail">PI: Prof. Jakub Szefer</span><span class="exp-detail">FPGA implementations of public-key and post-quantum cryptographic primitives; RISC-V cryptographic accelerators.</span> |
        | <a href="https://www.gmu.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/gmu-logo.png" alt="George Mason University"></a><a class="exp-org" href="https://www.gmu.edu/" target="_blank" rel="noopener">George Mason University</a><span class="exp-loc">Fairfax, VA, USA</span> | **Aug 2015 – Dec 2016** | **Research Assistant**, Cryptographic Engineering Research Group (CERG)<span class="exp-detail">PI: Prof. Kris Gaj</span><span class="exp-detail">High-throughput FPGA architectures for authenticated ciphers in the CAESAR competition.</span> |

        ### [Teaching Appointments](/teaching/)

        | Organization | Date | Position |
        |---|------|------|
        | <a href="https://www.yale.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/yale-logo-blue.svg" alt="Yale University"></a><a class="exp-org" href="https://www.yale.edu/" target="_blank" rel="noopener">Yale University</a><span class="exp-loc">New Haven, CT, USA</span> | **Fall 2022 – Spring 2024** | **Teaching Fellow**<span class="exp-detail">[EENG201: Introduction to Computer Engineering](/teaching/yale_spring24_eeng201/) ([Spring 2023](/teaching/yale_spring23_eeng201/), [Spring 2024](/teaching/yale_spring24_eeng201/); ~100 students)</span><span class="exp-detail">[CPSC415/515: Law, Security, and Logic](/teaching/yale_fall22_cpsc415/) ([Fall 2022](/teaching/yale_fall22_cpsc415/); ~50 students)</span> |
        | <a href="https://www.gmu.edu/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/gmu-logo.png" alt="George Mason University"></a><a class="exp-org" href="https://www.gmu.edu/" target="_blank" rel="noopener">George Mason University</a><span class="exp-loc">Fairfax, VA, USA</span> | **Fall 2015 – Fall 2016** | **Teaching Assistant**<span class="exp-detail">[ECE334: Linear Electronics Lab](/teaching/gmu_fall16_ece334/) ([Fall 2015](/teaching/gmu_fall15_ece334/), [Fall 2016](/teaching/gmu_fall16_ece334/); 3 sections of ~50 students)</span><span class="exp-detail">[ECE448: FPGA Design with VHDL Lab](/teaching/gmu_spring16_ece448/) ([Spring 2016](/teaching/gmu_spring16_ece448/); ~50 students)</span><span class="exp-detail">[ECE545: Digital System Design with VHDL](/teaching/gmu_fall16_ece545/) ([Fall 2015](/teaching/gmu_fall15_ece545/), [Fall 2016](/teaching/gmu_fall16_ece545/); ~25 students)</span><span class="exp-detail">ECE232: Digital System Design Lab (Summer 2016; ~50 students)</span> |

        ### Industry Research Experience

        | Organization | Date | Position |
        |---|------|------|
        | <a href="https://www.sandboxaq.com/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/sandboxaq-logo.png" alt="SandboxAQ"></a><a class="exp-org" href="https://www.sandboxaq.com/" target="_blank" rel="noopener">SandboxAQ</a><span class="exp-loc">Palo Alto, CA, USA</span> | **Nov 2024 – May 2025**<br>**Apr – Dec 2023** | **PQC Research Scientist Resident**<span class="exp-detail">Hardware architectures and performance evaluation for NIST additional post-quantum signature candidates (SDitH) and the NIST-proposed Rijndael-256; open-source RTL released.</span> |
        | <a href="https://www.microsoft.com/en-us/research/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/microsoft-logo.png" alt="Microsoft Research"></a><a class="exp-org" href="https://www.microsoft.com/en-us/research/" target="_blank" rel="noopener">Microsoft Research</a><span class="exp-loc">Redmond, WA, USA</span> | **Jun – Aug 2024** | **Research Intern**<span class="exp-detail">Reconfigurable, side-channel-protected ASIC architecture for an ISO-standardized post-quantum KEM with runtime security-level switching; open-source RTL released.</span> |
        | <a href="https://www.tii.ae/" target="_blank" rel="noopener"><img class="exp-logo" src="/media/logos/tii-logo.png" alt="Technology Innovation Institute"></a><a class="exp-org" href="https://www.tii.ae/" target="_blank" rel="noopener">Technology Innovation Institute</a><span class="exp-loc">(formerly DarkMatter LLC)</span><span class="exp-loc">Abu Dhabi, UAE</span> | **Mar 2017 – Jul 2020** | **Senior Security Researcher**<span class="exp-detail">Production-grade FPGA/ASIC IP for symmetric and asymmetric (elliptic-curve and post-quantum) cryptography; side-channel analysis; hardware reverse engineering and device security assessment.</span> |
    design:
      columns: '2'
  
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: list
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: All Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation  

  - block: markdown
    id: service
    content:
      title: Academic Service
      text: |-
        ### Organizing Committee Member

        | Date | Role |
        |------|------|
        | **Apr 2027** | Publicity Chair, New England Hardware Security Day (NEHWS) 2027 |
        | **Nov 2026** | Poster Session Chair, Quantum Computer Cybersecurity Symposium (QCCS) 2026 |
        | **Apr 2026** | Web Chair, New England Hardware Security Day (NEHWS) 2026 |

        ### Program Committee Member

        | Date | Venue |
        |------|------|
        | **Nov 2026** | Design Automation Conference (DAC) 2027 |
        | **Nov 2026** | IEEE International Symposium on Hardware Oriented Security and Trust (HOST) 2027 |
        | **Oct 2026** | IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2027 |
        | **Aug 2026** | Hardware and Architectural Support for Security and Privacy (HASP) 2026 |
        | **Jun 2026** | International Conference on Security, Privacy and Applied Cryptographic Engineering (SPACE) 2026 |
        | **Dec 2025** | IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS) 2026 |
        | **Oct 2025** | ACM QSec: Quantum Security and Privacy Workshop (co-located with ACM CCS 2025) |
        | **Sep 2025** | Hardware and Architectural Support for Security and Privacy (HASP) 2025 |

        ### Academic Reviewing Service

        | Date | Venue |
        |------|------|
        | **Mar 2026** | IEEE Symposium on Security and Privacy 2026 |
        | **Nov 2025** | International Symposium on Circuits and Systems (ISCAS) 2026 |
        | **Oct 2025** | Journal of Systems Architecture |
        | **Oct 2025** | IEEE Transactions on Computers |
        | **Jul 2025** | CHIPS Journal |
        | **Jun 2024** | IEEE Computer Architecture Letters |
        | **Dec 2023** | International Symposium on Circuits and Systems (ISCAS) 2024 |

        ### Artifact Evaluation Committee Member

        | Date | Venue |
        |------|------|
        | **Oct 2026** | IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2027 |

        ### Session Chair

        | Date | Venue |
        |------|------|
        | **Mar 2026** | 2<sup>nd</sup> IEEE Conference on Secure and Trustworthy Cyber Infrastructure for IoT and Microelectronics (SaTC 2026) |
    design:
      columns: '2'

#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Cryptography and Hardware
#          tag: Deep Learning
#        - name: Quantum Computer Security
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
  - block: markdown
    id: awards
    content:
      title: Awards
      text: |-
        | Date | Award |
        |------|------|
        | **May 2026** | Best Hardware Demo Award (2nd Place), IEEE International Symposium on Hardware Oriented Security and Trust (HOST) 2026, for ["Correlation Power Analysis of Hamming Quasi-Cyclic"](/publication/host2026/) |
        | **Sep 2025** | Best Project Award, [Cyber-Physical Systems Summer School](https://www.cpsschool.eu/), Sardinia, Italy |
        | **Dec 2023** | Best of [IEEE Computer Architecture Letters](https://www.computer.org/csdl/journal/ca) (CAL) Award, for ["A Quantum Computer Trusted Execution Environment"](/publication/cal2023/) |
        | **May 2016** | Outstanding Academic Achievement Award, Department of ECE, [George Mason University](https://www.gmu.edu/) |
        | **Dec 2015** | Best Project Award (3rd Place), Cryptography and Computer Network Security course, [George Mason University](https://www.gmu.edu/) |
        | **Jul 2014** | Certificate of Excellence in Academics, [Jawaharlal Nehru Technological University](https://www.jntuh.ac.in/) |
        | **Oct 2013** | First Prize, Robocup 2k14 (zonal), [Jawaharlal Nehru Technological University](https://www.jntuh.ac.in/) |
    design:
      columns: '2'
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sanjay.deshpande1@northwestern.edu
      phone: 
      appointment_url: 
      address:
        street: 
        city:  Evanston
        region: IL
        postcode: '60208'
        country: United States
        country_code: US
      directions: 
      office_hours:
#        - 'Monday 10:00 to 11:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/sanjaydshpande'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
#      autolink: true
#      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---
