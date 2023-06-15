---
# Leave the homepage title empty to use the site title
title:
date: 2022-3-26
type: landing

sections:
  - block: markdown
    content:
      title: StarCraftImage
      subtitle: Dataset and code 
      text: |-
        StarCraftImage is a large-scale easy to use spatial reasoning including 3.6 million images summarizing 10-seconds of human-played matches from the StarCraft II video game.
        This work was presented in CVPR 23' via the publication: [StarCraftImage: A Dataset For Prototyping Spatial Reasoning Methods For Multi-Agent Environments](https://openaccess.thecvf.com/content/CVPR2023/html/Kulinski_StarCraftImage_A_Dataset_for_Prototyping_Spatial_Reasoning_Methods_for_Multi-Agent_CVPR_2023_paper.html)
        
        <figure>
            <img src="hyper-cifar-mnist-example-grids.png" alt="Dataset Overview Figure">
        </figure>

        <!--

        </br>
        
        This website is currently under construction, but in the meantime please see [our github repository](https://github.com/inouye-lab/starcraftimage) to see how you can use the `StarCraftImage` datasets!
            
        For more information or to be contacted when this is ready, please email us at [dinouye@purdue.edu](mailto:dinouye@purdue.edu).
        -->
        
        <div class="row">
            <div class="box">
                <a href="/docs/">
                    <h3>Get Started</h3>
                </a>
            </div>
            <div class="box">
                <a href="https://github.com/inouye-lab/starcraftimage">
                    <h3>GitHub Repo</h3>
                </a>
            </div>
            <div class="box">
                <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Kulinski_StarCraftImage_A_Dataset_for_Prototyping_Spatial_Reasoning_Methods_for_Multi-Agent_CVPR_2023_paper.pdf">
                    <h3>CVPR 23' Paper</h3>
                </a>
            </div>
        </div>

        <style>
            .row {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                align-items: center;
            }
            
            .box {
                flex: 1 1 300px;
                margin: 10px;
                text-align: center;
                background-color: #4682B4;
            }
            
            .box h3 {
                margin-top: 10px;
            }
            
            @media (max-width: 768px) {
                .box {
                    flex-basis: 100%;
                }
            }
        </style>

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
#   - block: portfolio
#     id: Documentation
#     content:
#       text: |-
#       filters:
#         # Folders to display content from
#         folders:
#           - docs
#           - github
#         # Only show content with these tags
#         tags: []
#         # Exclude content with these tags
#         exclude_tags: []
#         # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
#         kinds:
#           - project
#           - link
#           - page
#       # Field to sort by, such as Date or Title
#       sort_by: 'Date'
#       sort_ascending: false
#     design:
#       # See Page Builder docs for all section customization options.
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '2'
#       # Choose a listing view
#       view: card
#       # For Showcase view, flip alternate rows?
#       flip_alt_rows: false
---
