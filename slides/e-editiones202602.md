---
_class: lead
_paginate: skip
backgroundColor: #fff
header: '<div style="display: flex; justify-content: space-between; align-items: center; width: 100%;"><img src="images/tei-publisher-logo-color.svg" width="220px" style="margin: 0;"><img src="images/e-editiones-logo-color-for-light-bg-05.svg" width="120px" style="margin: 0;"></div>'

marp: true
incremental: false
---

<style>
section {
  padding-top: 3rem !important;
}
header {
  /* background-color: #3a6a6a !important; */
  padding: 0.5rem 1rem;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  margin: 0;
  box-sizing: border-box;
  z-index: 1;
}
header div {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}
.images {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin-top: 1rem;
}
</style>

# Upgrading from TP 9

* no need to upgrade if you're happy with TP 9
* server-side API stayed the same
* `web components`, `tei-publisher-lib` work with all versions
* upgrade to Jinks requires manually recreating the app, but …

---

# Upgrade to Jinks workflow

* create new basic app
* file diff, identify and copy customized code
* code structure much better defined
* clear extension points via `config.json`

---
# Outlook

* TP 10 provides a fundament on which the community can build by
    * adding domain specific profiles
    * reusable blueprints, nice themes, workflow utilities
* community driven: *you* determine the roadmap

---

# In the works

* profiles for annotation and display targeted at DTA format
* theme following USWDS design system
* new DTS profile
…

---

# Funding

* the following institutions contributed funding to TEI Publisher 10 development:
    * Digital Humanities Lab (Jagiellonian University in Kraków)
    * Office of the Historian (US Department of State)
    * Polish Academy of Sciences
    * DASCH
* bigger part of development financed by Jinntec (150 days past 1.5 years)

---

# Problem

* our goal is to work ourselves out of the job
* in short time, AI will be able to handle many customization steps
* this is possible because *we humans* 
    * provide all the tools and the knowledge required
    * maintain and ensure the machinery is oiled
    * support the community in tricky situations
* the community must rethink its financing models and engagement