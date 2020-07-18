# browso
Vanilla HTML/CSS/JS browser-based presentation template

# Description:  
A browser based preso template. This template can be used by shell scripts or manual editing to turn 
a PPT deck into a self-guided, online presentation. It can be then be hosted on any platform that 
serves HTML pages and associated content.

# Why?:  
Corona.  The need to give pitches without being in the same meeting room is really what drove this.  The specific requirements that weren't met by other existing tools are:

      - Office Power Point on the Mac fails badly at HTML export. But that is still the source of 
      existing decks, example templates, and a common editing tool.
      - Requiring other people to install video-conf malware du jour... err. "meeting apps" is rude, 
      unreliable, and adds friction. (Most) everyone has a browser and a phone.
      - Asynchronous, self-guided presentation is a good option to have.  Think of it like Netflix for 
      presentations.  Your audience can consume on their schedule, not yours.
      - Enable things the web can do, that Power Point can't: links to supporting material, 
      click-through wire-frames integrated into presentation, in-line capture of feedback or questions, 
      performance tracking, etc.

# Current Features:
      - mobile-swipe, keyboard, and mouse-click controls
      - auto-play of presentation with configurable times per slide
      - auot-play of slide specific audio (narration)
      - per-slide notes sidebar, for supporting material, external links, etc.
      - table of contents sidebar to jump to specific slides
      - directly linkable slides for sharing, reference
      - single HTML page, no libraries or externals dependencies
      - minimal constraints, heavy commenting, native code to make editing as easy as possible

# Planned Features:
      - wire-frame or demo app click-through integration
      - in-line questions/feedback dialogue (requires server component)
      - perfromance tracking, telemetry, logging (requires server component)
      - meeting mode, presenter driven click-through (requires server component)

