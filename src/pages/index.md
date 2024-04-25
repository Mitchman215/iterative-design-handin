---
layout: ../layouts/CaseStudyLayout.astro
name: Iterative Design
---

# Iteractive Design

For this project, we partnered with a startup company called Warp to improve their app's onboarding experience for new users. Our team of 4 went through several iterations of the design process in order to produce a final high-fidelity prototype that we then presented back to the Warp design team.

## The Problem

Warp's app is a modernized developer terminal with built-in tools for collaboration and AI. Warp already had an existing onboarding experience for new users. At a high level, this experience consisted of downloading the app, signing up with an email, completing a marketing survey in a modal, then customizing the appearance of the app directly through the terminal interface.

We were tasked with improving and expanding this entire sequence, including finding a way to introduce some of Warp's features to users so they could easily determine if the app was suitable for them. Warp also wanted us to reduce friction so that users could get value out of the app faster and address some confusion that new users experienced.

## Initial Sketches

To generate ideas, each team member sketched 2 different possible flows of an improved onboarding sequence. The full sketches are viewable as pdfs separated by each member avaiable at the following links: [Emily](../iterative-design/sketches/emily-sketches.pdf), [Futen](../iterative-design/futen-sketches.pdf), [Joel](../iterative-design/joel-sketches.pdf), and [Mitchell](../iterative-design/mitchell-sketches.pdf). A few screenshots are included below to capture their essence.

![sample of emily's sketches](../images/emily-sample.jpg)

![sample of futen's sketches](../images/futen-sample.jpg)

![sample of joel's sketches](../images/joel-sample.jpg)

![sample of mitchell's sketches](../images/mitchell-sample.jpg)

There were quite a few aspects that our sketches differed on. For example, we came up with different ideas of how and where to present the marketing survey - some integrated it into the terminal experience directly and others kept it as a separate modal. We also differed in the medium we would use to introduce users to Warp's features, for example having it as a video walkthrough on the download page or a more interactive tutorial within the app.

## 1st Lofi Iteration

### Critique

The feedback we received from our peers included suggetsions regarding general formatting of our sketches and specific technical choices for ease of interpretation by the end users. Some suggestions included not having too much whitespace in our initial log-in/sing up screen in order to differentiate between the figma background and the frame background, making sure to include the scrollable history on all screens, and having consistent formatting across all the screens. Some thought the setup part might be confusing, especially for new developers, and suggestions included perhaps having a prompt before starting the technicals. One suggestion was to include some sort of progress indication regarding the length of the marketing survey and perhaps the entire onboarding experience. In addition, the "Other" option in the marketing survey with the included text box below it seemed confusing to some. Some points to consider were how multi-select would work within the clicking process, since a variable amount of options may be desired. Additional suggestions included having screens to introduce/transition between different parts of the first-time user experience (e.g. survey --> onboarding --> walkthrough), changing the name of the marketing survey to "intro survey" instead, and including a side panel that allows for between navigation and skipping through the onboarding experience.

The feedback we received from the client was quite sparse. Our contact suggested thinking about how the donwload flow would fit in to the process, since the first-time user experience is defined from the moment the user clicks "download" to the first 24 hours or even the first week of use. In additon, the suggestion to move the marketing survey into the "blocklist" or terminal view instead of the modal was repeated again.

## 2nd Lofi Iteration

Lofi 2nd-iteration Figma: <https://www.figma.com/file/50TYCr9AH0QHsNiBSxBS9W/Warp-Onboarding-Final?type=design&mode=design&t=Jn5SAC6rQsVRtICP-1>

We made a few noticeable changes to our first lo-fi mockup. The biggest change was to move the marketing survey into the "in-blocklist" terminal experience, as per suggested by our client. The primary reason for this was due to the fact that this suggestion had been repeated multiple times. Although we personally did not agree to the move as the optimal user experience, we felt that the opinion of the client should be prioritized over personal rationale regarding user optimality. We disagreed with incorporating the marketing survey into the in-blocklist terminal onboarding process mainly because we felt the dry rigor of clicking through a user survey offered little benefit to the first-time user, dimished incentive to continue with the onboarding process for Warp, and generally seemed out of place in such a critical time of experimentation for the first-time user. The process of clicking through questions one-at-a-time in the terminal does not seem conducive to providing the user with a broad overview of the features of Warp. It also brought up technical concerns regarding data transfer on the backend; the incorporation of the survey into the terminal allows for the viewing of one's history of survey responses, and the decision of whether to allow the user to change responses brought up considerations of when a user was considered to have completed a question and when the response data should be submitted to Warp. Furthermore, the need to potentially select multiple options within some questions surfaced concerns regarding whether a "finished" button was necessitated for each question. If so, the addition of such input between each question would only added to the tediousness of the process. We forewent the suggestion to change the name of the marketing survey, as that was the term colloquially used by our contact; we felt it was not apt to change a term they most likely already used within the company.

## Visual style guide

## High Fidelity Prototype

### Critique
