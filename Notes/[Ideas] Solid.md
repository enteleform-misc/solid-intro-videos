
<!--####################################################################################################################-->
# Notes
<!--####################################################################################################################-->

  - Solid Logo
    - animate

  - [0:01] "reactivity"
    - "reactive" animation
      - [React in 100 Seconds](https://www.youtube.com/watch?v=Tn6-PIqc4UM&t=41s)
    - show interaction between code & UI

  - remove realtime thoughts/considerations/decisions
    - ensure conciseness is consistent throughout video
    - refactor relevant content into planned, linear flow

  - target considerations
    - new developers ?
    - developers with basic framework experience ?
    - worth making multiple videos ?


<!--####################################################################################################################-->
# Refactor
<!--####################################################################################################################-->

  - break up code into fragments
    - think about relationship / sections / themes / etc


<!--####################################################################################################################-->
# Ideas
<!--####################################################################################################################-->

  - [flow 1] (based on original)
    - intro:
      - let's make a `<thing>`
      - show UI of `thing` in it's final state
      - explain what/why/how ?
    - core:
      - start simple, build up
        - code only ?
        - code + UI ?
        - how much emphasis on code VS breadth/overview ?

  - [flow 2] (overview, Fireship-style)
    - Solid Logo + animation
    - Reactive Framework
    - zoom out to list of prevalent frameworks
      - [runtime, compiled]
      - explain current state of web dev, where Solid fits in
        - why was solid created
          - to build upon predecessors that established <paradigms>
          - to resolve <issues> that are baked into predecessors that are now addressable via hindsight + improved technologies
        - goals
          - e.g. "to provide <x>"
          - ???
    - brief explanation of core primitives/structure
    - briefer mention of additional features
    - benefits afforded by Solid VS other frameworks
      - performance
        - render once
      - pure JS
        - allows free structuring
          - DEMO this, refactor reactivity from component to util file
      - how
        - compiler optimizations

  - [topics]
    - metrics
      - performance
      - benchmarks
      - comparison to other frameworks ?
    - call to action
      - what next
      - resources
      - subscribe, describe future content
      - join community, contribute, etc.
    - current state of web dev/paradigms/etc
      - how Solid fits in
    - hype
      - solid is dope
      - here's why you want to use it

  - [timeline]
    - Intro Video
      - WHAT / WHY / HOW
      - high-level overview, relevance to current state of web dev
    - First Tutorial
      - intro to reactivity in Solid
    - More Tutorials
      - come up with static/linear cluster of initial tutorials


<!--####################################################################################################################-->
# Reference
<!--####################################################################################################################-->

  - Existing Solid Content
    - [What is Solid? Intro Video Draft](https://www.youtube.com/watch?v=Fr-ZIhNnCmQ                                          )
    - [Ryan's Feedback                 ](https://discord.com/channels/722131463138705510/861229287868858379/938567585040056360)
    - [CoderPad interview w/ Ryan      ](https://www.twitch.tv/videos/1275982315                                              )
    - [Solid Intro Videos - Google Docs](https://docs.google.com/document/d/1XuINGmkwBeULd4Zoizk2bvvTebag9M5syxqs15Uv0go/edit )

  - Explainers
    - [React in 100 Seconds           ](https://www.youtube.com/watch?v=Tn6-PIqc4UM)
    - [Astro in 100 Seconds           ](https://www.youtube.com/watch?v=dsTXcSeAZq8)
    - [Vue.js Explained in 100 Seconds](https://www.youtube.com/watch?v=nhBVL41-_Cw)

  - Code Walkthroughs
    - [I built the same app 10 times // Which JS Framework is best?            ](https://www.youtube.com/watch?v=cuHDQhDhvPE&t=1038s)
    - [Build a Mindblowing 3D Portfolio Website // Three.js Beginner’s Tutorial](https://www.youtube.com/watch?v=Q7AOvWpIVHU        )
    - [I built a chat app in 7 minutes with React & Firebase                   ](https://www.youtube.com/watch?v=zQyrwxMPm88        )
    - [I built a decentralized chat dapp // GUN web3 Tutorial                  ](https://www.youtube.com/watch?v=J5x3OMXjgMc        )
    - [I created a Command Line Game for you // 5-Minute Node.js CLI Project   ](https://www.youtube.com/watch?v=_oHByo8tiEY        )
    - [TypeScript - The Basics                                                 ](https://www.youtube.com/watch?v=ahCwqrYpIuM        )

  - Documentation
    - [XState Docs                                              ](https://xstate.js.org/docs/                           )
    - [Introducing Astro: Ship Less JavaScript                  ](https://astro.build/blog/introducing-astro/           )
    - [Announcing The Astro Technology Company                  ](https://astro.build/blog/the-astro-technology-company/)
    - [Introduction — Vue.js                                    ](https://vuejs.org/v2/guide/                           )
    - [React – A JavaScript library for building user interfaces](https://reactjs.org/                                  )

  - Video Editing
    - [How I Make Videos for Programmers (on Fireship.io)                                            ](https://www.youtube.com/watch?v=N6-Q2dgodLs)
    - [World's Most Advanced Video Editing Tutorial (Premiere Pro) - Editing LTT from start to finish](https://www.youtube.com/watch?v=O6ERELse_QY)


<!--####################################################################################################################-->
# Dave's Notes
<!--####################################################################################################################-->

  - Definitely need to disable the error window popping up and the tooltip above the cursor as you're typing
  - Instead of using exponents as a learning concept, it might be best just to use counters and addition. ie. the typical "reactive explainer" uses the a, b, c example. So I suggest we change the intro to use basic summing and then modify the exponentiated function to be just "counted". It's a small detail but just brings it to basics
  - Pacing and breathing time between concepts could be better. The video is already very short, we can add in an extra minute to give you time to pause before shifting between concepts. The first part of the video goes rather quick, so I suggest a few pauses there specifically.
  - There are some "exciting" moments we need to taut ie. when you move state outside the component. The video ends with it, but I think it should reinforce the important/exciting aspect of it before closing out the video.
  - Can we state somewhere explicitly that "Solid utilizes JSX is a convenience DSL, taking advantage of it's powerful properties and large ecosystem". Obviously rephrase it, I just want to reinforce JSX as a major component and explain how it was helpful in making Solid extremely accessible to the avg developer.
  - If we can aim for a total video time of 7:30 or 8:00 that would be ideal
  - Can the conclusion have a few final sentence ie. "Thanks for watching this intro to Solid." maybe even draw attention to a second video? or better yet a CTA to draw them to try it out in the playground by mentioning playground.solidjs.com. We can use an embedded YouTube link to push them directly tot he sample you created in the video.


<!--####################################################################################################################-->
# FollowUp @ Discord
<!--####################################################################################################################-->

  - pitch [Intro, FirstVideo] release
    - get feedback for what [...InitialTutorialSeries] should look like

  - refine notes & share
    - philosophy, references, etc.
