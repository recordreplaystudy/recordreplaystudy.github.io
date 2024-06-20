Android User Interface (UI) testing has emerged as an important and prevalent research topic due to the ubiquity of apps and the unique challenges faced by developers in this software domain. One popular topic of research that aims to facilitate both manual and automated UI testing and debugging processes is record and replay (R&R) tools. These tools allow for the recording of UI actions to facilitate the execution of test scenarios and the replay of various types of bugs. R&R tools typically support three main settings: (i) UI regression testing via R&R of feature-based execution scenarios, (ii) R&R of non-crashing functional bugs (e.g., in crowdsourced settings), and (iii) R&R of crashing bugs. 
Despite the progress made in research related to R&R tools, past approaches and studies only examine the effectiveness of these tools in disparate or fragmented settings. As such, the research community currently lacks a comprehensive examination of the effectiveness of existing tools across their common use cases and the potential key limitations that emerge.

We address this current gap in knowledge by conducting a thorough empirical study on using R&R tools to manually record and replay non-crashing failures, crashing bugs, and feature-based user scenarios. Additionally, we explore the possibility of using R&R tools in conjunction with AIG tools to automatically record and replay crashing bugs. Our study context includes one industrial and three academic R&R tools, 34 common user scenarios from 17 apps, 90 non-crashing failures from 42 Android apps, and 31 crashing bugs from 17 Android apps. Our results illustrate that 17% of execution scenarios, 38% of non-crashing bugs, and 44% of crashing bugs are not able to be reliably recorded and replayed, with the most prevalent reasons for non-replayability being action interval resolution, incompatibility related to APIs, and limitations in Android tooling. Our findings reveal important future research directions related to R&R tools that should facilitate their practical application and adoption.

## Key differences from prior relevant studies
![Figure 1: Key differences from prior relevant studies.](Figures/fig1.png?raw=true "Figure 1: Key differences from prior relevant studies.")

## Overview of the relationship of issue symptoms and root causes
![Figure 2: Overview of the relationship of issue symptoms and root causes.](Figures/fig2.png?raw=true "Figure 2: Overview of the relationship of issue symptoms and root causes.")

## Breakdown of failed cases in R&R process
![Figure 3: Breakdown of failed cases in R&R process.](Figures/fig3.png?raw=true "Figure 3: Breakdown of failed cases in R&R process.")

## Data Availability
Our data is available [here](https://drive.google.com/file/d/1fcRcWcjMVn06rHBJaDzc6ppNeOLEe0GI/view?usp=sharing).
