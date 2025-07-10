# FusionDev
Collection of Fusion Posts and Scripts

 ## Contents
- [FusionDev](#fusiondev)
  - [Contents](#contents)
  - [Warning](#warning)
  - [Why](#why)
  - [Installation](#installation)
  - [Okuma Mill](#okuma-mill)
    - [Functions](#functions)
    - [Trouble Shooting](#trouble-shooting)
  - [Okuma Lathe](#okuma-lathe)
    - [Functions](#functions)
    - [Trouble Shooting](#trouble-shooting)
## Warning
⚠ Warning & Release of Liability

Note that this is a work in progress. Changes will be made overtime. 

When using any Fusion 360 post processors from this repository, you assume full responsibility for their implementation. These posts can generate CNC machine motions and modify values, potentially leading to unexpected behavior, material waste, equipment damage, or personal injury if not properly reviewed and tested.

By using any files from this repository, you acknowledge and agree that:

- You fully understand how to verify the post-processed code before running it on a machine.
- You accept all risks associated with using these posts and assume responsibility for any outcomes.
- You will not hold the creator(s) of these posts liable for any damages, losses, injuries, or expenses resulting from their use.

⚠ Use at Your Own Risk! Always review, simulate, and test before running any generated code on actual machinery. If you are unsure, do not use these posts. 
Please ask questions on Stack Overflow using the `[okuma]` tag and report issues using the github issue reporting tool.

## Why

It's important to point out the reasons why these posts exists and why they might be more valuable to you than the ones on the fusion cloud library. First off, the ones on the cloud have issues. Some are more serious than others, such as the G16 H0 function on milling that will always crash unless you know how to modify the post, dangerous restart commands on lathe, or alarm prone code on both. Though no post is perfect, the goal here is to offer a more user friendly interface with better documentation and use clarification.

## Installation
 https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/How-to-add-a-Post-Processor-to-your-Personal-Posts-in-Fusion-360.html


## Okuma Mill 
The Milling post is intended to handle a few types of machines and a few control revisions. The list includes (but is not limited to) 3 and 4 axis, M560/460-V, MB-V, MB-H, MA-H, and M460/560 - 5AX. 
 ### Functions
 
 ### Trouble Shooting

## Okuma Lathe 
The Lathe post is intended to handle a few types of machines and a few control revisions. The list includes (but is not limited to) Genos-L and LB machines.

 ### Functions
 Add switch for Sub spindle VS tailstock
 Add witch for Milling
 Add switch for Y axis


 ### Trouble Shooting
  4304 No move without order after change offset: This alarm is created because the code did not specify exact motion of all moving axes. See this Okuma document LE61-420 for reference. https://1drv.ms/b/c/35075179a236ed1a/EahigsF-pBdFloGYSxQPP8UBFyZWSJe3YgOBAWR4tGHnmA?e=gnlbg8


